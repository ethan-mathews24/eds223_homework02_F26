# Exploring Patterns of Environmental Justice

![](images/EDS223.png)

<p align = "center">
<a href = "https://science.nasa.gov/mission/landsat/">Your Name in LANDSAT</a>
</p>


## Purpose of this Repository

This repository contains Homework 1 for EDS 223: Geospatial Analysis & Remote Sensing. The analysis explores the legacy of historical redlining in Los Angeles using Home Owners’ Loan Corporation (HOLC) grade designations. First, it combines HOLC data with the EPA’s EJScreen data at the census block group level to examine how redlining relates to present-day environmental justice conditions. Second, it uses pedestrian and bicycle crash and fatality data from the California Highway Patrol’s Statewide Integrated Traffic Records System (SWITRS) from 2020 to 2025, producing maps that show their spatial relationship to historical HOLC grades.


## Package Dependencies

* `tidyverse`

* `sf`

* `here`

* `tmap`

* `gt`


## File Structure

```
EDS223-HW2
├── data
│   ├── ejscreen
│   ├── mapping-inequality
│   └── SWITRS_LA
├── HW2.pdf
├── HW2.qmd
├── images
└── README.md
```


## Repository Contents

The `data` folder contains the data used for this analysis. 

The `images` folder contains images that were used for the README and results section.


## Results

INSERT MAPS' HERE


## Data Information/Access

#### EJSCREEN:

The data used for this analysis was from the United States Environmental Protection Agency’s previous EJScreen: Environmental Justice Screening and Mapping Tool found [here](https://www.epa.gov/ejscreen).

The tool, when in existence, was intended to support research and policy goals. It was shared with the public to be more transparent about how we consider environmental justice in our work and to assist  stakeholders in making informed decisions about pursuing environmental justice.

While the original tool is no longer available, an unofficial version can be found [here](https://pedp-ejscreen.azurewebsites.net/).


#### HOLC Redlining:

A team of researchers, led by the [Digital Scholarship Lab](https://dsl.richmond.edu/) at the University of Richmond have digitized maps and information from the HOLC as part of the [Mapping Inequality project](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58).

For this analysis, we worked with maps of HOLC grade designations for Los Angeles. Information on the data can be found [here](https://dsl.richmond.edu/panorama/redlining/data).


#### Bike and Pedestrian Crash Reports:

The Statewide Integrated Traffice Records System (SWITRS) database collects and processes data gathered from collision scenes. The data is hosted on the Transportation Information Mapping System (TIMS) which was developed by UC Berkley SafeTREC, accessed [here](https://tims.berkeley.edu/). The metadata can be found on the [SWITRS Codebook](https://tims.berkeley.edu/help/crashdata/switrs-codebook.php).

For this analysis, we worked with crash reports from 2020- 2025.


## Authors and Contributors 

Author: [Ethan Mathews](https://github.com/ethan-mathews24)

Contributor: [Annie Adams](https://github.com/annieradams)


## Citations

Public Environmental Data Partners. (2025). *EJScreen: Environmental Justice Screening and Mapping Tool*. Originally developed by U.S. Environmental Protection Agency, accessed October 15, 2026, pedp-ejscreen.azurewebsites.net/.

Robert K. Nelson, LaDale Winling, Richard Marciano, Nathan Connolly, et al. (2026) *Mapping Inequality, Redlining in New Deal America*, accessed October 15, 2023, https://dsl.richmond.edu/panorama/redlining/.

Transportation Injury Mapping System (TIMS). (2026). *Safe Transportation Research and Education Center*, University of California, Berkeley, https://tims.berkeley.edu/about.php.






