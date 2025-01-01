# Finland Public Holidays Analysis

## Overview

This project investigates and analyzes the public holidays in Finland from 2000 to 2050. It focuses on identifying the number of "real off days" each year—days that are public holidays falling on weekdays and not overlapping with weekends. Additionally, the analysis highlights the best and worst years in terms of real off days.

## Key Features

- **Data Scope**: Covers public holidays in Finland from 2000 to 2050.
- **Weekend Adjustment**: Excludes holidays coinciding with weekends to determine real off days.
- **Yearly Insights**: Provides insights into the best and worst years based on the number of real off days.

## Methodology

1. **Data Collection**: 
   - Utilized the Python `holidays` library to fetch public holidays in Finland for the specified years. (https://github.com/vacanza/holidays/)

2. **Calculations**:
   - Identified the weekday for each public holiday.
   - Excluded holidays that fall on weekends.
   - Counted the remaining holidays to calculate real off days for each year.

3. **Analysis**:
   - Compared yearly data to identify trends.
   - Highlighted years with the maximum and minimum real off days.

## Results

- The project outputs a comprehensive list of public holidays with their respective classifications (weekday vs. weekend).
- Identifies the year with the most favorable distribution of public holidays for extended breaks.
- Highlights years with fewer opportunities for real off days.

## Technologies Used

- **Programming Language**: Python
- **Data Analysis Tools**: Pandas, NumPy
- **Holiday Library**: `holidays`
- **Environment**: Jupyter Notebook

## How to Use

1. Clone the repository.
2. Using conda (https://www.anaconda.com/download) to create a new environment and install the required packages.
    Environment: datafinnishholidays

    ```bash
    conda create --name datafinnishholidays
    conda activate datafinnishholidays
    ```

3. Install the required Python packages:
   ```bash
    pip install pandas numpy matplotlib holidays seaborn
    ```
4. Run the analysis script in Jupyter Notebook to generate the results.