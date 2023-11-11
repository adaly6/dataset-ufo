# UFO Sightings Dataset

This repository contains a dataset of UFO sightings scraped from [NUFORC]([https://nuforc.org/ndx/?id=event]) (National UFO Reporting Center). The dataset is compiled from multiple scripts and integrated into a comprehensive dataset.

## Data Details

- **Data Source:** The data is scraped from NUFORC using Selenium and Python scripts.
- **Current Status:** The dataset is regularly updated and integrated from monthly CSV files.
- **Data Integration Script:** [ufo_integration.R](monthly_sightings/ufo_integration.R) combines monthly CSV files into a single dataset.

## Data Dictionary

| Column         | Description                                              |
| -------------- | -------------------------------------------------------- |
| details        | Details about the sighting, including a hyperlink        |
| date           | Date and time of the sighting                            |
| city           | City where the sighting occurred                         |
| state          | State where the sighting occurred                        |
| country        | Country where the sighting occurred                      |
| shape          | Shape of the observed object                             |
| summary        | Summary or description of the sighting                   |
| report_date    | Date when the sighting was reported                      |
| posted_date    | Date when the sighting was posted on NUFORC              |
| image          | Link to an image related to the sighting                  |

## To-Do List

- [ ] Enhance data cleaning process.
- [ ] Explore additional features for analysis.
- [ ] Document any patterns or trends discovered in the dataset.

## Changelog

- **[Latest Entry]** Added the ufo_integration.R script to combine monthly CSV files (date: [11/10/2023]).

## Notes

- The data is collected using Selenium and Python scripts ([1_ufo_events_by_year_month.py](1_ufo_events_by_year_month.py), [2_ufo_by_month.py](2_ufo_by_month.py)).
- The scripts are available in the root folder.
