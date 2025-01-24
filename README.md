# COVID-19-Data-Analysis-and-Visualization

**Overview**
This repository contains a Jupyter Notebook dedicated to analyzing and visualizing COVID-19 data in conjunction with the World Happiness Report. The analysis explores the relationship between various factors, such as GDP per capita, social support, healthy life expectancy, freedom to make life choices, and the maximum infection rate of COVID-19 across different countries.

**Datasets Used**

The analysis utilizes the following datasets:

**COVID-19 Dataset:**
Provides data on confirmed COVID-19 cases across various countries.

Includes daily case counts.

Sourced from covid19_Confirmed_dataset.csv.

**World Happiness Report Dataset:**

Offers insights into factors contributing to happiness in different countries.

Contains data on GDP per capita, social support, healthy life expectancy, freedom to make life choices, etc.

Sourced from worldwide_happiness_report.csv.

**Analysis and Visualization Tasks**

**Task 1: Importing Required Libraries**

Ensuring the successful import of necessary Python libraries such as pandas, numpy, matplotlib, and seaborn.

**Task 2: Data Preprocessing**

Step 2.1: Importing the COVID-19 dataset.

Step 2.2: Removing unnecessary columns to streamline the dataset.

Step 2.3: Aggregating data by country to facilitate comparative analysis.

Step 2.4: Visualizing country-specific COVID-19 trends.

**Task 3: Infection Rate Analysis**

Step 3.1: Calculating the infection rate for specific countries.

Step 3.2: Computing and plotting the first derivative of the infection rate curve.

Step 3.3: Identifying the maximum infection rates for India and China.

Step 3.4: Determining the maximum infection rate across all countries and creating a new dataframe to store these values.

**Task 4: Merging Datasets**

Importing and preprocessing the World Happiness Report dataset.

Combining the COVID-19 dataset with the Happiness Report dataset.

Analyzing correlations between happiness factors and COVID-19 infection rates.

**Task 5: Visualization of Results**

Step 5.1: Plotting GDP per capita vs. Maximum Infection Rate.

Step 5.2: Plotting Social Support vs. Maximum Infection Rate.

Step 5.3: Plotting Healthy Life Expectancy vs. Maximum Infection Rate.

Step 5.4: Plotting Freedom to Make Life Choices vs. Maximum Infection Rate.

**Tools and Libraries Used**

pandas: For data manipulation and analysis.

numpy: For numerical computations.

matplotlib: For creating static visualizations.

seaborn: For statistical data visualization.

**Conclusion**

The insights gained from this analysis provide valuable information on the relationship between COVID-19 spread and various socio-economic factors such as GDP per capita, social support, and health expectancy. These findings can help health organizations and governments design targeted intervention strategies, allocate resources more efficiently, and develop policies that promote public health and well-being. Additionally, by understanding the correlation between happiness factors and infection rates, authorities can implement measures to improve mental and physical health resilience during pandemics. 

