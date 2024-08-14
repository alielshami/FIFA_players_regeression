<<<<<<< HEAD
# Regression Project

This project involves applying various regression models to a dataset containing player attributes. The goal is to predict the "overall_rating" of players based on other features.

## Project Overview

1. **Data File**: `regression_project_data.csv`
2. **Exploration and Visualization**:
   - Distribution of Player Ages
   - Nationality Count Plot
   - Overall Rating Distribution
   - Potential vs. Value Scatter Plot
   - Comments on the visualizations

3. **Data Preprocessing**:
   - Dropped Columns: `['full_name', 'birth_date', 'nationality', 'value_euro', 'wage_euro', 'preferred_foot', 'release_clause_euro', 'national_team', 'national_rating', 'national_team_position', 'national_jersey_number']`
   - Encoded Categorical Columns
   - Split Data into Features and Label (Target: `overall_rating`)
   - Dataset Split using `train_test_split`

4. **Regression Models Applied**:
   - Linear Regression
   - K-Nearest Neighbors (KNN)
   - Support Vector Regression (SVR)
   - Random Forest
   - Decision Tree
   - AdaBoost
   - XGBoost

5. **Model Evaluation**:
   - Evaluated Models using `r2_score`, `mean_absolute_error`, `mean_squared_error`, and `root_mean_squared_error`
   - Identified the Best Performing Model (Champion Model)


## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/repository-name.git
=======
# FIFA_players_regeression
This project involves applying various regression models to a dataset containing player attributes. The goal is to predict the "overall_rating" of players based on other features.
>>>>>>> origin/master
