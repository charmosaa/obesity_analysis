# Obesity Data Analysis Project

## Overview
This project analyzes the **Estimation of Obesity Levels Based on Eating Habits and Physical Condition** dataset from the [UC Irvine ML Repository](https://archive.ics.uci.edu/dataset/544). The goal is to explore the dataset, clean and preprocess the data, perform exploratory data analysis (EDA), and visualize correlations between features affecting obesity.

### Setup
First, create a virtual environment and install required packages:
```sh
python -m venv venv
source venv/Scripts/activate # activate venv (here in bash) 

pip install -r requirements.txt
```

### Run the Data Analysis
To execute the analysis script you can open and run Jupyter Notebooks:
```sh
jupyter notebook
```
Then open the data_analysis_main.ipynb file and run the step-by-step analysis.
You can also open and run the notebook in VS Code.

## Dataset Description
The dataset contains demographic, behavioral, and physical condition data to estimate obesity levels. The target variable is `NObeyesdad` (obesity level). Key features include:

- **Demographics**: `Age`, `Gender`, `Height`, `Weight`, `family_history_with_overweight`
- **Dietary Habits**: `FAVC` (high-calorie food consumption), `FCVC` (vegetable consumption), `CAEC` (snacks), `CH2O` (water intake), `SCC` (kcals monitoring), `NCP` (meals per day)
- **Lifestyle**: `FAF` (physical activity frequency), `TUE` (time spent on electronic devices)
- **Other**: `SMOKE` (smoking habit), `CALC` (alcohol consumption), `MTRANS` (mode of transport)



## References
- [UCI ML Repository: Obesity Dataset](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition)

