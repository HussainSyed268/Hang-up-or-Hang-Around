# Hang up or Hang Around: Telecommunication Churn Data Analysis

"Hang up or Hang Around" is a data analysis project focused on understanding customer churn in the telecommunications industry. Using a comprehensive churn dataset, this project explores factors influencing customer attrition and employs various analysis techniques to identify patterns and insights. The insights derived can help telecom companies enhance their retention strategies and reduce churn rates.

## Project Overview

This project involves the following steps:

1. **Data Preprocessing**:
   - Handling missing values in the dataset.
   - Converting data types for appropriate analysis.
   - Cleaning the dataset to ensure consistency and accuracy.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizing and summarizing the dataset to uncover initial insights.
   - Analyzing numeric columns with bar charts to understand their relationship with churn.
   - Investigating categorical features and their relationship with churn using count plots and crosstab analysis.

3. **Categorical Analysis**:
   - Identifying unique values in categorical columns and their distributions.
   - Creating visualizations to show the distribution of churn labels across different categories.

4. **Numerical Analysis**:
   - Exploring numerical features and their impact on churn.
   - Using scatter plots, KDE plots, and box plots to analyze the relationship between numerical features and churn score.
   - Applying log transformation to handle skewness in numerical data.

5. **Association Rules**:
   - Using the Apriori algorithm to identify frequent patterns in service usage.
   - Generating association rules to uncover relationships between different services.

6. **Correlation Analysis**:
   - Examining the relationships between numerical features using Pearson’s correlation matrix.
   - Visualizing the correlation matrix to identify significant correlations.

7. **Nearest Neighbor Search**:
   - Implementing MinHash and LSH (Locality-Sensitive Hashing) to find similar customers.
   - Encoding categorical features and creating MinHash objects for each customer.
   - Building a MinHashLSHForest index to perform nearest neighbor search and identify similar customers based on selected features.

## Dependencies

The project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- plotly
- datasketch
- scikit-learn

## How to Use

1. **Clone this repository**:
    ```sh
    git clone https://github.com/HussainSyed268/hang-up-or-hang-around.git
    ```

2. **Navigate to the project directory**:
    ```sh
    cd hang-up-or-hang-around
    ```

3. **Install the required dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook to explore the analysis**:
    ```sh
    jupyter notebook Hang_up_or_Hang_around.ipynb
    ```
