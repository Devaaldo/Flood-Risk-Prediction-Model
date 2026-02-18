# Flood Prediction

This repository contains a Jupyter notebook and dataset files for a machine learning project focused on flood prediction. The data used in this project is sourced from the Kaggle competition: [Playground Series Season 4 Episode 5](https://www.kaggle.com/competitions/playground-series-s4e5/data).

## Dataset

The `data/flood` directory includes:

- `train.csv` : Training data with features and target variable indicating flood risk.
- `test.csv` : Test data for which predictions are to be made.
- `sample_submission.csv` : Example submission format for the Kaggle competition.

The original dataset can be downloaded from the competition page linked above. Place the files in the `data/flood/` directory.

## Notebook

- `flood_prediction.ipynb` : Contains exploratory data analysis (EDA), feature engineering, model training, and evaluation steps.

## Project Structure

```
\flood_prediction.ipynb
\README.md
\data\
    \flood\
        train.csv
        test.csv
        sample_submission.csv
```

## Requirements

- Python 3.11
- Common libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost` (or other ML libraries as used in the notebook).

## Usage

1. Download the dataset from Kaggle and place files in `data/flood/`.
2. Open `flood_prediction.ipynb` in Jupyter or VS Code and run the cells to reproduce analysis and model training.
3. Use the trained model to generate predictions for `test.csv` and format according to `sample_submission.csv`.
