# Project Overview: Weather Analysis and Trends in Delhi


## **Project Description**
This project analyses historical weather data from Delhi to uncover significant trends and patterns. The key objectives include identifying seasonal variations, tracking long-term climate changes, and understanding the relationships between key weather variables such as temperature, humidity, wind speed, and pressure. Through data visualisation and statistical analysis, the project provides insights into how Delhi’s weather has evolved over the years.


## **Problem Statement**
The central question being addressed in this project is: "How have the key weather variables in Delhi, specifically temperature, humidity, wind speed, and pressure, changed over time, and what trends can be identified?" Understanding these trends is important for addressing broader concerns about climate change, planning for urban sustainability, and improving the accuracy of weather forecasting.

## **Approach**
The approach to solving the problem involves the following steps:

### Data Collection and Preparation:
* The dataset used consists of daily weather observations for Delhi, including:
  - Mean Temperature (°C)
  - Humidity (%)
  - Wind Speed (km/h)
  - Mean Pressure (hPa)
- **Source**: The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data), covering the period from [2013-01-01] to [2017-01-01].
- Initial data cleaning involved handling missing values, converting data types, and ensuring the 'date' column was properly formatted for time series analysis.


### Exploratory Data Analysis (EDA):

- Key weather variables were visualized to understand their distributions.
- Seasonal trends were explored by aggregating data by month and year.
- Time series plots were generated to observe trends in temperature and other weather metrics.

### Data Resampling and Transformation:
- Data was resampled on a monthly basis to smooth out daily fluctuations and to observe long-term trends.
- Percentage changes in variables such as mean temperature were computed to highlight periods of rapid change.

### Visualization:
- Line plots were used to track the evolution of temperature, humidity, and wind speed over time.
- Bar plots with conditional colouring highlighted positive or negative monthly percentage changes.
- Dual y-axis plots allowed for simultaneous visualization of multiple variables, such as temperature and pressure.
- Box plots to display the temperature and humidity distribution across different months, revealing seasonal patterns.
- Scatter plots and heatmaps to visualise correlations between variables.


## **Tools Used**
- **Programming Language**: Python
- **Libraries**:
  - `Pandas`: For data manipulation and analysis
  - `Matplotlib`: For data visualization
  - `Seaborn`: For enhanced statistical graphics
- **Environment**: Jupyter Notebook and Visual Studio Code

## **Insights and Findings**
- **Temperature Trends**: The analysis revealed a significant drop trend in mean temperatures between 2016 and 2017.
- **Seasonal Variations**: The mean temperature in Delhi shows clear seasonal patterns, with higher temperatures observed during the summer months and lower during the winter months.
- **Correlation**: A strong negative correlation was found between mean temperature and humidity, highlighting the interplay between these variables.

## **Conclusion**
This project effectively demonstrates the ability to analyze and visualize weather data, uncovering meaningful insights that contribute to a better understanding of climatic conditions in Delhi. The visualizations produced not only present the data effectively but also serve as a valuable resource for further research and decision-making.

## **Future Work**
- Implement machine learning models to predict future weather conditions based on historical data.
- Develop an interactive dashboard to present the findings dynamically.
- Additional data sources, such as air quality or pollution levels, could be incorporated to understand their relationship with weather variables.

## **Link to Project Notebook**
- [Notebook](https://github.com/Promisekeh/Data-Analysis-Projects/blob/main/Time-Series-Analysis/daily-climate-time-series-data.ipynb)
