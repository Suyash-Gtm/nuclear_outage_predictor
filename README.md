# Nuclear Outage Risk Predictor

This project builds a basic classification model to identify outage-like months in the U.S. nuclear fleet, based solely on historical capacity factor values.

## ⚙️ Techniques Used
- Data loading and preprocessing from cleaned capacity factor dataset
- Binary target creation for "outage-like" conditions (<75% capacity factor)
- Model training using Random Forest classifier
- Evaluation using confusion matrix and precision/recall metrics

## 📈 Insights
This initial model uses raw historical performance as a predictor of reliability risk, providing a foundation for future enhancements like feature engineering, volatility indicators, and seasonality patterns.

## 📁 Files
- `nuclear_capacity_cleaned.csv`: Preprocessed dataset with outage labels
- `outage_prediction_model.ipynb`: Notebook with model training and performance diagnostics

