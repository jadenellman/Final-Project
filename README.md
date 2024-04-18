# Examining Prevalence of Food Establishments, Obesity, and Socioeconomic Status in the U.S.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jadenellman/Final-Project/HEAD)

|              |                          |
|--------------|-------------------------:|
| Jaden Ellman |     *jnellma\@emory.edu* |
| Sanya Kumar  | *sanya.kumar\@emory.edu* |
| Zaim Zibran  | *zaim.zibran\@emory.edu* |

This project was completed for an undergraduate Technical Writing course at Emory University.

## Overview

The following is an exploratory data analysis of obesity and fast-food restaurants in America. Using an assortment of data science packages in R, we parse through and re-contextualize an extensive dataset of \~1.04 million observations to construct a computational narrative around fast-food's role in shaping American obesity trends, propose a statistical argument, and provide suggestions for future research in this field.

## Methods Used

-   Data Visualization

-   Intensive Data Cleaning

-   Distribution Measures

-   Correlation Analysis

-   Linear Regression Modeling

-   Time Series

-   Basic GIS Computations

## Programs/Languages Used

-   R

-   Rstudio

-   tidyverse

-   HTML

## Project Description

Our primary data comes from the National Neighborhood Archive (NaNDA) and features census data on population, demographics, and the presence of varying types of food and drink establishments at the census tract level. Using this data, we seek to examine whether the prevalence of fast-food restaurants in a given area can be used as a reliable predictor for local obesity and poverty rates. In doing so, we implement a mix of correlation plots, geospatial heatmaps, and distribution comparisons to observe establishment density (number of fast-food restaurants per 1000 residents) against obesity rate. We specifically look at food establishment data from 2007 and 2009, the years immediately before and after the onset of the Great Recession, to explore potential ramifications of widespread economic downturn. Our findings reflect and/or confirm those of existing studies, suggesting that the presence of fast-food restaurants in a given region correlate moderately with rising obesity, serving as a relatively reliable predictive measure for crucial health indicators.

Though our exploratory analysis was largely successful in its objectives, certain obstacles and potential next steps are worth mentioning. For instance, to capture the more localized implications of socioeconomic status, much of our analysis and visualization subsets the 5 richest and 5 poorest states in the nation for comparison. While this was done to make more readable visualizations given our intermediate level of expertise, we acknowledge that it is a rather arbitrary threshold, so future work with this data could develop a more robust approach to visualizing economic factors for all 50 states. Furthermore, while we had hoped to incorporate ethnic/racial demographics to examine the relationships between establishment density, obesity, and race, we were unable to access a suitable tract-level dataset given the scope and timeline of this project. Thus, we encourage future progress on this data to implement such a dataset to advance the discussion of American race relations.

## Instructions for Getting Started

1.  Clone this repository.

2.  Raw data used in the code can be found in [`main/data/`](https://github.com/jadenellman/Final-Project/tree/main/data).

3.  Before running any code, unzip the `nanda.csv.zip` file in `main/data/` to create the file `nanda.csv`. Keep this file in the `main/data/` folder to ensure the code runs properly.

4.  The executable code can be found in the root folder (`main/`) as an R Markdown file called `EDANotebook_Submit.Rmd`. In addition to the executable code, this file contains integrated textual analysis, comments, and data reference citations.

5.  A knitted HTML version of the R Markdown file is also included in the root folder as `EDANotebook_Submit.html`.

## Directory Structure

```         
.
└── main/
    ├── data/
    │   ├── .DS_Store
    │   ├── CDC Obesity 2022-overall-prevalence.csv
    │   └── nanda.csv.zip
    ├── renv/
    │   ├── .gitignore
    │   ├── activate.R
    │   └── settings.json
    ├── .DS_Store
    ├── .Rprofile
    ├── .gitignore
    ├── EDANotebook_Submit.Rmd
    ├── EDANotebook_Submit.html
    ├── Final Project.Rproj
    ├── README.md
    └── renv.lock
```
