# Weather Classification Data Analysis

This project performs an exploratory data analysis (EDA) on a weather classification dataset. The analysis includes a series of visualizations, data manipulation, and insights into the relationships between various weather-related features.

## Dataset

The dataset used in this project is sourced from a Kaggle weather classification dataset, which includes features like temperature, precipitation, humidity, UV index, wind speed, visibility, and cloud cover, among others.

### Dataset Description

- **Precipitation (%):** The percentage of precipitation.
- **Temperature:** The temperature recorded at a specific time.
- **Humidity:** The percentage of humidity in the atmosphere.
- **UV Index:** The ultraviolet index at a specific time.
- **Wind Speed:** The speed of the wind at a specific time.
- **Visibility (km):** The visibility distance in kilometers.
- **Season:** The season when the data was recorded (categorical).
- **Weather Type:** The type of weather conditions (categorical).
- **Cloud Cover:** The percentage of cloud cover in the atmosphere.

## Project Structure

The project is divided into the following sections:

### 1. Data Analysis
- Load the weather classification dataset using pandas and analyze its structure.
- Display the first few rows and summary statistics of the dataset.

### 2. Data Types of Features
- Display the data types of each feature in the dataset.

### 3. Missing Values Visualization
- Visualize the missing values in the dataset using `missingno` bar plots.

### 4. Data Visualization
This section explores the data through various visualizations:
- **Distribution of Target:** Visualize how the target variables (`Season`, `Weather Type`, and `Cloud Cover`) are distributed across other features.
- **Correlation Matrix:** Display a heatmap of correlations between numerical features in the dataset.
- **Data Relationships:** Examine the relationships between specific features like humidity, precipitation, UV index, wind speed, and visibility through line charts and bar charts.

## Data Visualization Examples

### 4.1 Distribution of Target Across Columns
Visualize how the categorical targets such as `Season` are distributed across other numerical and categorical columns using stacked bar plots.

### 4.2 Correlation Matrix
Visualize the correlation matrix of numerical features using a heatmap to identify strong relationships between variables like temperature, wind speed, and precipitation.

### 4.3 Data Relationships
Analyze the following relationships in the dataset:
- **Humidity vs. Precipitation**
- **Temperature vs. UV Index**
- **Wind Speed vs. Humidity**
- **Visibility vs. Humidity**

Line and bar charts are used to showcase how these weather parameters influence each other.

## Requirements

To run the analysis and visualizations, you need the following Python libraries installed:

- `numpy`
- `pandas`
- `prettytable`
- `matplotlib`
- `seaborn`
- `missingno`
- `scikit-learn`

You can install the required libraries using the following command:

```pip install numpy pandas prettytable matplotlib seaborn missingno scikit-learn```

## How to Run
1. Clone the repository to your local machine:
2. Install the required libraries listed in the Requirements section.
3. Run the Python script:

```python weather_classification_analysis.py```

4. The script will load the dataset and generate various visualizations and insights about weather-related parameters.

## Project Highlights
- **Data Inspection:** Initial inspection of the dataset including feature types and handling missing values.
- **Target Distribution:** A detailed look at how the target variables Season, Weather Type, and Cloud Cover are distributed across other features.
- **Correlation Analysis:** A heatmap showing correlations between numerical weather features.
- **Data Relationships:** Insights into how weather parameters like humidity, precipitation, and temperature are related.
