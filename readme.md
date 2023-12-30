# COVID-19 Data Visualization Repository

## Overview

This GitHub repository contains Python scripts for visualizing COVID-19 data using various plotting techniques. The data source used for this project is the "Our World in Data" COVID-19 dataset, and the visualizations focus on vaccination status, bubble charts, and bar graphs to illustrate the progression of the pandemic.

## Files

### Dataset
- The primary dataset used is located at: [owid-covid-data.csv](C:\Users\meena\Downloads\owid-covid-data.csv\owid-covid-data.csv)
- This dataset is sourced from "Our World in Data" and provides comprehensive COVID-19 statistics for various countries.

### Python Scripts
1. **[iitbombay.ipynb](iitbombay.ipynb):**
    - This script loads the COVID-19 dataset, processes the data, and creates visualizations using Matplotlib, Seaborn, and Plotly Express.
    - It includes functions for drawing a pie chart, bubble plot, and bar graph.

## Usage

1. **Clone the Repository:**
   ```
   git clone https://github.com/Goutammeena03/covid-19-data-visualise.git
   ```

2. **Install Dependencies:**
   ```
   pip install pandas matplotlib plotly seaborn
   ```

3. **Run the Scripts:**
   - Open and run the `iitbombay.ipynb` script to generate visualizations.

## Visualizations

1. **Vaccination Status in India Pie Chart:**
   - Displays the distribution of fully vaccinated, partially vaccinated, and not vaccinated individuals in India.

2. **Yearly Month-wise COVID-19 Statistics Bubble Plot:**
   - Depicts the progression of COVID-19 cases in a bubble plot, with bubble sizes representing population and color indicating the year.

3. **Total Cases by Year-Month Bar Graph:**
   - Presents a bar graph illustrating the total COVID-19 cases in India, with facets for each month and year.

## Notes

- Ensure the provided dataset path is correct: [owid-covid-data.csv](https://www.kaggle.com/datasets/georgesaavedra/covid19-dataset).
- Adjust the file paths and names as needed in the scripts.

## Dataset Columns

- **location:** Country or region name.
- **date:** Date of the recorded data.
- **people_fully_vaccinated:** Number of people fully vaccinated.
- **people_vaccinated:** Number of people partially or fully vaccinated.
- **population:** Total population of the country or region.
- **year_month:** Period in year-month format.
- **year_month_numeric:** Numeric representation of the year-month period.
- **total_cases:** Total reported COVID-19 cases.
- **month:** Name of the month extracted from the date.
