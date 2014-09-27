## MCR Voting System

This is a work-in-progress. Following are the intended scripts:

Locations:

- votes are stored in `$output/private/slug/votes/`
- results are stored in `$output/private/slug/results/`

Scripts:

- **vote-create**: creates and sets up the vote (index.py only)
- **vote-email-uuids**: emails the uuids to each person, stores in directory uuids/
- **vote-collate**: collects the voting results; only run when the voting is over.
- **vote-count**: counts and emails the results from results/
- **vote-archive**: archives the entire folder


