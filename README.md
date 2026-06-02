# FIT5197 Assessment 2: Mental Health and Happiness Prediction

Student: SUN ZHEN  
Student ID: 36446874  
Kaggle name: xiamiya

This repository contains the final assessment notebook, final Kaggle prediction files, and selected submission backups for the FIT5197 Assessment 2 regression and classification tasks.

## Final Results

Regression Contest: Predict Happiness

- Best selected public RMSE: 4.92159
- Second selected public RMSE: 4.92162
- Final `RegressionPredictLabel.csv` uses `R68_R38_010_R40_0990_ultrafine.csv`
- Model summary: ultrafine blend of 99.0% shallow GBM candidate and 1.0% earlier tree/linear blend

Classification: Predict Mental Health

- Best selected public macro F1: 0.56078
- Final `ClassificationPredictLabel.csv` uses the C22 ordinal-threshold blend
- Second selected submission uses the C35 more-trees GBM ordinal model

## Repository Contents

- `FINAL_SUBMISSION_DO_NOT_EDIT/`: final assessment artifacts with checksum manifest.
- `candidate_submissions/`: selected Kaggle backup submissions only.
- `r_libs/`: local R package library used for running the notebook on this machine.

## Final Files

- `FIT5197_FinalAssessment.ipynb`
- `FIT5197_FinalAssessment.pdf`
- `RegressionPredictLabel.csv`
- `ClassificationPredictLabel.csv`

The same four files are also available in `FINAL_SUBMISSION_DO_NOT_EDIT/`, together with `SUBMISSION_MANIFEST.txt` containing SHA256 checksums.

## Data

The original assessment datasets are kept in the repository root:

- `regression_train.csv`
- `regression_test.csv`
- `classification_train.csv`
- `classification_test.csv`

## Environment Notes

The notebook is written in R. The local R executable used during development was:

`E:\R language\R-4.5.2\bin\x64\Rscript.exe`

Main R packages used or prepared:

- `ranger`
- `e1071`
- `xgboost`
- `nnet`
- `rmarkdown`
- `IRkernel`

Python was used only for fast candidate generation and PDF/checksum utilities during development.
