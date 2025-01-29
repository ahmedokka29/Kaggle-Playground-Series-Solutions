# Kaggle Chronicles: A Collection of Data Science and Machine Learning Notebooks

Welcome to my Kaggle Chronicles! This repository contains my work on various Kaggle datasets and competitions. Each notebook represents a unique project where I explore data, apply machine learning algorithms, and extract meaningful insights. This collection is a testament to my continuous learning and passion for data science.

## Table of Contents
- [Introduction](#introduction)
- [Notebooks](#notebooks)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Notebooks
Here is a list of all the notebooks in this repository:

### [Regression of Used Car Prices - S4E9](https://github.com/ahmedokka29/Kaggle-Chronicles/blob/main/PG-S4-E9%20%7C%20AutoML-Submission.ipynb)
- **Description**: This notebook focuses on predicting used car prices using a dataset with features like brand, model, mileage, and fuel type. It includes data cleaning, exploratory data analysis (EDA), feature engineering, and model building using both traditional machine learning (Linear Regression) and AutoML (H2O). The final submission is generated using the best model from H2O AutoML.
- **Technologies**: Python, Pandas, Matplotlib, Seaborn, Scikit-learn, H2O AutoML.
- **Kaggle Playground Link**: [Link to Kaggle](https://www.kaggle.com/competitions/playground-series-s4e9).

#### Results
- **Best Model**: H2O AutoML (XGBoost) achieved an RMSE of Y on the validation set.
- **Key Insights**: 
  - Mileage has a strong negative correlation with car price.
  - Luxury brands like BMW and Mercedes-Benz command higher prices.
  - Electric and hybrid cars are priced higher than petrol or diesel cars.

### [Mushroom Classification - S4E8](https://github.com/ahmedokka29/Kaggle-Chronicles/blob/main/PG-S4-E8%20--%20EDA-Modeling-Submission.ipynb)
- **Description**: This notebook focuses on predicting whether a mushroom is edible or poisonous using features like cap shape, odor, and habitat. It includes exploratory data analysis (EDA), data preprocessing, feature engineering, and modeling with XGBoost, LightGBM, and CatBoost. The final submission is generated using the best-performing model.
- **Technologies**: Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, XGBoost, LightGBM, CatBoost, Missingno.
- **Kaggle Playground Link**: [Link to Kaggle](https://www.kaggle.com/competitions/playground-series-s4e8).

#### Results
- **Best Model**: CatBoost achieved an accuracy of X on the validation set.
- **Key Insights**: 
  - Features like odor and cap shape are strong predictors of mushroom edibility.
  - Missing data was handled using imputation techniques.
  - Feature engineering improved model performance significantly.

...

## Usage
Each notebook is designed to be run independently. Simply open the notebook you're interested in, and follow the instructions within. Feel free to use these notebooks as templates or inspiration for your own projects.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request with your improvements or new notebooks.

## License
This repository is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
