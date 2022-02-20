# Census Peculiarities (In-Progress)

Data publication and documentation for a project on states' reallocation of prisoner populations in the U.S. 2020 Census. 


## Project goal

To understand the differences between the original census counts, states' department of corrections counts, and the ammended counts for states that reallocate prisoner residences to addresses before incarceration.  

## Project notes
### Notebooks

* [Exploring_DOC_numbers_vs_Census.ipynb](analysis/Exploring_DOC_numbers_vs_Census.ipynb) looks at the U.S. Census 2020 PL 94-171 data summary files for states at the block level compared to the Department of Corrections' Counts 
* [census_vs_adjusted_incarcerated_populations.ipynb](analysis/census_vs_adjusted_incarcerated_populations.ipynb) merges the U.S. Census 2020 PL 94-171 data summary files for states at the block level with the states' adjusted population files into one dataframe per state
* [CO-Identifying-Census-Blocks.ipynb](analysis/CO-Identifying-Census-Blocks.ipynb) is a notebook used for identifying census blocks in Colorado where DOC has incarcerated populations in facilities. 
* [NJ-adjusted-census-merged.ipynb](analysis/NJ-adjusted-census-merged.ipynb) merges New Jersey's 21 adjusted datasets for each county into one dataset for importing into the ccensus_vs_adjusted_incarcerated_populations notebook. 
* [VA-SQLite-adjusted-census-exploration.ipynb](analysis/VA-SQLite-adjusted-census-exploration.ipynb) is an exploration of Virginia's Adjusted Census files using SQLite to identify important tables for importing into the census_vs_adjusted_incarcerated_populations notebook.

### Data sources

* [Redistricting Data Hub](https://redistrictingdatahub.org/): Many state census and ammended census files were downloaded with the hub's API
* Individual state redistricting sites

## Technical

*TBD*


## Data notes

*TBD*
