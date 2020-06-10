# activitysim_resources

Welcome to the [ActivitySim](https://activitysim.github.io/) datasets! This repository contains
the necessary data to perform a complete ActivitySim model for the [MTC](https://mtc.ca.gov/) Bay Area region in California.
The data is provided at several scales, including the entire 1475-TAZ region, as well as smaller
sub-regions with faster runtimes and lower memory overhead.

Configuration files can be found in the main [ActivitySim repository](https://github.com/ActivitySim/activitysim),
which also stores the 25-zone mini-example used for testing.

## Full scale model
- **skims.omx** - complete 1475 TAZ-TAZ OD matrices
- **persons.csv** - 7.5M persons
- **land_use** - TAZ attributes
- **households.csv** - 2.8M households

## San Francisco only
- **skims.omx** - SF area OD matrices of 190 TAZs
- **persons.csv** - 900k persons
- **land_use.csv** - TAZ attributes
- **households.csv** - 400k households
