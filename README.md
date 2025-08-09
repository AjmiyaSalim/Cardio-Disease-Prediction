# Heart Disease Prediction Using Machine Learning

## Project Overview

This project focuses on predicting the presence of heart disease using the `heart.csv` dataset. Heart disease is a major health concern worldwide, and early diagnosis through predictive modeling can greatly improve patient outcomes.

The machine learning models utilized here include **Decision Tree**, **Random Forest**, **XGBoost**, and a **Voting Classifier** ensemble — each chosen for their ability to handle classification tasks with varying complexity and robustness.

## About the Models

- **Decision Tree:** A simple and interpretable model that splits data based on feature values to make predictions. Prone to overfitting but easy to visualize.
- **Random Forest:** An ensemble of multiple decision trees trained on bootstrapped samples and random feature subsets, improving accuracy and reducing overfitting.
- **XGBoost (Extreme Gradient Boosting):** An advanced boosting algorithm that builds trees sequentially, optimizing errors with regularization and efficient computations.
- **Voting Classifier:** Combines predictions from multiple models (like the above) using majority voting or averaged probabilities to increase overall accuracy and stability.

These models provide a comprehensive comparison of single-tree, ensemble, boosting, and voting-based methods for heart disease classification.

## Dataset

- Source: `heart.csv`  
- Contains clinical data from patients including features like Age, Cholesterol, Resting Blood Pressure, and more.  
- Target variable: Indicates the presence (1) or absence (0) of heart disease.

## Key Steps

1. **Exploratory Data Analysis (EDA)**  
   - Inspect the dataset structure and summary statistics.  
   - Visualize feature distributions and relationships using plots such as histograms, jointplots, and pairplots.

2. **Data Preprocessing**  
   - Handle missing values and encode categorical variables as needed.  
   - Split the dataset into training and testing subsets.

3. **Model Training and Evaluation**  
   - Train Decision Tree, Random Forest, XGBoost, and Voting Classifier models with appropriate hyperparameters.  
   - Evaluate performance using accuracy, precision, recall, F1-score, and confusion matrices.  
   - Compare models to identify the best performer.

4. **Insights and Conclusion**  
   - Analyze the results and discuss the advantages of ensemble and boosting methods over single-tree models.  
   - Highlight that XGBoost and Voting Classifier achieved the highest accuracies and robust performance.

## Results Summary

- Decision Tree test accuracy: ~86.4%  
- Random Forest test accuracy: ~87.5%  
- XGBoost test accuracy: ~89.7%  
- Voting Classifier test accuracy: ~89.1%

XGBoost delivered the highest raw accuracy, while the Voting Classifier showed competitive performance with added robustness by combining multiple models.

## Requirements

- Python 3.x  
- Libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `seaborn`, `matplotlib`

---

*This project demonstrates an end-to-end approach to heart disease prediction using powerful machine learning techniques, providing a foundation for further exploration and deployment.*

