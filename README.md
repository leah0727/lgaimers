# LG Aimers: Predicting Pregnancy Success Using Infertility Treatment Data
6th LG AIMERS Hackathon | Hosted by LG, Korea Enterprises Federation  | January - April 2025
# Overview


## [Offline] Pregnancy Success Probability Prediction
- Developed an AI model to estimate the probability of pregnancy success for infertility patients, reframing the task as a classification problem to better capture the target distribution. Performed domain-informed feature engineering, including IVF/DI-specific missing value imputation, feature type conversion, and removal of variables.
- Achieved a final Private Score of 0.6648 using a 3-seed ensemble of LightGBM and CatBoost models, ranking 3rd overall.

  
## [Online] Pregnancy Success Classification
- Developed an AI model to predict the success of pregnancy for infertility patients, optimizing a 5-seed ensemble model based on XGBoost. Conducted extensive feature engineering on 68 variables, including domain-specific preprocessing, variable flipping, missing value imputation, and removal of features.
- Achieved a final performance of ROC-AUC 0.7422 through Optuna-driven hyperparameter tuning. Ranked in the top 30 out of 798 teams and advanced to the final offline round.
