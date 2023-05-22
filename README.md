# Basic statistics and projects in R
This repository provides information and material for the [Basic Statistics and Projects in R](https://zuw.me/kurse/dt.php?kid=4474) course of the [Public Health Sciences Course Program](https://www.medizin.unibe.ch/studies/study_programs/phs_course_program) at the [University of Bern](https://www.unibe.ch).

## Preparation
Course participants will bring their own laptops with installed versions of [R](https://www.r-project.org) and [RStudio](https://posit.co/products/open-source/rstudio):

1. Download and install R by going to https://cloud.r-project.org/.
 - If you are a Windows user: Click on "Download R for Windows", then click on "base", then click on the Download link.
 - If you are macOS user: Click on "Download R for macOS", then under "Latest release:" click on R-X.X.X-arm64.pkg or R-X.X.X-x86_64.pkg for Apple silicon (M1/M2) or older Intel Macs, respectively.
 - If you are a Linux user: Click on "Download R for Linux" and choose your distribution for more information on installing R for your setup.
2. Download and install RStudio at https://posit.co/download/rstudio-desktop/.

## Short timetable
Day | Time | Topic | Lecturer(s)
--- | ---- | ----- | -----------
Friday, 2 June 2023 | 09:00-12:30 | Optional: Maths and probabilities refresher | Ben Spycher
Monday, 5 June 2023 | 09:00-12:00 | Projects in R: RStudio and tidyverse | Christian Althaus, Alan Haynes
Monday, 5 June 2023 | 13:00-17:00 | Projects in R: Data visualization using ggplot2 | Christian Althaus, Judith Bouman, Martin Wohlfender
Tuesday, 6 June 2023 | 09:00-12:30 | Projects in R: Reproducible reports and GitHub | Christian Althaus, Alan Haynes
Thursday, 8 June 2023 | 09:00-12:30 | Basic Statistics: Inference about the mean | Ben Spycher
Thursday, 8 June 2023 | 13:30-17:00 | Basic Statistics: Non-normal and dependent/paired data | Beatriz Vidondo
Friday, 9 June 2023 | 09:00-12:30 | Basic Statistics: Inference about proportions and rates | Ben Spycher
Friday, 9 June 2023 | 13:30-17:00 | Basic Statistics: Continue R project with a guided data analysis | Ben Spycher, Beatriz Vidondo

## Full timetable

### Friday morning, 2 June 2023 - Maths and probabilities refresher
Time | Duration | Topic | Content | Exercise | Lecturer(s)
---- | -------- | ----- | ------- | -------- | -----------
09:00-09:10 | 10 min | Introduction | Welcome - Overview content | - | Beatriz/Ben
09:10-09:25 | 15 min | Fundamentals | Sets, union, intersection, functions | Built-in questions | Ben 
09:25-09:40 | 15 min | Basic arithmetic| Solve a simple equation, $\Sigma$ / $\Pi$ notation  | White Board  | Ben 
09:40-10:05 | 15 min | Maximizing a function | intuitive explanation of derivatives  | WB | Ben 
10:05-10:20 | 15 min | Area under a function | intuitive explanation of integration  | WB  | Ben 
10:20-10:40 | 20 min | Exponentiation / logarithms | rules, exp/log functions | Built-in Qs | Ben 
10:40-10:00 | 20 min | Coffee break |   |  |
11:00-11:20 | 20 min | Probability | Basic rules, conditional probability, independence |  | Ben 
11:20-11:40 | 20 min | Random variables | discrete and continuous distributions |  | Ben 
11:40-12:00 | 20 min | Characterizing distributions | expectation, variance, covariance, transformations|  | Ben 
12:00-12:30 | 30 min | Specific distributions | Binomial, normal, Poisson | z-transformation | Ben 

### Monday morning, 5 June 2023 - Projects in R: RStudio and tidyverse
Time | Duration | Topic | Content | Exercise | Lecturer(s)
---- | -------- | ----- | ------- | -------- | -----------
09:00-09:10 | 10 min | General introduction | Lecturers and course program | - | All
09:10-09:40 | 30 min | Introduction to RStudio | Hands-on, functions, characters | - | Christian
09:40-09:50 | 10 min | Project organization | Files, names, etc. | - | Christian
09:50-10:00 | 10 min | Creating an R project | Template | 1 (10 min) | Christian
10:00-10:15 | 15 min | Base R and tidyverse | Concepts | - | Alan
10:15-10:30 | 15 min | Data | Import, CSV, Excel, REDCap, packages | 2 (10 min) | Alan
10:30-10:50 | 20 min | Coffee break | - | - | -
10:50-11:00 | 10 min | Data types | Dates, factors, boolean, numeric | - | Alan
11:00-12:00 | 60 min | Data wrangling | tidyverse, mutate, gtsummary()? | 3 (10 min) | Alan

#### Exercises
1. Create a project using a template directory with several files (10 min)
2. Read Excel and CSV files and look at data (look at types) (10 min)
3. Wrangle with data by calculating a BMI and format data (10 min)
	   
### Monday afternoon, 5 June 2023 - Projects in R: Data visualization using ggplot2
Time | Duration | Topic | Content | Exercise | Lecturer(s)
---- | -------- | ----- | ------- | -------- | -----------  
13:00-13:30 | 30 min | Data visualization | Base R vs. tidyverse/ggplot2 | - | Christian
13:30-14:30 | 60 min | Aesthetics | Size, shape, color, geom_point() | 4 (15 min) | Judith & Martin
14:30-14:50 | 20 min | Coffee break | - | - | -
14:50-15:50 | 60 min | Geometric objects | Other geoms | 5 (15 min) | Judith & Martin
15:50-16:10 | 20 min | Coffee break | - | - | -
16:10-16:25 | 15 min | Scales | | - | Judith & Martin
16:25-16:40 | 15 min | Themes | | - | Judith & Martin
16:40-17:00 | 20 min | Panels | Facets, patchwork, cowplot | 6 (15 min) | Judith & Martin

#### Exercises
4. geom_point() with size, shape, and color (15 min)
5. Other geoms (15 min)
6. Combining plots in a new theme (15 min)
 
### Tuesday morning, 6 June 2023 - Projects in R: Reproducible reports and GitHub
Time | Duration | Topic | Content | Exercise | Lecturer(s)
---- | -------- | ----- | ------- | -------- | ----------- 
09:00-10:00 | 60 min | Reproducible reports | Markdown, Quarto, etc. | 7 (15 min) | Christian
10:00-10:30 | 30 min | Coffee break | - | - | -
10:30-11:30 | 60 min | Version control and collaboration | Git/GitHub | 8 (15 min) | Alan
11:30-12:30 | 60 min | Publishing | GitHub Pages, Shiny apps?  | 9 (15 min) | Christian

#### Exercises
7. Reproducible report using Quarto (15 min)
8. Create a GitHub repository and push report (15 min)
9. Create a website using GitHub pages (15 min)

### Thursday morning, 8 June 2023 - Basic Statistics: Inference about the mean
Time | Duration | Topic | Content | Exercise | Lecturer(s)
---- | -------- | ----- | ------- | -------- | -----------
09:00-09:05 | 5 min | Intro | overview of topics, program | - | Beatriz, Ben
09:05-09:20 | 15 min | Descriptive statistics | data types, mean, median, variance, SD, IQR, R commands |  | Ben
09:20-09:35 | 15 min | Associations between continuous vars | pearson correlation| - | Ben
09:35-10:00 | 25 min | Exercise | descriptive stats, box plot, scatter plot, correlation | 10 | Ben
10:00-10:15 | 15 min | Coffee break | | |
10:15-10:20 | 5 min | Intro inferential statistics | Population, samples, statistics | - | Ben
10:05-10:25 | 15 min | CLT and normal distribution | SE of mean, central limit theorem, working with the normal distribution | - | Ben
10:25-10:40 | 15 min | Point and interval estimation for means | CIs for means (using normal approx) | - | Ben
10:40-11:05 | 15 min | Testing for differences in means | H0, H1, error types, p-values| - | Ben
11:05-11:30 | 25 min | Exercise | z-transformatiom, calculating probabilities using pnorm, manual CI, p calculation | 11 | Ben
11:30-11:45 | 15 min | Coffee break | | |
11:45-11:55 | 10 min | Inference about mean (small sample, normality) | t-distribution, CIs | - | Ben
11:55-12:05 | 10 min | Comparing means of independent samples | two-sample t-test, Welch's t-test test | - | Ben
12:05-12:15 | 10 min | Comparing means paired samples, multiple groups | paired-sample t-test, ANOVA | - | Ben
12:15-12:30 | 15 min | Exercise | Inference about means | 12 | Ben

#### Exercises
10.
11.
12.

### Thursday afternoon, 8 June 2023 - Basic Statistics: Non-normal and dependent/paired data            
Time | Duration | Topic | Content | Exercise | Lecturer(s)
---- | -------- | ----- | ------- | -------- | -----------
13:30-13:30 | 5 min | Intro | contents of afternoon | - | Beatriz
13:30-13:50 | 20 min | Non-Normality | Examples, QQ-plot, Normality tests | - | Beatriz
13:50-14:00 | 10 min | Comparing independent samples (non-normal) | Mann–Whitney U, Kruskal Wallis | - | Beatriz
14:00-14:30 | 30 min | Exercise | Mann–Whitney U, Kruskal Wallis test, multiple comp corrections | 13 | Beatriz
14:30-15:00 | 30 min | Coffee break | - | - | -
15:00-15:15 | 15 min | Associations between continuous vars | Spearman correlation | - | Beatriz
15:15-15:30 | 15 min | Exercise | correlation matrix, pairwise listwise deletion | 14 | Beatriz
15:30-15:50 | 20 min | Dependent/paired, clustered, panel data | Intraclass correlation coefficient ICC |  | Beatriz                   
15:50-16:30 | 10 min | Comparing paired samples (non-normal) | Wilcoxon signed rank |  | Beatriz
13:30-17:00 | 15 min | Exercise | calculate ICC, Wilcoxon signed rank | 15 | Beatriz                                          

#### Exercises
13. Non-normality, visualize, QQplots, Normality tests, Mann–Whitney U test, Kruskal Wallis
14. Correlation matrix, pairwise listwise missing values deletion
15. Calculate ICC, Wilcoxon signed rank

### Friday morning, 9 June 2023 - Basic Statistics: Inference about proportions and rates
Time | Duration | Topic | Content | Exercise | Lecturer(s)
---- | -------- | ----- | ------- | -------- | -----------
09:00-09:05 | 5 min | Intro | overview of topic, events and counts | - | Ben
09:05-09:25 | 20 min | Associations between categorical variables | contingency table, Chi2, Fisher's exact test ||
09:25-09:45 | 20 min | Exercise | tabulating data in R, extracting p-values of tests | 16 | Ben
09:45-10:00 | 15 min | Inference about a proportion | binomial distribution, CI (normal approx, exact binom)|  | Ben
10:00-10:15 | 15 min | Coffee break | | |
10:15-10:35 | 20 min | Differences in proportions | testing (normal approx), proptest | - | Ben
10:35-10:55 | 20 min | Ratio measures of association  | RR, OR | - | Ben
10:55-11:15 | 20 min | Exercise | tabulating data in R, extracting p-values of tests | 17 | Ben
11:15-11:30 | 15 min | Coffee break | | |
11:30-11:50 | 20 min | Inference about event rates | CI, testing (normal approx) for rates and IRR | - | Ben
11:50-12:10 | 20 min | Survival curve, Kaplan Meier | | - | Ben
12:10-12:30 | 20 min | Exercise | Survival curve, Kaplan Meier | 18 | Ben

#### Exercises
16.
17.
18.

### Friday afternoon, 9 June 2023 - Basic Statistics: Student's own work with R with guided data analysis
Time | Duration | Topic | Content | Exercise | Lecturer(s)
---- | -------- | ----- | ------- | -------- | -----------             
13:30-13:45 | 15 min | Introduction | Explanations of tasks | - | Ben, Beatriz
13:45-14:30 | 45 min | Descriptive part | describe dataset, variables, some plots, descriptive stats | | Students project
14:30-15:15 | 45 min | Analytical part | Point,  interval estimation, measure associations, compare two groups, decide  | | Students project
15:15-15:45 | 30 min | Coffee break | | |
15:45-16:30 | 45 min | Finish report | Write discussion, finalise, and upload | | Students project
16:30-17:00 | 30 min | Evaluation, Wrap up, Outlook other courses | | - | Ben, Beatriz
