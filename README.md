# Weather Data Analysis Project

This repository contains a weather data analysis project that demonstrates beginner-level data analysis skills. Completed as part of an introductory data analysis course, this project focuses on learning essential techniques for cleaning, analyzing, and visualizing data while working with real-world weather data.

## Project Overview

The goal of this project is to explore a weather dataset, apply foundational data preprocessing and analysis methods, and build a simple predictive model.

## Files in This Repository

- **weather.csv**: The weather dataset used for analysis.
- **Final Project.ipynb**: A Jupyter Notebook containing the Python code for data cleaning, exploratory analysis, feature engineering, and visualizations.
- **WeatherDataAnalysisProject.pdf**: A summary of the project goals, methods, and results.

## Skills Demonstrated

1. **Data Preprocessing**
   - Cleaned the dataset by handling missing values.
   - Converted categorical variables (`RainToday`, `RainTomorrow`, and `WindDir9am`) into numerical formats using ordinal encoding.

2. **Exploratory Data Analysis (EDA)**
   - Generated summary statistics to understand the dataset.
   - Visualized key variables, such as temperature, humidity, and rainfall distributions.

3. **Feature Engineering**
   - Created new features:
     - `TempRange`: Difference between maximum and minimum temperatures.
     - `AvgHumidity`: Average of morning and afternoon humidity levels.
   - Normalized columns for temperature and humidity to improve data consistency.

4. **Data Visualization**
   - Created scatterplots (e.g., `TempRange` vs. rainfall) and boxplots (e.g., sunshine hours vs. rain).
   - Developed a correlation heatmap to identify relationships between variables.

5. **Beginner Machine Learning**
   - Built a Naive Bayes classification model to predict whether it will rain tomorrow (`RainTomorrow`).
   - Evaluated the model's performance using metrics like accuracy and confusion matrices.

## Tools and Libraries Used

- **Data Processing**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Machine Learning**: `scikit-learn`
- **Regular Expressions**: For cleaning and extracting data related to wind direction.

## Outcomes

- Cleaned and transformed the dataset into a usable format for analysis.
- Developed foundational skills in creating meaningful visualizations and extracting insights from data.
- Built and evaluated a basic classification model to predict rain, gaining hands-on experience with machine learning.

## How to Use

1. **View the Analysis**: Open `Final Project.ipynb` to see the step-by-step code and outputs.
2. **Explore the Data**: Use `weather.csv` to replicate the analysis or build on it further.
3. **Read the Summary**: Refer to `WeatherDataAnalysisProject.pdf` for an overview of the project’s approach and findings.

## Acknowledgments

The dataset used for this project was provided through course materials.
