## Teleconfia Customer Churn Analysis

### Overview:
This repository contains a project focused on analyzing customer churn for Teleconfia, a telecommunications company establishing itself in the USA. The project aims to identify cities and individual customers at risk of churn and formulate targeted marketing campaigns to mitigate churn rates.

### Key Steps:
1. **Data Import**: Connect to the provided `telco_churn.db` database and load relevant tables into pandas DataFrames.
2. **Data Cleaning**: Inspect and clean the data to address missing values, inconsistencies, and outliers.
3. **City Churn Analysis**: Identify the four cities with the highest rates of customer churn.
4. **Predictive Modeling**:
   - Identify categorical, integer, and floating-point features to predict churn.
   - Determine thresholds and recommend which customers to target for retention efforts.
5. **Visualization**: Create visualizations to represent churn patterns in cities and selected data series.
6. **Recommendation**: Formulate recommendations for targeted marketing campaigns based on the analysis.

### Usage:
1. Clone the repository: `git clone https://github.com/your-username/teleconfia-churn-analysis.git`
2. Navigate to the project directory: `cd teleconfia-churn-analysis`
3. Explore the notebooks and data to understand the analysis process and findings.

### Data:
The project utilizes data stored in the `telco_churn.db` SQLite database. Various tables within the database provide information on customer demographics, usage patterns, and churn status.

### Requirements:
- Python 3.x
- pandas
- matplotlib
- scikit-learn
- SQLite3
