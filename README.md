# **Crime Data Analyzer**

This project aims to analyze and predict crime patterns by leveraging advanced data analysis techniques and machine learning models. The project provides insights into crime trends, hotspots, and arrest patterns, while offering an interactive **Power BI Dashboard** for dynamic data exploration and visualization.

---

## **Problem Statement**

The goal of this project is to develop an interactive application that allows users to analyze crime data effectively and identify patterns based on time, location, and crime type. Key features include:

- **Temporal Analysis**: Analyze trends in crime occurrences over different time periods.
- **Geospatial Analysis**: Identify crime hotspots and compare crime rates across districts/wards.
- **Crime Type Analysis**: Understand the distribution and severity of crimes.
- **Arrest Analysis**: Examine arrest rates and distinguish between domestic and non-domestic crimes.
- **Predictive Modeling**: Develop models to forecast future crime patterns.
- **Interactive Visualization**: Allow users to interactively explore crime insights using **Power BI Dashboards**.

---

## **Workflow**

1. **Data Retrieval**: Import crime data, including fields such as `Primary Type`, `Description`, `Date`, `Location Description`, `Latitude`, and `Longitude`.
2. **Data Cleaning and Preparation**: Handle missing values, duplicates, and incorrect data formats.
3. **Exploratory Data Analysis (EDA)**: Analyze temporal, geospatial, and categorical trends.
4. **Feature Engineering**: Process data for modeling, scaling, and transformations.
5. **Predictive Modeling**: Develop machine learning models to predict crime patterns.
6. **Power BI Dashboard**: Build an interactive visualization dashboard for analyzing crime insights.

---

## **Features**

### 1. **Temporal Analysis**
   - **Crime Trends Over Time**: Visualize crime occurrences across years, months, and days.
   - **Peak Crime Hours**: Analyze hourly trends to identify high-crime time periods.

### 2. **Geospatial Analysis**
   - **Crime Hotspots**: Use latitude and longitude data to identify high-crime areas.
   - **District/Ward Analysis**: Compare crime rates across different regions and neighborhoods.

### 3. **Crime Type Analysis**
   - **Distribution of Crime Types**: Identify the most common crimes by analyzing the `Primary Type` and `Description` fields.
   - **Severity Analysis**: Distinguish between severe crimes (e.g., homicides) and minor offenses (e.g., thefts).

### 4. **Arrest and Domestic Incident Analysis**
   - **Arrest Rates**: Calculate and visualize the percentage of crimes resulting in arrests, broken down by crime type and location.
   - **Domestic vs. Non-Domestic Crimes**: Compare the characteristics of domestic and non-domestic crime incidents.

### 5. **Location-Specific Analysis**
   - **Location Description**: Analyze the most common locations for crimes (e.g., streets, parking lots, apartments).
   - **Beat and Community Area Comparison**: Identify localized crime trends and patterns.

### 6. **Predictive Modeling**
   - **Crime Forecasting**: Predict future crime trends based on historical patterns using machine learning.
   - **Risk Assessment**: Evaluate the likelihood of crimes occurring in specific locations or time periods.

### 7. **Interactive Power BI Dashboard**
   - **Dynamic Visualizations**: Use charts, and tables to explore crime insights.
   - **Geospatial Insights**: Visualize crime hotspots and trends.
   - **User Input Filters**: Allow users to filter data dynamically based on time and location.
   - **Real-Time Insights**: Display updated visualizations and metrics based on selected parameters.

---

## **Technologies Used**

- **Python**: Core programming language for data processing and analysis.
- **Pandas/Numpy**: Libraries for data manipulation and preparation.
- **Seaborn/Matplotlib**: Libraries for data visualization during EDA.
- **Scikit-learn**: For machine learning model development.
- **Plotly**: For interactive charts and geospatial visualizations.
- **Power BI**: For creating interactive dashboards with advanced data visualizations.

---

## **References**

- **Python**: [https://docs.python.org/3/](https://docs.python.org/3/)
- **Scikit-learn Documentation**: [https://scikit-learn.org/stable/](https://scikit-learn.org/stable/)
- **Plotly**: [https://plotly.com/](https://plotly.com/)
- **Power BI Documentation**: [https://learn.microsoft.com/en-us/power-bi/](https://learn.microsoft.com/en-us/power-bi/)
