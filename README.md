# CMPINF-Group-8

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
- `kevin_higher_education.ipynb` — Kevin's individual analysis notebook
- `sadia_green_spaces.ipynb` — Sadia's individual analysis notebook
- `final_project_combined.ipynb` — Combined presentation notebook with merged metric and conclusions from both members
- `higher_education_metric.csv` — Kevin's exported sub-metric data
- `green_spaces.csv` — Sadia's green spaces dataset

---

## How We Combined Our Metrics

Each sub-metric was normalized and weighted equally to produce a single combined score per neighborhood. The combined notebook contains the full methodology, visualizations, and our final answer for the best neighborhood in Pittsburgh.

---

## Result

See `final_project_combined.ipynb` for our final ranking and conclusion.
