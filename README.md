# CMPINF-Group-8

<<<<<<< HEAD
## What Is the Best Neighborhood in Pittsburgh?

This repository contains our group's final project for CMPINF 0010. We define "best" by combining two sub-metrics — higher education rate and green space availability — using data from the WPRDC to rank Pittsburgh neighborhoods.

---

## Team Members

| Name | Email | Notebook |
| Kevin Harned | krh220@pitt.edu | `kh final project.ipynb` |
| Sadia Azizi | saa981@pitt.edu | `Green Space Analysis.ipynb` |

**Canvas Group Number:** Final Project Group 8

> *Note: Our third group member was unable to participate due to a medical emergency. The professor approved our group submitting with two members.*

---

## Datasets Used

| Dataset | Source | Description |
| [School Enrollment by Race/Ethnicity](https://data.wprdc.org/) | WPRDC — American Community Survey 2015 | School enrollment broken down by grade level and race/ethnicity across Pittsburgh neighborhoods. Used to calculate the percentage of residents enrolled in college or graduate school. |
| [Green Spaces in Pittsburgh](https://data.wprdc.org/) | WPRDC | Locations of parks and green spaces across Pittsburgh neighborhoods. Used to count green space availability per neighborhood. |

---

## Sub-Metrics

- **Kevin — Higher Education Rate:** Percentage of a neighborhood's population enrolled in college undergraduate or graduate/professional programs. Calculated by combining enrollment data across all racial/ethnic groups.
- **Sadia — Green Space Availability:** Number of parks and green spaces located in each neighborhood.

---

## Repository Contents

- `README.md` — This file
- `kh final project.ipynb` — Kevin's individual analysis notebook
- `Green Space Analysis.ipynb` — Sadia's individual analysis notebook
- `CombinedNotebook.ipynb` — Combined presentation notebook with merged metric and conclusions from both members
- `higher_education_metric.csv` — Kevin's exported sub-metric data
- `green_spaces.csv` — Sadia's green spaces dataset

---

## How We Combined Our Metrics

Each sub-metric was normalized and weighted equally to produce a single combined score per neighborhood. The combined notebook contains the full methodology, visualizations, and our final answer for the best neighborhood in Pittsburgh.
=======
# What we define as the best: education, safety, health, & resources. 


# Pittsburgh Green Space Analysis Project

Green Space Explorers

## Team Members
- Sadia Azizi (saa981@pitt.edu)
- Partner 1 (email here)
- Partner 2 (email here)

---

## Project Overview
This project analyzes Pittsburgh neighborhoods to determine the “best neighborhood” using data from the Western Pennsylvania Regional Data Center (WPRDC).
Each team member created their own sub-metric using different datasets. These metrics were later used to compare neighborhoods and determine an overall “best” neighborhood in Pittsburgh.

---

## My Sub-Metric: Green Space Availability
My part of the project focuses on measuring how “green” each neighborhood is by counting the number of parks and green spaces in each area.

## Why this metric?
Green spaces improve:
- Physical health (exercise, outdoor activity)
- Mental health (stress reduction)
- Community engagement (public gathering spaces)

---

## Dataset Used
## Green Spaces Dataset (WPRDC)
- Source: Western Pennsylvania Regional Data Center  
- Link: https://data.wprdc.org/

This dataset contains information about parks and green areas located in different Pittsburgh neighborhoods.

---

## Methods
- Loaded dataset using pandas
- Counted green spaces per neighborhood using `value_counts()`
- Identified top neighborhoods
- Visualized results using a bar chart (matplotlib)
- Found the neighborhood with the highest number of green spaces using `idxmax()`
>>>>>>> 3dc2f4e (Added my Jupyter notebook)

---

## Result
<<<<<<< HEAD

See `CombinedNotebook.ipynb` for our final ranking and conclusion.
=======
Based on this metric, **East Liberty** has the highest number of green spaces and is considered the best neighborhood according to this analysis.

---

## Conclusion
This project demonstrates how data can be used to evaluate neighborhoods based on specific criteria. While green space is an important factor, other factors such as safety, education, transportation, and cost of living also influence what makes a neighborhood the “best.”

---

## Notes
- Each group member is responsible for their own dataset and analysis.
- All notebooks are included in this repository.
- This project follows the CMPINF final project requirements.
>>>>>>> 3dc2f4e (Added my Jupyter notebook)
