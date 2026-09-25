# FIT5197 | Regression & ordinal classification

R modelling notebook and standalone scripts for happiness regression and an ordered survey-response classification task. Methods include linear baselines, BIC selection, Random Forest, XGBoost, GBM, Ridge, out-of-fold stacking and ordinal score blending.

Open `regression-classification.ipynb` with a Jupyter R/IRkernel environment, or inspect the standalone `.R` scripts. Required packages are declared in the code, including `randomForest`, `xgboost`, `gbm`, `glmnet`, `caret`, `dplyr` and `forecast`.

Supply the authorised regression/classification training and test CSVs named in the code. Survey records, prediction CSVs, course templates and lecture materials are not distributed. Notebook outputs and execution metadata were cleared; algorithms were not changed or rerun.

The original notebook reports a public regression RMSE of 3.84 and a classification macro-F1 of 0.51. These remain author-reported historical coursework results; the original classification narrative mixes validation and submission language, so this portfolio does not present them as independently verified holdout scores.
