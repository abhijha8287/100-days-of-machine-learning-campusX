# 100 Days of Machine Learning (CampusX)

Notes, notebooks and practice datasets from working through the CampusX "100 Days of Machine Learning" course.

## Why this exists
A day-by-day record of learning machine learning from the ground up: the maths behind each method and its code.

## What it does
- Days 1-11: written notes as PDFs (ML basics, the ML lifecycle, data roles)
- Days 13-60: Jupyter notebooks covering data gathering, EDA, feature engineering, encoding, scaling, missing values, outliers and pipelines
- Practice datasets used in the notebooks (Titanic, placement, cars, wine, house prices and others)
- Profiling reports generated during EDA (`titanic_report.html`, `train_report.html`)

## Project structure
```
100-days-of-machine-learning-campusX/
├── day*.pdf           Notes for days 1-11
├── day*.ipynb         Notebooks for days 13-60
├── project..ipynb     End-to-end practice project
├── *.csv              Practice datasets
├── digit-recognizer/  Kaggle digit recognizer data
├── titanic/           Kaggle Titanic data
├── *_report.html      EDA profiling reports
├── model.pkl          Model saved in a notebook
└── mlenv/             Local Python virtual environment
```

## Getting started
Requirements: Python 3.10+, Jupyter.
```bash
git clone https://github.com/abhijha8287/100-days-of-machine-learning-campusX.git
cd 100-days-of-machine-learning-campusX
python -m venv .venv && source .venv/bin/activate
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
jupyter notebook day13.ipynb
```
Notebooks read the CSVs from the repo root, so start Jupyter from this folder.

## Tech stack
Python, Jupyter, pandas, NumPy, scikit-learn, Matplotlib, Seaborn

## Notes
Course: [CampusX on YouTube](https://www.youtube.com/@CampusX). Some day numbers are missing because those lessons had no code. `mlenv/` is a committed virtual environment and is not needed; create your own as shown above.
