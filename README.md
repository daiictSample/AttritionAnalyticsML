# Employee Attrition Prediction

## Overview

This project uses machine learning to predict employee attrition based on HR data. Two algorithms are implemented and compared:

- **Logistic Regression** (with resampling to address class imbalance)
- **Random Forest Classifier**

## Files

## Approach 1: Logistic Regression with Resampling

- Used to establish a baseline for attrition prediction.
- Addressed class imbalance using SMOTE.
- Preprocessed data with label encoding and feature scaling.
- Evaluated with accuracy, precision, recall, and ROC-AUC.
- Key finding: [e.g., Overtime and JobSatisfaction were strong predictors.]

## Approach 2: Random Forest Classifier

- Chosen for its ability to handle non-linear relationships and feature importance analysis.
- Used same preprocessing as above.
- Tuned number of trees and max depth for best performance.
- Achieved higher accuracy and recall than logistic regression.
- Top features: [e.g., Age, MonthlyIncome, Overtime.]

## How to Run

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/employee-attrition.git
   cd employee-attrition/Attrition
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Open and run the notebooks:**
   - `logit_resample.ipynb`
   - `Random_forest.ipynb`

   *(Use Jupyter Notebook or VS Code with Jupyter extension.)*

## Results

| Model                | Accuracy | Precision | Recall | F1 Score |
|----------------------|----------|-----------|--------|----------|
| Logistic Regression  | 0.95     | 0.96      | 0.95   | 0.94     |
| Random Forest        | 0.96     | 0.95      | 0.96   | 0.95     |

*(Replace with your actual results. You can add confusion matrices or ROC curves as images if desired.)*



## License

MIT License

---
