# Basic statistics and projects in R
This repository provides information and material for the [Basic Statistics and Projects in R](https://zuw.me/kurse/dt.php?kid=4474) course of the [Public Health Sciences Course Program](https://www.medizin.unibe.ch/studies/study_programs/phs_course_program) at the [University of Bern](https://www.unibe.ch).

## Preparation
### Mandatory steps
Course participants will bring their own laptops with installed versions of [R](https://www.r-project.org), [RStudio](https://posit.co/products/open-source/rstudio), and [Git](https://git-scm.com):

1. [Download](https://cloud.r-project.org) and install R:
 - Windows: Click on "Download R for Windows", then click on "base", then click on the Download link.
 - macOS: Click on "Download R for macOS", then under "Latest release:" click on R-X.X.X-arm64.pkg or R-X.X.X-x86_64.pkg for Apple silicon (M1/M2) or older Intel Macs, respectively.
 - Linux: Click on "Download R for Linux" and choose your distribution for more information on installing R for your setup.
2. [Download](https://posit.co/download/rstudio-desktop) and install RStudio.
3. Install Git using the following [instructions](https://happygitwithr.com/install-git.html).
4. If you don’t already have one, don't forget to create a [GitHub](https://github.com) account.

### Optional steps
The following preparation steps are optional. You will also have time during the course to complete these steps.

1. Make sure RStudio knows about Git by following the corresponding section [here](https://sites.northwestern.edu/researchcomputing/resources/using-git-and-github-with-r-rstudio).
2. Install the [usethis](https://usethis.r-lib.org) package for R using the following command: `install.packages("usethis")`
3. Set up Git using the following command:
`usethis::use_git_config(user.name = "Jane Doe", user.email = "jane@example.org")`
4. Generate a personal access token (PAT) and store your PAT as described [here](https://happygitwithr.com/https-pat.html#get-a-pat).

## Timetable
Day | Time | Topic | Slides | Lecturer(s)
--- | ---- | ----- | ------ | -----------
Friday, 2 June 2023 | 09:00-12:30 | Optional: Maths and probabilities refresher | | Ben Spycher
Monday, 5 June 2023 | 09:00-12:00 | Projects in R: RStudio and tidyverse | [HTML](products/slides/2023_course_slides_1_wrangling.html) | Christian Althaus, Alan Haynes
Monday, 5 June 2023 | 13:00-17:00 | Projects in R: Data visualization using ggplot2 | [HTML](products/slides/2023_course_slides_2_dataviz.html) | Christian Althaus, Judith Bouman, Martin Wohlfender
Tuesday, 6 June 2023 | 09:00-12:30 | Projects in R: Reproducible reports and GitHub | [HTML](products/slides/2023_course_slides_3_reproducibility.html) | Christian Althaus, Alan Haynes
Thursday, 8 June 2023 | 09:00-12:30 | Basic Statistics: Inference about the mean | | Ben Spycher
Thursday, 8 June 2023 | 13:30-17:00 | Basic Statistics: Non-normal and dependent/paired data | | Beatriz Vidondo
Friday, 9 June 2023 | 09:00-12:30 | Basic Statistics: Inference about proportions and rates | | Ben Spycher
Friday, 9 June 2023 | 13:30-17:00 | Basic Statistics: Continue R project with a guided data analysis | | Ben Spycher, Beatriz Vidondo

## Slides
You can find all slides [here](products/slides).

## Exercises
You can find the exercises [here](products/exercises).

## Data sets
We will use the following data sets during the course:

File | Description | Source | exercise 
---- | ----------- | ------ | --------
[COVID19Cases_geoRegion.csv](data/raw/COVID19Cases_geoRegion.csv) | Laboratory-confirmed SARS-CoV-2 cases by region | [FOPH](https://www.covid19.admin.ch) |
[COVID19Cases_geoRegion_AKL10_w.csv](data/raw/COVID19Cases_geoRegion_AKL10_w.csv) | Laboratory-confirmed SARS-CoV-2 cases by region and age group | [FOPH](https://www.covid19.admin.ch) |
[covid_cantons_2020_06.csv](data/processed/covid_cantons_2020_06.csv) | Laboratory-confirmed SARS-CoV-2 cases for selected cantons and time period | [FOPH](https://www.covid19.admin.ch) |
[ebola.csv](data/raw/ebola.csv) | World-wide Ebola cases from 2014-2016  | [data.world](https://data.world/brianray/ebola-cases) | 4
[insurance_with_date.csv](data/raw/insurance_with_date.csv) | Data on costs of medical procedures | [kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance?resource=download) | 5


## Further online material
We recommend the following online tutorials and books on R and RStudio with specific applications to epidemiology, public health, and data science:

- [The R Manuals](https://rstudio.github.io/r-manuals/)
- [Hands-On Programming with R](https://rstudio-education.github.io/hopr)
- [The Epidemiologist R Handbook](https://epirhandbook.com/en/)
- [Introduction to R for Public Health Researchers](https://jhudatascience.org/intro_to_r/index.html)
- [R for Data Science](https://r4ds.had.co.nz)
- [Fundamentals of Data Visualization](https://clauswilke.com/dataviz)
