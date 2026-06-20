# Fertilizer Recommendation with Tree-Based Models

This project predicts fertilizer recommendations from soil conditions, crop type, and nutrient levels. It compares three tree-based classifiers and uses the best-performing model for example recommendations.

## Models

- Decision Tree
- Gradient Boosting Machine
- XGBoost

No trained model files are saved in this workflow.

## Results

On the current train/test split:

| Model | Accuracy | Weighted F1 |
| --- | ---: | ---: |
| XGBoost | 1.0000 | 1.0000 |
| Decision Tree | 0.9500 | 0.9533 |
| Gradient Boosting Machine | 0.9500 | 0.9473 |

Best model: `XGBoost`

## Files

```text
Fertilizer_Recommendation_Tree_Models.ipynb
data/
  fertilizer_prediction.csv
README.md
```



## How to Run

Install the required packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

Open and run:

```text
Fertilizer_Recommendation_Tree_Models.ipynb
```

