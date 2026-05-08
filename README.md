# Admission Prediction

A small machine learning notebook that explores graduate admissions data and trains a regression model to estimate the chance of admission from applicant profile features.

## What’s in the repo

- `Admission prediction.ipynb` - exploratory analysis, visualization, model comparison, and predictions
- `admission_predict.csv` - source dataset used by the notebook

## Features used

- GRE score
- TOEFL score
- University rating
- SOP rating
- LOR rating
- CGPA
- Research experience

## Setup

1. Create a Python environment.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Open `Admission prediction.ipynb` in Jupyter or VS Code.
4. Run the notebook cells top to bottom.

## Notes

- The notebook currently performs exploratory data analysis, model selection with `GridSearchCV`, and a linear regression prediction workflow.
- Predictions are shown as admission probability estimates.

## Suggested improvements

- Save the cleaned dataset or trained model for reuse.
- Split the notebook into separate analysis and training scripts if you want a production-style project layout.
- Add notebook outputs only if you want them tracked in GitHub.
