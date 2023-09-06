# ADC_Dissertation_NUR-799

> :warning: This research project is currently under development, application, analyses, and manuscript authoring

**Author:** Aaron Cromar.


**Description:** Welcome to my Dissertation_NUR-799 repository! This dissertation research project contains six (6) cleaned and annualized-cohort data sets/waves from the United States Centers for Disease Control and Prevention (CDC) Youth Risk Behavior Surveillance System (YRBSS) for the years 2009 to 2019. The primary purpose of this research project/study is to facilitate examination of the relational mechanisms between and underlying exposure-response correlations of mobile digital technology medias (MDTM) or social media (SM) usage, adolescent victimization (AV), depression or depressive symptomatology, and suicide-related behaviors (SRBs) among adolescents from 2009 to 2019 for the author's dissertation.

**Notes:** The progress notes are here [DATED_RESEARCH_PROGRESS_NOTES.md](Dated_Research_Progress_Notes.md).

## Run Me First

``` {r}
install.packages("remotes")

remotes::install_cran(
  c("conflicted", "tidyverse", "tidymodels", "knitr", "tidyREDCap", 
  "skimr", "gtsumamry", "themis", "vip", "table1", "gt", "janitor", "usethis"))

remotes::install_github()
```

## Raw YRBSS Data:

The `raw_2019YRBS.rds` file contains the raw data from the YRBSS for the year 2019.

The `raw_2017YRBS.rds` file contains the raw data from the YRBSS for the year 2017.

The `raw_2015YRBS.rds` file contains the raw data from the YRBSS for the year 2015.

The `raw_2013YRBS.rds` file contains the raw data from the YRBSS for the year 2013.

The `raw_2011YRBS.rds` file contains the raw data from the YRBSS for the year 2011.

The `raw_2009YRBS.rds` file contains the raw data from the YRBSS for the year 2009.

The YRBSS is a biennial survey conducted by the CDC to monitor health-risk behaviors among adolescents in the United States. The six (6) selected data sets/waves provides valuable information on various behaviors that contribute to the leading causes of death and other suicide-related behaviors among adolescents.

The YRBSS 2009 to 2019 data sets/waves includes a broad range of topical areas, such as:

- Behavioral Risk Factors: Information related to health-risk behaviors, including but not limited to MDTM or SM usage, amounts of sleep time, and lack of physical activity.

- Mental Health and Suicide-Related Data: Data pertaining to mental health issues, depression, self-harm, suicidal ideation, suicide planning, and suicide attempts among adolescents.

- Demographic Information: Basic demographic details such as survey respondents' age, sex/gender identification, sexual orientation, race/ethnicity background, and grade level.

- Violence and Safety: Information about experiences with adolescent victimization (AV), dating or sexual-related violence, bullying, cyberbullying, and other relational social aggression (RSA) safety concerns.

## License:

The project is currently under [CC0 license](https://choosealicense.com/licenses/cc0-1.0/). Please refer to the LICENSE.md file for more details.

## Directories:

**`data` Directory:**
- This directory folder contains the six (6) essential cleaned YRBS data sets/waves used in this study project.

- "clean_2019YRBS.rds": The cleaned version of the 2019 YRBS data set, which generates after running the "Cleaning_2019YRBS_data.Rmd" script.
- "clean_2017YRBS.rds": The cleaned version of the 2017 YRBS data set, which generates after running the "Cleaning_2017YRBS_data.Rmd" script.
- "clean_2015YRBS.rds": The cleaned version of the 2015 YRBS data set, which generates after running the "Cleaning_2015YRBS_data.Rmd" script.
- "clean_2013YRBS.rds": The cleaned version of the 2013 YRBS data set, which generates after running the "Cleaning_2013YRBS_data.Rmd" script.
- "clean_2011YRBS.rds": The cleaned version of the 2011 YRBS data set, which generates after running the "Cleaning_2011YRBS_data.Rmd" script.
- "clean_2009YRBS.rds": The cleaned version of the 2009 YRBS data set, which generates after running the "Cleaning_2009YRBS_data.Rmd" script.

**`inst` Directory:**

**'extData' Directory:**
- This directory folder contains the necessary files used during the YRBSS data retrieval process.

- The YRBS Data Users Guides (.pdf) files used to download and interpret the raw YRBS data sets/waves from the official CDC YRBSS website.

- The SPSS syntax (.sps) files used to download the raw YRBS data sets/waves from the official CDC YRBSS website.

- The ASCII (.dat) files required for data conversion during the SPSS.sav-to-R.rds transformation.

- The raw SPSS (.sav) data sets/waves downloaded from the CDC YRBSS website, before conversion to R (.rds) format:

- "raw2019YRBS.rds": The raw data set/wave for the year 2019, transformed and saved as an (.rds) file for easy integration and analysis in R.
- "raw2017YRBS.rds": The raw data set/wave for the year 2017, similarly transformed and stored as an (.rds) file.
- "raw2015YRBS.rds": The raw data set/wave for the year 2015, similarly transformed and stored as an (.rds) file.
- "raw2013YRBS.rds": The raw data set/wave for the year 2013, similarly transformed and stored as an (.rds) file.
- "raw2011YRBS.rds": The raw data set/wave for the year 2011, similarly transformed and stored as an (.rds) file.
- "raw2009YRBS.rds": The raw data set/wave for the year 2009, similarly transformed and stored as an (.rds) file.

**'scripts' Directory:**
- This directory folder contains the scripts utilized throughout the YRBS data cleaning and R (.rds) file creation processes.

## Ordered Data Analysis Pipeline/Workflow:

Run these files in order from raw YRBS processing to publication:

1.inst/extData/2019XXH_SPSS.sps and 2019YRBS-SPSS.sav
2.inst/extData/2017XXH_SPSS.sps and 2017YRBS-SPSS.sav
3.inst/extData/2015XXH_SPSS.sps and 2015YRBS-SPSS.sav
4.inst/extData/2013XXH_SPSS.sps and 2013YRBS-SPSS.sav
5.inst/extData/2011XXH_SPSS.sps and 2011YRBS-SPSS.sav
6.inst/extData/2009XXH_SPSS.sps and 2009YRBS-SPSS.sav
7.inst/scripts/Importing_YRBS_data.Rmd
8.inst/scripts/Cleaning_2019YRBS_data.Rmd
9.inst/scripts/Cleaning_2017YRBS_data.Rmd
10.inst/scripts/Cleaning_2015YRBS_data.Rmd
11.inst/scripts/Cleaning_2013YRBS_data.Rmd
12.inst/scripts/Cleaning_2011YRBS_data.Rmd
13.inst/scripts/Cleaning_2009YRBS_data.Rmd