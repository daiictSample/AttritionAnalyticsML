# Employee Attrition Prediction

## Overview

This project uses machine learning to predict employee attrition based on HR data. Two algorithms are implemented and compared:

- **Logistic Regression** (with resampling to address class imbalance)
- **Random Forest Classifier**

## Files

- **logit_resample.ipynb**  
  Logistic Regression with data resampling, preprocessing, and evaluation.

- **Random_forest.ipynb**  
  Random Forest implementation, feature importance, and performance analysis.

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
