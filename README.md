# QRT Football Prediction Challenge ⚽

This repository contains my work for the **QRT Football Prediction Challenge**, where the objective is to predict outcomes and performance metrics for football matches using data analysis and machine learning techniques. Below, I describe my approach, progress, and enhancements made in each version of the notebooks.

📌 **Challenge Website:** [QRT Football Prediction Challenge](https://challengedata.ens.fr/participants/challenges/143/)

---

## Notebook Progression 📈

### 1. **`notebook_test.ipynb`**:
   - **Objective:** Initial exploration of the dataset.
   - **Key Steps:**
     - Basic data cleaning and preprocessing.
     - Exploratory Data Analysis (EDA) to understand the key features.
     - Studied the correlation matrix and feature importance to identify impactful variables.
     - Preliminary implementation of a simple baseline model.

---

### 2. **`notebook_test_version_2.ipynb`**:
   - **Updates:**
     - Removed highly correlated columns to reduce multicollinearity.
     - Added binary variables to indicate missing data for specific features.
     - Replaced missing values with the median.
     - Created new features, such as the win rate for teams.
     - Performed hyperparameter tuning using GridSearch for initial models.

---

### 3. **`notebook_test_version_3.ipynb`**:
   - **Updates:**
     - Integrated the player dataset for the first time.
     - Merged the player statistics with the match dataframe, adding mean and sum statistics for each player’s performance in a match.
     - Addressed columns with excessive missing values by determining an appropriate ratio for column removal.
     - Improved overall feature engineering to enhance model performance.

---

### 4. **`notebook_test_version_4.ipynb`**:
   - **Updates:**
     - Introduced additional player-related statistics, such as standard deviation and variance for player stats in matches.
     - Stopped removing columns with excessive missing values, opting for imputation and better handling of data sparsity.
     - Minor refinements to existing features and preprocessing steps.

---

### 5. **`notebook_test_version_5.ipynb`**:
   - **Updates:**
     - Finalized the preprocessing pipeline with minor adjustments.
     - Improved the handling of missing values and optimized feature engineering.
     - Focused on further improving interpretability and runtime efficiency for the final model.

---

## About the Challenge
The **QRT Football Prediction Challenge** is a data-driven competition aimed at leveraging machine learning and statistical techniques to predict football match outcomes. This repository showcases my learning journey and iterative progress throughout the competition.

📌 **Challenge Website:** [QRT Football Prediction Challenge](https://challengedata.ens.fr/participants/challenges/143/)

Feel free to explore the repository, and don’t hesitate to reach out with questions or feedback!
