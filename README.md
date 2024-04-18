# Examining Prevalence of Food Establishments, Obesity, and Socioeconomic Status in the U.S.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jadenellman/Final-Project/HEAD)

|              |                          |
|--------------|-------------------------:|
| Jaden Ellman |     *jnellma\@emory.edu* |
| Sanya Kumar  | *sanya.kumar\@emory.edu* |
| Zaim Zibran  | *zaim.zibran\@emory.edu* |

This project was completed for an undergraduate Technical Writing course at Emory University.

## Overview

[]

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

Our primary data comes from the National Neighborhood Archive (NaNDA) and features census data on population, demographics, and the presence of varying types of food and drink establishments at the census tract level. Using this data, we seek to examine whether the prevalence of fast-food restaurants in a given area can be used as a reliable predictor for local obesity and poverty rates.

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
