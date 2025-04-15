# 🧠 AutoGluon: Health Activity Insights - Regression & Classification

Welcome! This project explores health and activity data through the power of [AutoGluon](https://auto.gluon.ai/stable/index.html), applying cutting-edge machine learning techniques for both **regression** and **classification** tasks.

### Project Highlights:
- **Regression**: Predict daily calories burned based on activity metrics.
- **Classification**: Categorize days as **Weekdays** or **Weekends**, analyzing activity patterns.


## 🔗 My EDA Report

Explore detailed insights and visualizations in my [Y-data profile report](https://millie1310.github.io/EDA_reports/ydata/MySteps_report.html).
---

## 🏗️ Repository Structure

Your one-stop directory guide:
- **`notebooks/`**
  - `01_regression_calories.ipynb`: Crafting a regression model to predict calorie burn.
  - `02_classification_daytype.ipynb`: Building a classification model to distinguish day types.
- **`data/`**: Contains health and activity datasets.
- **`AutogluonModels/`**: Stores trained AutoGluon models.
- **`README.md`**: You're reading it!

---

## 📊 Dataset Insights

The dataset delves into various daily activity metrics, such as:
- **Steps**: Total steps taken.
- **Distance**: Distance traveled.
- **Calories**: Calories burned in a day.
- **Minutes Sedentary**: Time spent idle.
- **Minutes Active**: From light activity to intense workouts.
- **Sleep Hours**: Total sleep duration.
- **DayType**: **Target variable**—Weekend or Weekday.
- And much more!

This rich collection helps us uncover fascinating patterns in human activity.

---

## 🧪 ML Tasks Overview

### 1️⃣ Regression: Predicting Calories Burned
- **Goal**: Predict calorie burn based on activity metrics.
- **Method**: Leveraging AutoGluon's `TabularPredictor` for optimal performance.
- **Results**:
  - **Best Model**: Weighted Ensemble.
  - **Validation RMSE**: 41.37.
  - **Key Features**: Steps, distance, sleepHours, activity levels.

---

### 2️⃣ Classification: Weekday vs. Weekend
- **Goal**: Determine day type based on activity patterns.
- **Method**: AutoGluon's `TabularPredictor`, ensuring top-notch classification results.
- **Results**:
  - **Best Model**: Weighted Ensemble.
  - **Validation Accuracy**: 87.23%.
  - **ROC AUC**: 91.88%.
  - **Key Features**: Steps, activity levels, day name, sleep hours.

---

## 📈 Visualizations

The notebooks include detailed charts and plots:
- **Feature Importance**: Highlights key predictors.
- **Prediction vs Actual**: Reveals model accuracy.
- **Confusion Matrix & ROC Curve**: Unpack classification performance.

---

## ❤️ Why This Project?

This project aims to simplify complex health data using AutoGluon’s automated machine learning. Whether you're interested in calorie prediction or distinguishing weekdays from weekends, this repository is your gateway to smart health analytics.

  pip install autogluon pandas matplotlib seaborn
