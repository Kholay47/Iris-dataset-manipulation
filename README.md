# Iris Dataset Analysis in R

## Repository Overview
This repository contains an analysis of the Iris dataset using R. The repository includes:
- `Iris.csv`: The dataset used for analysis.
- `iris.R`: The R script that performs various operations on the dataset.

## Files
- **Iris.csv**: A CSV file containing the famous Iris dataset.
- **iris.R**: An R script that reads and explores the dataset.

## R Script Overview
The `iris.R` script performs the following operations:

1. **Set and Get Working Directory**
   - `setwd("path/to/directory")`  
   - `getwd()`  

2. **Read the CSV File**
   - `data <- read.csv("Iris.csv")`

3. **Basic Dataset Information**
   - `dim(data)`: Get the dimensions (rows and columns) of the dataset.
   - `nrow(data)`: Get the number of rows.
   - `ncol(data)`: Get the number of columns.

4. **Preview Data**
   - `head(data)`: View the first few rows of the dataset.
   - `tail(data)`: View the last few rows of the dataset.

5. **Structure of Data**
   - `str(data)`: Get the structure of the dataset, including data types of each column.

6. **Summary Statistics**
   - `summary(data)`: Get summary statistics of the dataset.

7. **Check for Missing Values**
   - `sum(is.na(data))`: Count the number of missing values in the dataset.
