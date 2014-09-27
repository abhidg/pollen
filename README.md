## pollen voting system

This is a work-in-progress. Following are the intended scripts:

Locations:

- votes are stored in `$output/private/slug/votes/`
- results are stored in `$output/private/slug/results/`

Scripts:

- **pollen-create**: creates and sets up the vote (index.py only)
- **pollen-pollinate**: emails the uuids to each person, stores in directory uuids/
- **pollen-collect**: collects the voting results; only run when the voting is over.
- **pollen-count**: counts and emails the results from results/
- **pollen-archive**: archives the entire folder


