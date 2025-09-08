![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-red)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Plots-lightblue)
![Time Series](https://img.shields.io/badge/Time_Series-Analysis-green)
![Energy Analytics](https://img.shields.io/badge/Energy-Analytics-brightgreen)
![ENTSO-E](https://img.shields.io/badge/Data-ENTSO_E-lightgrey)
# Power Consumption Analysis - Sweden (2024)

This project analyzes hourly and monthly electricity consumption patterns in Sweden for the year 2024. The analysis includes identifying peak demand hours, comparing seasonal (winter vs. summer) consumption patterns, and visualizing winter consumption using heatmaps.

## Project Structure

Power-Consumption-Analysis-Sweden

├── Test Data/            
├── Visuals/                
├── Main.ipynb/           
└── README.md

## Analysis Overview

The notebook performs the following key steps:

1. **Data Loading & Preparation**
   - Loads hourly electricity consumption data from Excel.
   - Parses timestamps and sets them as the DataFrame index.

2. **Peak Demand Analysis**
   - Identifies the top 5% of hours with the highest consumption.
   - Visualizes hourly consumption and highlights peak hours.

3. **Monthly Consumption Patterns**
   - Calculates average monthly consumption.
   - Highlights winter months (November–March) in the visualization.

4. **Daily Patterns: Winter vs. Summer**
   - Compares average daily consumption profiles for winter and summer months.
   - Highlights evening peak hours.

5. **Winter Consumption Heatmap**
   - Visualizes average hourly consumption for each winter month using a heatmap.

## How to Run

1. Clone the repository.
2. Place the data file (`monthly_hourly_load_values_SE_2024.xlsx`) in the `Test Data/` directory.
3. Open `Main.ipynb` in Jupyter Notebook or VS Code.
4. Run all cells to reproduce the analysis and visualizations.

## Requirements

- Python 3.11+
- pandas
- matplotlib
- seaborn
- numpy
- Jupyter Notebook

## Data Source

The dataset used in this project is sourced from the [ENTSO-E Transparency Platform](https://www.entsoe.eu/data/power-stats/), which provides official electricity statistics for European countries. The data file used is specific to Sweden for the year 2024.
