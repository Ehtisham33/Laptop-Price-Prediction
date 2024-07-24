

# Laptop Price Prediction

This project focuses on predicting laptop prices using machine learning techniques. The dataset includes various features of laptops, such as brand, processor specifications, RAM, storage, OS, and more.

## Project Overview

The goal of this project is to build a model that accurately predicts the price of a laptop based on its features.

## Table of Contents

- Dataset
- Installation
- Data Preprocessing
- Feature Engineering
- Model Evaluation
- Hyperparameter Tuning
- Results
- Technologies Used
- Visualizations
- Conclusion

## Dataset

The dataset contains 823 entries with the following columns:
- `brand`
- `processor_brand`
- `processor_name`
- `processor_gnrtn`
- `ram_gb`
- `ram_type`
- `ssd`
- `hdd`
- `os`
- `os_bit`
- `graphic_card_gb`
- `weight`
- `warranty`
- `Touchscreen`
- `msoffice`
- `Price`
- `rating`
- `Number of Ratings`
- `Number of Reviews`

## Installation

To run this project, you will need to have Python installed along with the following libraries:
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

You can install these libraries using pip:

```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

## Data Preprocessing

- **Loaded the dataset** and checked for datatypes, null values, and duplicates.
- **Dropped unnecessary columns** and labeled categorical columns.

## Feature Engineering

Selected the following features for prediction:
- `brand`
- `processor_brand`
- `processor_name`
- `processor_gnrtn`
- `ram_gb`
- `ram_type`
- `ssd`
- `hdd`
- `os`
- `os_bit`
- `graphic_card_gb`
- `weight`
- `warranty`
- `Touchscreen`
- `msoffice`
- `rating`

## Model Evaluation

Evaluated the following models:
- Linear Regression
- Decision Tree
- Random Forest

## Hyperparameter Tuning

Used **RandomizedSearchCV** for hyperparameter tuning of the RandomForestRegressor to achieve the best performance.

## Results

The Random Forest model provided the best performance with optimal hyperparameters, effectively predicting laptop prices based on the given features.

## Technologies Used

- **Python:** For data processing and model building.
- **Pandas & NumPy:** For data manipulation.
- **Scikit-Learn:** For machine learning algorithms.
- **Seaborn & Matplotlib:** For data visualization.

## Visualizations

Visualized the model's accuracy using scatter and regression plots.

## Conclusion

The project successfully built a model to predict laptop prices with high accuracy using Random Forest with hyperparameter tuning.

---

Feel free to reach out if you have any questions or feedback!

---
