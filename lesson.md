# Land carbon module

## Overview

Analyzing data that are spread across tables in database is widely used skill in data science.  This module developes these skills in the context of calculating forest carbon stocks from standard forest inventory measurements.

-   author: Quinn Thomas (@rqthomas)
-   contact: [rqthomas\@vt.edu](mailto:rqthomas@vt.edu){.email}
-   date: 2023-01-03
-   license: MIT, CC-BY
-   copyright: Quinn Thomas

## Feedback

<https://github.com/frec3044/land-carbon/issues>

## Questions

How much carbon is stored in different forests across the U.S.?

## Ojectives

- Demonstrate how to join tables to construct a dataset for analysis
- Demonstrate how to access tables from a database
- Calculate forest carbon stocks from forest inventory data
- Compare forest carbon stocks across locations and explain drivers of differences

## R packages used

- `duckdb` for database access
- `DBI` for database access
- `tidyverse` for read, joining, analyzing, and visualizing data
- `knitr` for printing tables

## Instructions

  - Open the notebook `assignment/land-carbon.qmd` in RStudio
  - Work through the exercises described in the notebook.
  - `Render` + commit output files to GitHub

## Context

This module has been developed a module in a junior-level Environmental Data Science course at Virginia Tech.  The course is required for majors in the Environmental Data Science degree.  The course has a pre-requisite course that introduces students to tidyverse concepts.  It assumes that students have a set of Git and GitHub and understand how to commit and push through Rstudio.

## Timeframe

2-weeks (4 75-minute class periods are allocated to this module)

## Background Reading

The background reading is embedded in the assignment Quarto document as links to the relevant sections of [R for Data Science book (2nd edition)](https://r4ds.hadley.nz) by Hadley Wickham, Mine Çetinkaya-Rundel, and Garrett Grolemund.
