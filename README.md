# Water Potability Prediction

A beginner-friendly machine learning project that analyzes water-quality measurements and predicts whether a sample is labeled as potable (`1`) or not potable (`0`).

## Project goal
Use Python, Pandas, NumPy, Matplotlib, Seaborn and Scikit-learn to:
- inspect and clean the dataset
- explore water-quality variables
- handle missing values
- visualize patterns
- train classification models
- compare model performance

## Dataset
This project uses the public Kaggle **Water Quality / Water Potability** dataset containing 3,276 water samples and 9 water-quality features plus the `Potability` target.

Download `water_potability.csv` from:
https://www.kaggle.com/datasets/adityakadiwal/water-potability

After downloading, place the CSV here:

`data/water_potability.csv`

## Features
- `ph`
- `Hardness`
- `Solids`
- `Chloramines`
- `Sulfate`
- `Conductivity`
- `Organic_carbon`
- `Trihalomethanes`
- `Turbidity`

Target:
- `Potability` — 1 = potable label, 0 = non-potable label

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

## How to run
```bash
pip install -r requirements.txt
jupyter notebook
```

Open `notebooks/water_potability_prediction.ipynb` and run the cells from top to bottom.

## Important note
This is a machine-learning practice project using a public dataset. The model's prediction should not be treated as a real-world drinking-water safety certification.

## Project structure
```text
Water-Potability-Prediction/
│
├── data/
│   └── water_potability.csv
├── notebooks/
│   └── water_potability_prediction.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```
