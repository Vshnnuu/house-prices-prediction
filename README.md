# House Prices Prediction (Kaggle Project)

This project predicts house sale prices using data from Kaggle’s *House Prices: Advanced Regression Techniques* challenge.

### 🔍 What I did
- Cleaned and engineered domain-specific features (e.g., total square footage, age, quality scores).
- Trained and blended Ridge, Lasso, XGBoost, and LightGBM models.
- Achieved **`~12% relative error`** on validation.
- Currently improving feature engineering to **push error below 12%**.

## 🔄UPDATE:
- Performed advanced feature engineering (TotalSF, TotalBath, Age, PorchSF, quality × area).
- Added leak-free K-Fold Target Encoding for `Neighborhood`.
- Rebuilt preprocessing to align train/test after new features.
- Generated 10-fold Out-of-Fold (OOF) predictions for stacking.
- Trained a Lasso meta-model to blend Ridge, Lasso, XGBoost, and LightGBM.
- Improved validation performance from **~12% error** to **~11.6% relative error** (OOF log-RMSE ≈ 0.1163).
- Achieved a Kaggle Leaderboard score of **0.12096** using the final stacked submission.

### 📁 Repo contents
- `house-price-prediction-v2-recovered.ipynb` — full Kaggle notebook (code)
- `house-price-prediction-v2.pdf` — rendered notebook in PDF
- `README.md` — this overview

### ⚙️ Tech stack
Python • pandas • scikit-learn • XGBoost • LightGBM • Matplotlib • Jupyter
