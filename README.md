# Cricket Performance Analysis Using Machine Learning

## Overview
This project focuses on analyzing cricket batting and bowling performance metrics using Python and machine learning techniques. The goal is to uncover insights into player performance, predict key metrics like runs scored and wickets taken, and provide actionable recommendations for player selection and strategy formulation.

The project involves:
- **Data Preprocessing**: Cleaning and preparing cricket datasets for analysis.
- **Exploratory Data Analysis (EDA)**: Visualizing trends and relationships in player performance.
- **Feature Engineering**: Creating new features to better capture player performance.
- **Machine Learning**: Building and evaluating regression models to predict player performance.
- **Model Optimization**: Using GridSearchCV and RandomizedSearchCV to fine-tune hyperparameters.
- **Insights and Recommendations**: Drawing meaningful conclusions from the analysis.

---

## Dataset
The project uses two datasets:
1. **Batting Data**: Contains player statistics such as runs scored, balls faced, strike rate, boundaries, and milestones (50s and 100s).
2. **Bowling Data**: Includes metrics like wickets taken, runs conceded, overs bowled, and economy rate.

Both datasets were preprocessed to handle missing values, encode categorical variables, and normalize numerical features.

---

## Key Features
### 1. **Exploratory Data Analysis (EDA)**
- Visualized the distribution of runs, strike rates, and wickets using histograms and scatter plots.
- Analyzed correlations between features to identify key performance indicators (KPIs).
- Generated insights on the impact of boundaries, strike rate, and milestones on batting performance.

### 2. **Feature Engineering**
- Created new features such as:
  - **Weighted Runs**: Runs adjusted for boundaries (4s and 6s).
  - **Strike Rate Impact**: Impact of strike rate on overall performance.
  - **Weighted Batting Points**: A composite score combining runs, boundaries, and milestones.
- Normalized and scaled features to ensure consistency across the dataset.

### 3. **Machine Learning Models**
- Built and evaluated regression models to predict:
  - **Batting Performance**: Runs scored by players.
  - **Bowling Performance**: Wickets taken and economy rate.
- Used **Linear Regression** and **Random Forest Regressor** for modeling.
- Optimized hyperparameters using **GridSearchCV** and **RandomizedSearchCV** to improve model accuracy.

### 4. **Model Evaluation**
- Evaluated models using metrics such as **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)**.
- Achieved an MAE of **35.76** for predicting runs scored by players.
- Conducted feature importance analysis to understand the contribution of each feature to the model's predictions.

## Technologies Used
- Python (pandas, scikit-learn)
- Power BI for data visualization

## Folder Structure
- `data/`: Contains raw and cleaned datasets.
- `scripts/`: Python scripts for analysis and modeling.
- `results/`: Final outputs like dashboards and reports.

## Results
Improved recommendation accuracy by 15% using weighted ranking systems.

## How to Use
1. Download the repository files.
2. Run `scripts/model.ipynb` to execute the analysis.
