# 📊 Google Play Store EDA

This portfolio project explores and analyzes the Google Play Store dataset to derive insights about app categories, install trends, and app ratings.

## 📁 Dataset Overview

- 10,841 rows × 20 columns
- Source: [Kaggle Dataset by Krishnaik](https://github.com/krishnaik06/playstore-Dataset)

## 📌 Objectives

- Find the most popular app category
- Identify apps with the highest installs
- Clean, transform, and analyze real-world app data

## 🧰 Tools & Libraries

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook in VS Code

## 📊 Key Insights

- **Game** is the most installed category (~35B installs)
- **Subway Surfers**, **Hangouts**, and **Instagram** are among the top apps
- 271 apps have a perfect 5.0 rating

## 🧼 Data Cleaning Highlights

- Converted non-numeric strings (Size, Installs, Price) into usable formats
- Removed duplicates and missing values
- Extracted date parts from `Last Updated`

## 📈 Visual Analysis

- Distributions of installs, ratings, reviews
- Most popular categories and apps
- Top apps by installs in major categories

## 📂 Structure

google-playstore-eda/
├── data/ # Cleaned dataset
├── notebooks/ # Jupyter notebook
├── README.md # Project documentation
├── .gitignore # Ignore rules for repo cleanliness

## 🧹 Repository Cleanliness

A `.gitignore` file is included to avoid committing unnecessary files such as virtual environments, system files, and Jupyter checkpoints.


