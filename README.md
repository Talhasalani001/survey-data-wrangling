# Data Cleaning and Wrangling Project

---

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Goals](#project-goals)
- [Methodology](#methodology)
- [Results](#results)
- [How to Run](#how-to-run)
- [File Structure](#file-structure)
- [Author](#author)

---

## Overview
This project showcases the use of Python and the Pandas library to clean, format, and analyze messy datasets. The goal is to develop a structured workflow for data cleaning and wrangling, which is a crucial skill for any data analytics or machine learning project.

---

## Dataset
The dataset used for this project is `580SurveyCleanup2.csv`, which contains responses to a survey. The survey includes questions Q1 to Q15, where Q1-Q14 are quantitative and Q15 is textual.  

The corresponding survey questions are provided in the file `580SurveyQuestion.pdf`.

---

## Project Goals
1. **Data Formatting**: Standardize and format the dataset to make it usable for further analysis.
2. **Data Cleaning**: 
   - Address missing values using appropriate techniques.
   - Resolve inconsistencies in the data, such as varying formats and duplicate entries.
   - Prepare the dataset for statistical analysis.
3. **Statistical Analysis and Insights**:
   - Generate descriptive statistics for survey responses.
   - Derive meaningful insights from the cleaned data, interpreting the results in the context of the survey questions.

---

## Methodology
### Step 1: Data Formatting
- Load the dataset into a Pandas DataFrame.
- Standardize column names and ensure consistent data types.
- Save the formatted dataset to a CSV file with the prefix `formatted_`.

### Step 2: Data Cleaning
- Identify columns with missing values and address them using imputation techniques:
  - **Numeric columns**: Filled using the mean or median values.
  - **Categorical columns**: Filled using the mode or logical placeholders.
- Standardize text data to handle inconsistencies like case sensitivity, whitespaces, and duplicate values.
- Save the cleaned dataset to a CSV file with the prefix `cleaned_`.

### Step 3: Statistical Analysis
- Use Pandas’ `describe()` function to compute summary statistics for survey responses Q1-Q14.
- Derive insights based on the statistical summaries and connect them to the corresponding survey questions.

---

## Results
### Key Outcomes
1. **Formatted Dataset**: The dataset was standardized to enable further analysis.
2. **Cleaned Dataset**: Missing values were imputed, inconsistencies resolved, and data was made ready for analysis.
3. **Insights from Statistical Analysis**: 
   - Identified trends, patterns, and behaviors from the survey responses.
   - Connected survey results to the original questions for meaningful interpretations.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/data-cleaning-wrangling.git
