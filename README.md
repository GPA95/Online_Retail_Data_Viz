# Data-Visualization-Business-Insights

## Project Overview

This repository contains an internship project focused on leveraging data visualization techniques to transform raw retail transaction data into actionable business insights. The project was undertaken as part of a Bachelor of Technology program in Computer Science & Engineering at Integral University, Lucknow.

## Key Features

  * **Data Preprocessing**: Utilizes Python (Pandas, NumPy, Matplotlib, Seaborn) for cleaning, structuring, and transforming raw retail transaction data.
  * **Interactive Dashboards**: Creates interactive dashboards using Tableau to address key business questions.
  * **Business Insights**: Focuses on analyzing sales trends, customer segmentation, geographical demand, and product performance to empower data-driven decision-making.
  * **Virtual Internship**: Project completed through the Tata Group’s Virtual Job Simulation on the Forage platform.

## Problem Statement

Businesses generate vast amounts of data, yet struggle to extract meaningful insights for strategic decision-making. This project aims to bridge the gap between raw data and actionable intelligence by applying effective data visualization techniques to a retail transaction dataset.

## Goals

1.  To explore business scenarios and identify key questions answerable through data.
2.  To clean, structure, and process datasets to ensure quality and consistency.
3.  To apply visualization techniques (e.g., bar charts, scatter plots, line charts, dashboards) to highlight patterns and Key Performance Indicators (KPIs).
4.  To communicate insights effectively to stakeholders in a clear and visually compelling manner.
5.  To emphasize storytelling with data to facilitate strategic decision-making.

## Dataset

The dataset used for this project is `Online Retail.xlsx`. It contains over half a million retail transaction records, including:

  * Invoice details
  * Product codes and descriptions
  * Quantities and prices
  * Customer IDs
  * Transaction dates
  * Customer countries for sales analysis

## Methodology

The project follows a structured methodology:

1.  **Data Acquisition**: The dataset was provided by the organization.
2.  **Data Preprocessing**: Cleaned and prepared the dataset using Python by handling missing values, removing duplicates, and performing transformations. A `Revenue` column was derived (Quantity × UnitPrice).
3.  **Exploratory Data Analysis (EDA)**: Performed preliminary analysis to identify patterns, outliers, and correlations using basic plots.
4.  **Visualization Design and Implementation**: Applied advanced visualization techniques using Python libraries (Matplotlib, Seaborn, Plotly) and Tableau to create interactive dashboards.
5.  **Insight Generation**: Translated visual patterns into meaningful business insights.
6.  **Validation and Evaluation**: Evaluated the effectiveness of visualizations by checking clarity and support for data-driven decisions.
7.  **Deployment**: Presented final outputs via interactive dashboards.

## Dashboards Created

Four interactive dashboards were designed in Tableau to address specific business questions:

1.  **Sales Trend Analysis (CEO – Question 1)**: A time series visualization of monthly revenue for 2011 to understand seasonal trends and plan forecasts.
2.  **Country-Wise Performance (CMO – Question 2)**: A bar chart displaying the Top 10 countries by revenue (excluding the UK).
3.  **Customer Segmentation (CMO – Question 3)**: A Pareto-style visualization showcasing the Top 10 customers ranked by revenue to identify high-value customers.
4.  **Geographical Insights (CEO – Question 4)**: A global map visualization displaying demand distribution across all countries excluding the UK, optimized for clarity.

## Technologies Used

  * **Python**: For data preprocessing (Pandas, NumPy) and basic visualization (Matplotlib, Seaborn, Plotly).
  * **Tableau**: For creating interactive dashboards and advanced visualizations.
  * **Jupyter Notebook / VS Code**: For development and experimentation.
  * **Git / GitHub**: For version control.

## Setup Instructions

1.  **Clone the repository**:
    ``` bash
    git clone https://github.com/GPA95/Oneline_Retail_Data_Viz.git
    
    ```
2.  **Navigate to the project directory**:
    ``` bash
    cd Data-Visualization-Business-Insights
    
    ```
3.  **Install Python dependencies**:
    ``` bash
    pip install pandas numpy matplotlib seaborn plotly openpyxl
    
    ```
4.  **Open and run the Python script**:
      * The Python script (`.py` or `.ipynb`) used for data preprocessing and initial analysis can be found in the `scripts/` directory (or similar, depending on organization).
      * This script will clean the `Online Retail.xlsx` dataset and prepare it for Tableau.
5.  **Access Tableau Dashboards**:
      * Ensure you have Tableau Desktop installed.
      * Open the Tableau workbook file (`.twb` or `.twbx`) located in the `tableau/` directory (or similar).
      * Connect the dashboards to the cleaned dataset generated by the Python script.

## Future Scope

  * Integrating predictive analytics into dashboards (e.g., forecasting revenue trends using time-series models).
  * Automating dashboard updates with real-time data feeds.
  * Extending analysis to multi-year datasets for better long-term planning.
  * Including additional KPIs like profit margins, return rates, and customer lifetime value.
  * Experimenting with AI-driven insights in Tableau (e.g., natural language queries).

## Contact

Ammaar Ahmad Khan  
Email: ammaarahmadkhan16@gmail.com  
LinkedIn: [Ammaar Ahmad Khan | LinkedIn](https://www.linkedin.com/in/ammaar-ahmad-khan-0044b9320/)  
GitHub: [GPA95](https://github.com/GPA95)
