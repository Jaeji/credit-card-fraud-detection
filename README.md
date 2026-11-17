# Credit Card Fraud Detection

A machine learning project that explores a synthetic credit card transaction dataset and compares tree-based classification models for identifying potentially fraudulent transactions.

## Project Objectives

- Prepare and inspect transaction data.
- Explore class imbalance and patterns associated with the target label.
- Train and compare multiple classification models.
- Evaluate model performance with metrics suited to an imbalanced classification problem.

## Workflow

1. **Data Cleaning** – Inspect data quality, remove duplicates, handle missing or malformed values, standardize categorical text, and check value ranges.
2. **Exploratory Data Analysis** – Examine the fraud class distribution and explore transaction characteristics by class.
3. **Preprocessing** – Encode categorical variables and use a stratified train/test split.
4. **Modeling** – Train and compare:
   - Decision Tree
   - Random Forest
   - XGBoost
5. **Evaluation** – Compare precision, recall, F1-score, classification reports, and confusion matrices. Feature importance is also examined where applicable.

## Tools & Technologies

- Python
- pandas, NumPy
- scikit-learn
- XGBoost
- Matplotlib / Seaborn
- Jupyter Notebook

## Repository Contents

- `credit_card_fraud_detection.ipynb` – Main analysis notebook.
- `requirements.txt` – Python package dependencies.
- `data/` – Directory for the input dataset (not included).

## How to Run

```bash
pip install -r requirements.txt
```

Place the dataset expected by the notebook in the `data/` directory, then run `credit_card_fraud_detection.ipynb` from top to bottom.

## Notes

The dataset used in this project is synthetic. Model outputs are analytical results from this dataset and should not be interpreted as validation on real-world banking transactions.
