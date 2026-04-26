# Titanic Survival Analysis

A machine learning project that analyzes the Titanic dataset and builds a Logistic Regression model to predict passenger survival.

## Project Overview

This project demonstrates:
- Data loading and exploration
- Data preprocessing and handling missing values
- Exploratory Data Analysis (EDA) with visualizations
- Machine learning model training and evaluation
- Model performance metrics (accuracy, confusion matrix, classification report)

## Dataset

Uses the famous Titanic dataset containing passenger information:
- **Features**: PassengerId, Pclass, Sex, Age, SibSp, Parch, Fare, Embarked, Cabin, Ticket, Name
- **Target**: Survived (0 = No, 1 = Yes)

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/vaibhavagarwal04/titanic_survival_vaibhav.git
cd titanic_survival_vaibhav
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the notebook:
```bash
jupyter notebook titanic_clean.ipynb
```

The notebook will:
1. Load the Titanic dataset
2. Perform exploratory analysis with visualizations
3. Preprocess data (handle missing values, encode categorical variables)
4. Train a Logistic Regression model
5. Evaluate model performance

## Results

The model achieves good accuracy on predicting passenger survival based on:
- Passenger class
- Gender
- Age
- Port of embarkation
- Fare

## File Structure

```
titanic-survival/
├── titanic_clean.ipynb      # Main analysis notebook (clean version)
├── train.csv                # Titanic dataset (not included in repo)
├── requirements.txt         # Python dependencies
├── .gitignore              # Git ignore file
└── README.md               # This file
```

## Notes

- The training data (`train.csv`) is excluded from the repository as it's a large data file
- All outputs are removed from the notebook to keep it clean
- The model uses a 80-20 train-test split with random_state=42 for reproducibility

## Author

Vaibhav Agarwal

## License

This project is open source and available under the MIT License.
