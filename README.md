# Support Vector Machine

**Support Vector Machine** for crash survival prediction: preprocessing, a from-scratch
SVM implementation, sklearn comparison, and grid-search tuning.

Built for a Machine Learning course assignment.

## What this project covers

- Missing-value imputation and label encoding
- Custom SVM training loop vs. `sklearn.svm.SVC`
- Hyperparameter grid search (task D)

## Project layout

| File | Description |
|------|-------------|
| `main.ipynb` | SVM workflow |
| `crash.csv` | Dataset |
| `Project_Description.pdf` | Assignment brief |
| `Report.pdf` | Report |

## Quick start

```bash
python -m venv .venv
.venv\\Scripts\\activate          # macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook main.ipynb
```

Notebook outputs are saved so plots render on GitHub.
