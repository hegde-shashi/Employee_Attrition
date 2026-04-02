# Employee Attrition Prediction

This project contains a machine learning workflow for predicting employee attrition using tabular HR data.

## Project Contents

- `Train_Dataset.csv`: Training dataset used to build and validate the model.
- `Test_Dataset.csv`: Test dataset used for generating final predictions.
- `employee_attr.ipynb`: Main notebook for data preprocessing, model training, evaluation, and inference.
- `Sample_Submission_(2)_(1)_(1)_(1).csv`: Reference submission format.
- `submission_3.csv`, `submission_4.csv`: Generated prediction files.

## Workflow

1. Load training and test datasets.
2. Perform preprocessing and feature engineering.
3. Train and evaluate one or more models.
4. Generate predictions for the test dataset.
5. Export predictions in submission format.

## Requirements

- Python 3.10+
- Jupyter Notebook
- Common ML libraries (for example: pandas, numpy, scikit-learn)

Install dependencies in your virtual environment:

```bash
pip install pandas numpy scikit-learn jupyter
```

## How To Run

1. Activate your virtual environment.
2. Open `employee_attr.ipynb`.
3. Run notebook cells in order.
4. Verify generated submission files.

## Notes

- Keep file names unchanged unless notebook paths are updated.
- If you change preprocessing or model parameters, regenerate submission files.