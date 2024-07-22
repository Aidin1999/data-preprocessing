# Data Preprocessing Report

## Overview

This document outlines the data preprocessing phase of a project involving the merging of multiple datasets related to health data. The data processing involved integrating 107 datasets, each representing monthly records over a period of 10 years. The datasets were categorized into three separate files based on their features, and the final output is a consolidated file named `health_data_bristol.csv`.

## Data Files

The datasets were categorized into three main files based on the time periods they cover:

1. **2015-2017**: Contains health data from the years 2015 to 2017.
2. **2017-2018**: Includes data from the years 2017 to 2018.
3. **2018-2024**: Covers the period from 2018 to 2024.

## Preprocessing Steps

1. **Merging Datasets**:
   - **Objective**: Combine 107 datasets representing health data over a span of 10 years.
   - **Process**: The datasets were merged based on their temporal categorization into the files mentioned above.

2. **Data Cleaning**:
   - **Dropping Unnecessary Columns**: Columns that were not relevant to the analysis were removed from the datasets.
   - **Creating New Columns**: Additional columns were computed based on existing data to enhance the dataset's usefulness.

3. **Data Transformation**:
   - **Renaming Columns**: Column names were standardized to ensure consistency across datasets.
   - **Concatenating Data**: After cleaning and transforming the data, the datasets were concatenated into a single comprehensive dataset.

4. **Output**:
   - The final output, `health_data_bristol.csv`, consolidates all the processed data from the three files.

## Code and Functions

The data preprocessing was performed using a Jupyter Notebook named **`health_data_sort_and_clean.ipynb`**. This notebook includes the following:

- **Functions**: Developed to facilitate data processing and transformation, ensuring that the code is modular and understandable.
- **Visualizations**: To provide insights into the cleaned data and verify the preprocessing steps.

## Data Source

The original health data was downloaded from the NHS. The datasets were categorized and processed as described above to create a consolidated and clean dataset.

## Summary

In summary, this preprocessing phase involved merging, cleaning, and transforming health data spanning ten years. The output file, `health_data_bristol.csv`, serves as the final dataset ready for further analysis and visualization.

---

**Author:** Aidin Miralmasi

For additional details on the code and functions used, please refer to the Jupyter Notebook **`health_data_sort_and_clean.ipynb`**.
