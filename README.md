# Travel Insurance Dataset - Binary Classification Analysis

## Description
This project involves analyzing a travel insurance dataset to predict the 'Claim Status', a binary outcome indicating whether a claim was made ('Yes') or not ('No'). The analysis uses Logistic Regression, Random Forest, and XGBoost models to improve prediction accuracy and handle class imbalance.

## Data Sources
- [Travel Insurance Dataset](https://www.kaggle.com/datasets/mhdzahier/travel-insurance?select=travel+insurance.csv)

## Methodology
The analysis involves the following steps:
- Data Integrity: Missing entries imputed to ensure comprehensive analysis.
- Dataset Split: 80% training set for model building and 20% testing set for performance validation.
- Dataset Preparation: Features one-hot encoded to transform categorical variables for model compatibility.
- Model Training: Trained models to identify patterns indicative of claims.
- Cross-Validation: Applied five-fold cross-validation for robust model evaluation.
- Precision Tuning: Parameters fine-tuned to maximize prediction accuracy.
- Diverse Predictive Models: Employed Logistic Regression, Random Forest, and XGBoost for varied insights.
- Class Weight Adjustment: Implemented class weight adjustments to balance the influence of all classes.

## Key Insights
- **Baseline Model – Logistic Regression:**
  - Without Class Weight: High accuracy but low precision and recall, indicating the model mainly predicts the majority class (No Claims).
  - With Class Weight: Improved balance with better identification of the minority class (Claims).

- **Best Model – XGBoost:**
  - Training Performance: High accuracy, precision, recall, and F1 score, indicating excellent balance.
  - Test Performance: High accuracy but lower precision and recall due to class imbalance, suggesting overfitting.

## Files
- `Final Project Presentation.pptx`: PowerPoint presentation with visualizations of the analysis.
- `Final(Models with Adjustment).ipynb`: Jupyter notebook with models including class weight adjustments.
- `Final Project(Models without Adjustment).ipynb`: Jupyter notebook with models without class weight adjustments.
- `travel insurance.csv`: Dataset used for the analysis.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Ivie-Irivbogbe/travel-insurance-analysis.git

