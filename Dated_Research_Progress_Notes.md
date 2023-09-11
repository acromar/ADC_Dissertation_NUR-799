## Date: 08/31/2023

- **Data Download from CDC Website:**
On this date, all six (6) of the YRBSS data sets for the years 2009, 2011, 2013, 2015, 2017, and 2019 were downloaded from the official Centers for Disease Control and Prevention (CDC) website. The data was obtained using SPSS syntax to ensure accuracy and consistency. Following the download, the files were stored inside the "extData" directory of the repository.

- **Data Transformation from SPSS (.sav) to R (.rda) Format:**
On the same date, the SPSS (.sav) files containing the YRBS data were transformed into a more convenient and efficient format for inclusion in this research project. The data sets were converted to R (.rda) files, making them compatible with R and facilitating their seamless integration into this project's GitHub repository.

- **README File Creation and Documentation:**
The README file for the repository was created previously on August 30th, 2023. 
The README file serves as a comprehensive guide to the project, providing an overview of the repository's purpose, objectives, and data set descriptions. It also includes essential information on how to use this research project, dependencies, installation instructions, and data sources.

## Date: 09/01/2023

- **Completed Cleaning the YRBS 2019 Data**
Remarkable strides were made in annotating, cleaning, and otherwise tidying the YRBS 2019 data. The pre-processing and data wrangling processes are nearly finished, ensuring that the data is in optimal shape for further analysis efforts. Applying to the 2019 YRBS data set, multiple YRBS survey question modifications were identified between the annualized-cohort data sets, where a total of 13,677 survey respondent observations with 81 study variables were retained.

## Date: 09/06/2023

- **License Addition:**
To ensure proper licensing and usage guidelines, the appropriate license was added to the project on September 5th, 2023. This ensures clarity on how this project's data and code can be used, shared, and modified by others.

- **Completed Cleaning the YRBS 2017 to 2009 Data Sets **
Remarkable strides were made in annotating, cleaning, and otherwise tidying the five (5) remaining YRBS data sets from 2017 to 2009. The pre-processing and data wrangling processes are nearly finished, ensuring that these data sets are in optimal shape for further analysis efforts. Applying to the 2017 to 2009 YRBS data sets, multiple YRBS survey question modifications were identified between the annualized-cohort data sets, where a total of 14,765 (2017), 15,624 (2015), 13,583 (2013), 15,425 (2011), and 16,410 (2009) survey respondent observations with 81 (2017), 81 (2015), 79 (2013), 77 (2011), and 71 (2009) study variables were retained, respectively.

## Date: 09/11/2023

- **Completed Creating the YRBS Composite Data set**
Completed the column (study variables) renaming, annotating, cleaning, and otherwise tidying the six (6) YRBS data sets from 2019 to 2009. As part of these pre-processing and data-wrangling processes, these data sets were combined for further analysis efforts using the 'row bind' method. Applying that 'rbind' coding function (found in more detail via the 'Data_Pre-processing.Rmd' file) to the six (6) YRBS data sets from 2019 to 2009, the YRBS Composite Data set contains 101 columns (study variables) and a total of 89,484 survey respondent rows (observations) retained, respectively.
