# Population of India Analysis

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)]()  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rohanambati/Population-of-India-/HEAD)

---

## Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
3. [Dataset](#dataset)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Project Structure](#project-structure)  
7. [Binder Notebook](#binder-notebook)  
8. [Environment](#environment)  
9. [License](#license)  
10. [Contact](#contact)  
11. [Acknowledgements](#acknowledgements)

---

## Overview

This project analyzes historical population data of India, explores key demographic trends, and builds forecasting models to predict future population growth. It covers:

- Data ingestion, cleaning, and exploratory analysis  
- Feature engineering (growth rates, lag features)  
- Regression and time-series modeling  
- Visualization of historical trends and future forecasts  

---

## Features

- **Exploratory Data Analysis**: Correlation heatmaps, time-series plots, distribution analyses  
- **Feature Engineering**: Yearly growth rates, rolling averages, lag variables  
- **Modeling**: Linear Regression, Random Forest, ARIMA time-series forecasting  
- **Reproducibility**: `requirements.txt` and `environment.yml` for environment setup  
- **Interactive Notebook**: Launchable via Binder for zero-install exploration  

---

## Dataset

- **Name**: `india_population.csv`  
- **Source**: Kaggle (to be uploaded in this repo)  
- **Description**: Yearly population figures for India from 1950 to the latest available year  

---

## Installation

```bash
git clone https://github.com/rohanambati/Population-of-India-.git
cd Population-of-India-
python3 -m venv venv
source venv/bin/activate     # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

---

## Usage

1. Upload `india_population.csv` into the `data/` directory.

2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open `notebooks/Population_of_India_Analysis.ipynb` and step through:

   Data → EDA → Modeling → Forecasting → Conclusions

---

## Project Structure

```
Population-of-India-/
├── data/
│   └── india_population.csv
├── notebooks/
│   └── Population_of_India_Analysis.ipynb
├── requirements.txt
├── environment.yml
├── LICENSE
├── .gitignore
└── README.md
```

---

## Binder Notebook

Launch instantly in your browser (no local setup required):

[https://mybinder.org/v2/gh/rohanambati/Population-of-India-/HEAD](https://mybinder.org/v2/gh/rohanambati/Population-of-India-/HEAD)

---

## Environment

* **Python**: 3.8 or above
* **Key packages**: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels

Use `environment.yml` to recreate:

```yaml
name: pop-india
channels:
  - defaults
dependencies:
  - python=3.8
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - statsmodels
```

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

Rohan Ambati

* GitHub: [@rohanambati](https://github.com/rohanambati)
* Email: [rohanambati40@gmail.com](mailto:rohanambati40@gmail.com)

---

## Acknowledgements

* Kaggle for the India population dataset  
* Documentation from pandas, scikit-learn, statsmodels, and matplotlib  
* Inspiration from the Awesome Public Datasets repository  
