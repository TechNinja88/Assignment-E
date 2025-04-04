# Assignment E (California Schools Performance Analysis)

## Overview
This project analyzes the California Schools dataset to identify factors that influence school performance. It includes exploratory data analysis, supervised classification models, and unsupervised clustering techniques to discover patterns within the data.
## Dataset
The dataset contains information about California schools, including:
- Student demographics
- Socioeconomic indicators like CalWorks, lunch programs and income.
- Resource metrics like teachers, computers and expenditure.
- Performance outcomes like reading and math test scores.
Data source: [Rdatasets Repository](https://vincentarelbundock.github.io/Rdatasets/articles/data.html)
## Project Structure
- `analysis` - Data preprocessing and exploratory data analysis
- `supervised_learning` - Classification models (Logistic Regression and KNN)
- `unsupervised_learning` - Clustering algorithms (K-Means, Hierarchical, DBSCAN)
## Key Features
1. **Data Preprocessing**
   - Feature engineering (student-teacher ratio, disadvantage index)
   - Performance classification into Low/Medium/High categories
2. **Supervised Learning**
   - Logistic Regression with different regularization parameters
   - K-Nearest Neighbors with various k values
3. **Unsupervised Learning**
   - K-Means clustering with k values from 2-6
   - Hierarchical clustering with different linkage methods
   - DBSCAN with various eps and min_samples values
## Plots
you can find the plots in the `Part1_plots`, `Part2_plots`  and `Part3_plots`  folder. 