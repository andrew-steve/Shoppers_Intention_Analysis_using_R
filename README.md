## Online Retail Store Shopper's Intention Analysis

### Introduction
This repository contains R code for the analysis of online retail store shopper's intention. The analysis includes exploratory data analysis (EDA) to understand the dataset and machine learning models for predicting shopper's purchase intention.

### Dataset
The dataset used in this analysis is named "Online retail store shoppers intention.csv". It contains various features related to online shopping behavior, including page interactions, duration, visitor types, and more.

### Libraries Used
- **tidyverse**: A collection of R packages designed for data science, including ggplot2 for data visualization.
- **gridExtra**: Provides functions to arrange multiple grid-based plots on a page.
- **psych**: Provides functions for psychological research.
- **reshape2**: Allows restructuring and aggregating data.
- **rpart**: Implements decision tree algorithms.
- **rpart.plot**: Produces plot of decision trees.
- **randomForest**: Implements random forest algorithms.
- **caret**: Provides a unified interface for various machine learning models.
- **recipes**: Provides pre-processing methods for modeling.
- **purrr**: Functional programming tools.
- **stringr**: String manipulation functions.

### Analysis Steps

1. **Importing Libraries**: Necessary R libraries are imported.
2. **Importing the Dataset**: The dataset is loaded into the R environment using the `read.csv()` function.
3. **Summary Statistics**: Summary statistics are computed using functions like `summary()`, `describe()`, `glimpse()`, and `str()` to understand the dataset's structure and contents.
4. **Missing Values Check**: Missing values in the dataset are checked using `colSums(is.na(df))`.
5. **Visualization**:
   - Distribution of the dependent variable (`Revenue`) is visualized using bar plots.
   - Distribution of numerical variables (`BounceRates` and `ExitRates`) is visualized using histograms.
6. **Exploratory Data Analysis (EDA)**:
   - Page interaction analysis is performed, and average page counts by page type and revenue are visualized.
   - Page duration analysis is performed, and average page duration by page type and revenue are visualized.
   - Time duration visitors spend on each page type is analyzed and visualized.
   - Visitor type numbers are analyzed and visualized.
   - User interaction with webpages is analyzed and visualized.
   - Browser and operating system analysis for buyers is performed and visualized.
7. **Machine Learning**:
   - Decision Tree Algorithm: A decision tree model is built to predict whether a user makes a purchase.
   - Random Forest Algorithm: A random forest classifier is trained and evaluated to predict purchase intention.

### Conclusion
This repository provides a comprehensive analysis of online retail store shopper's intention, including data visualization, exploratory data analysis, and machine learning modeling. The analysis aims to provide insights into shopper behavior and predictive models for purchase intention.
