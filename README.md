# Pakistan Super League (PSL) Batting Analysis

This project analyzes the batting performance of players in the Pakistan Super League (PSL) using a provided dataset. The project aims to extract meaningful insights into player and team performance by applying various data analysis and visualization techniques.

## Project Overview

This project uses Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn to:

1.  **Data Acquisition:** The data for this project was scraped from the ESPN website using web scraping techniques. 
2.  **Data Cleaning and Preprocessing:** The scraped data is cleaned and preprocessed using Pandas to ensure consistency and accuracy. This includes handling missing values, converting data types, and removing irrelevant information.
3.  **Data Exploration and Analysis:** Various techniques are used to discover patterns and trends, including calculating averages, identifying top performers, grouping data by teams, and analyzing relationships between variables like runs, innings, and strike rates.
4.  **Data Visualization:** Matplotlib and Seaborn are used to create informative visualizations like bar plots, scatter plots, and histograms to effectively present the findings.

## Key Findings

The analysis revealed several interesting insights, including:

*   The top 5 players with the highest batting averages and strike rates in the PSL.
*   The team with the highest average number of runs per player and the team with the most centuries.
*   A positive correlation between innings played and runs scored.
*   Insights into players with the most not-outs and ducks and their impact on batting averages and strike rates.
*   Comparison of the run distribution of players who primarily score centuries versus those who score half-centuries.
*   The most efficient batsmen based on the runs-per-match ratio.
*   The correlation between total runs scored and strike rates among the top run-scorers.

## Technologies Used

*   Python
*   Pandas
*   NumPy
*   Matplotlib
*   Seaborn

## How to Run the Project

1.  Clone this repository: `git clone https://github.com/Dawood-Imran/PSL-Data-Set-Analysis`
2.  Install the required libraries: `pip install pandas numpy matplotlib seaborn`
3.  Download the dataset 'PSL_Batting_Dataset.csv' and place it in the project directory.
4.  Run the Jupyter Notebook or Python script to execute the analysis and generate visualizations.
