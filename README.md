# AML_Project

 Storm Prediction and Climate Trends Analysis

This project focuses on analyzing climate and stormrelated data to predict storm counts and understand their relationship with various environmental factors. The application is implemented using Streamlit for an interactive user interface and utilizes machine learning and time series analysis techniques for predictive modeling and insights.


 Features

1. Data Upload:
   Upload multiple datasets such as Storm Data, Extreme Temperature Data, Global Warming Data, Methane Data, Carbon Dioxide Data, and Ocean Warming Data in CSV format.

2. Data Processing:
   Cleans and preprocesses data to ensure compatibility across datasets.
   Handles missing values and adjusts values for consistency.

3. Exploratory Data Analysis:
   Displays descriptive statistics for key variables.
   Visualizes relationships using correlation heatmaps.
   Line plots for storm counts over the years.

4. Machine Learning Prediction:
   Implements a Decision Tree Regressor to predict storm counts based on climate factors.
   Evaluates predictions using Mean Squared Error (MSE).

5. Time Series Analysis:
   Generates ACF and PACF plots for storm counts.
   Builds an ARIMA model to predict storm counts and evaluates its performance using MSE.

6. Visualization:
   Heatmaps, line plots, and comparative plots for actual vs predicted storm counts.



 Requirements

 Python Libraries:
  pandas
  numpy
  seaborn
  matplotlib
  scikitlearn
  statsmodels
  Streamlit



 How to Use

1. Clone this repository to your local machine:
   git clone <repositoryurl>

2. Navigate to the project directory:
   cd stormprediction

3. Install the required dependencies:
   pip installr requirements.txt
  
4. Run the Streamlit application:
   streamlit run app.py

5. Upload the necessary CSV files when prompted in the application.



 Input Data

 Storm Data: Historical storm counts and related indicators.
 Extreme Temperature Data: Records of extreme temperature events over time.
 Global Warming Data: Trends and lowessfiltered data related to global temperature anomalies.
 Methane Data: Methane concentration levels across years.
 Carbon Dioxide Data: CO2 levels with seasonal adjustments.
 Ocean Warming Data: Average temperature changes in ocean environments.


 Acknowledgments

This project uses publicly available datasets for analysis and visualization from Nasa's site : https://climate.nasa.gov/%C2%A0%C2%A0/

