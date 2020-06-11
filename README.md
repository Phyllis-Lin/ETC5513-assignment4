# Distribution of Job Postings Across Australia in 2018

## :clipboard: About the repository

This repository provides an exploratory data analysis on job postings across Australia in 2018.  We analysed the changes in job demand in 2018 by:

1. job category
2. states
3. job type

We also performed a correlation test between the number of job postings in some big cities with more job postings and the living cost there.

##  :bar_chart: Data Source

The job postings data set was downloaded from [Kaggle](https://www.kaggle.com/PromptCloudHQ/australian-job-listings-data-from-seek-job-board) and provided by [PromptCloud](https://www.promptcloud.com), a web-scraping company. Originally, this data was scraped from [Seek](https://www.seek.com.au) job board. This data set has a [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license, where people are free to share and adapt the data.

The living cost dataset was scraped from the table of Cost Living Index by City 2018 in [Numbeo](https://www.numbeo.com/cost-of-living/rankings.jsp?title=2018). From the [website’s term of use](https://www.numbeo.com/common/terms_of_use.jsp), it is mentioned that use, reuse, and distribution of Numbeo’s content are allowed.

## :wrench: Environment

Data analysis and report are produced using R in R studio. The packages used are:

1. `tidyverse`
2. `ggplot2`
3. `lubridate`
4. `knitr`
5. `naniar`
6. `polite`
7. `rvest`
8. `xml2`
9. `readr`
10. `forcats`
11. `kableExtra`
12. `tidyr`
13. `glue`
14. `MonashEBSTemplates`
15. `Rmarkdown`
16. `bookdown`
17. `tinytex`

## :closed_lock_with_key: License
The license of this repository is MIT License.

## :books: Output
The final output of this repository is a pdf file using LaTeX format.
