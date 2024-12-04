# ReadMe
Author: Danyang Zhang
# ADA Final Project
## Project Description
This project analyzes the association between food security status and diabetes status, and other demographic and health variables using data from the National Health and Nutrition Examination Survey (NHANES) from 2017 to March 2020 Pre-pandemic. The primary objective is to determine the impact of food insecurity on diabetes prevalence among adults and explore confounding factors like age, PIR, race, and educational level.

## Code Description
The R Markdown document (ADA_Final) includes several sections of R code which perform the following functions:
-Data Import and Installation: Installs necessary packages and imports data from SAS format files into R using the haven package.
-Data Merging and Cleaning: Combines multiple datasets and filters out incomplete entries to ensure a robust analysis.
-Descriptive Statistics: Generates descriptive statistics and visualizations to understand the data distribution.
-Advanced Data Analysis: Conducts logistic regression to explore associations between food security and diabetes, using likelihood ratio test to test if confounding factors will affect model fit. It also performs chi-square tests for categorical comparisons and t-test for continuous variables, and calculates weighted averages using survey methods.

## Dataset Description
The datasets used include multiple .XPT files from NHANES that contain demographic information, diabetes status, food security status, and BMI data:

-P_DEMO.XPT: Demographic variables
-P_DIQ.XPT: Diabetes status
-P_FSQ.XPT: Food security status
-P_BMX.XPT: Body mass index data
-These files are merged and processed to create a comprehensive dataset for analysis. The cleaned data is stored locally and used for subsequent statistical testing.

## Installation
To run the code, you need to install R and RStudio. Use the following commands in RStudio to install necessary packages:
-install.packages("haven")
-install.packages("dplyr")
-install.packages("pacman")
-install.packages("survey")

## Usage
-Open the Final project code_Danyang .Rmd file in RStudio. Ensure that all data files are in the specified directory: /Users/danyang/Library/CloudStorage/Box-Box/FL2024/ADA/Final code
-To generate the final document, click on the "Knit" button in RStudio. This will compile the report, executing all R code chunks and rendering them along with the narrative you've provided into an HTML, PDF, or Word document, based on your output settings in the YAML header.

## Contributing
Contributions to this project are welcome. You can contribute by:
-Improving the efficiency of the R code.
-Enhancing the data visualization.
-Expanding the analysis to include more variables from NHANES.
-To contribute, please fork the repository, make your changes, and submit a pull request.

## Contact Information
For support or collaboration, please email danyang.z@wustl.edu

