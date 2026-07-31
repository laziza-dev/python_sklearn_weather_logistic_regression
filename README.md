# python_sklearn_weather_logistic_regression
# Australian Weather Data Analysis & Prediction Pipeline

## Project Overview
This project performs an end-to-end data analysis and machine learning preparation pipeline built in Python utilizing Pandas, Scikit-Learn, Plotly, and Seaborn. The goal was to explore the comprehensive Australian weather dataset from Kaggle, perform exploratory data analysis, and prepare data splits for predictive modeling.

## Methodology
* **Data Retrieval:** Automated downloading of datasets directly from Kaggle using the `opendatasets` library[cite: 1].
* **Data Inspection & Cleaning:** Handled missing target variables (`RainToday` and `RainTomorrow`) and analyzed feature distributions[cite: 1].
* **Data Splitting:** Partitioned the cleaned dataset into training, validation, and test sets using `scikit-learn` (60% train, 20% validation, 20% test) to prepare for robust machine learning workflows[cite: 1].

## Key Visualizations
* **Location vs. Rainy Days:** Distribution of precipitation events across different Australian regions[cite: 1].
* **Temperature & Humidity vs. Rain:** Investigating how afternoon temperature (`Temp3pm`) and humidity (`Humidity3pm`) correlate with precipitation (`RainTomorrow`)[cite: 1].
* **Temperature Bounds:** Scatter plots comparing minimum and maximum temperatures categorized by `RainToday`[cite: 1].

## Conclusion
The analysis successfully processed over 145,000 meteorological records from various Australian weather stations to set up a reliable machine learning pipeline[cite: 1]. Future iterations of this project will involve training predictive models to forecast rainfall based on these meteorological features.
