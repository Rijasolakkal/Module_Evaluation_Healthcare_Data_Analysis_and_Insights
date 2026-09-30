# Module_Evaluation_Healthcare_Data_Analysis_and_Insights
Healthcare data cleaning, transformation, analysis, visualization, and interactive dashboard creation using Excel and Power Query.
# Healthcare Data Analysis and Insights

## Project Overview

This project focuses on cleaning, transforming, analyzing, and visualizing healthcare data using Microsoft Excel and Power Query.

The project combines customer information, hospitalization details, and medical examination data into a single dataset for further analysis and dashboard creation.

## Data Preparation

The healthcare dataset was prepared by performing the following data cleaning and transformation tasks:

- Identified missing values represented by `?`
- Counted missing values in the relevant columns
- Handled missing Month and Year values using appropriate statistical methods
- Identified frequent values for categorical fields and used them to handle missing categorical data
- Standardized inconsistent values and capitalization
- Corrected inconsistent `Yes` / `No` entries
- Identified and handled data errors
- Removed duplicate records
- Transformed and combined date-related fields
- Calculated Age as of 8 June 2023
- Created Weight Status based on BMI
- Created Diabetes Status based on HBA1C
- Formatted Charges as currency
- Combined the Customer Names, Hospitalisation Details, and Medical Examinations data using Customer ID and VLOOKUP

## Data Transformation

### Weight Status

Weight Status was created based on BMI values:

- BMI below 18.5 → Underweight
- BMI 18.5 to below 25 → Normal weight
- BMI 25 to below 30 → Overweight
- BMI 30 and above → Obesity

### Diabetes Status

Diabetes Status was created based on HBA1C values:

- HBA1C below 5.7 → Normal
- HBA1C 5.7 to below 6.5 → Pre-diabetes
- HBA1C 6.5 and above → Diabetes

## Data Analysis

PivotTables and PivotCharts were used to analyze the healthcare data.

The analysis includes:

- Cancer history by smoking status
- Total major surgeries by transplant history
- Average HBA1C by transplant history
- Healthcare charges by Weight Status and Diabetes Status
- Average healthcare charges by Hospital Tier and State
- Relationships between Age and BMI
- Relationships between Age and HBA1C
- Relationships between Age and healthcare Charges

## Interactive Dashboard

An interactive Healthcare Analysis Dashboard was created using Excel.

The dashboard contains:

- PivotCharts
- Scatter charts
- Weight Status slicer
- Diabetes Status slicer
- Interactive filtering
- Healthcare charge analysis
- Medical and demographic relationship analysis

## Tools Used

- Microsoft Excel
- Power Query
- VLOOKUP
- PivotTables
- PivotCharts
- Slicers
- Scatter Charts
- Data Cleaning and Transformation
- Dashboard Creation

## Project Screenshots
- Screenshot attached for the reference.
