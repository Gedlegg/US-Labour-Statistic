# US Labor Statistics Analysis

## Project Overview

This project analyzes US labor statistics to understand trends in wages and employment across various industries and states. The analysis was conducted using Excel, employing various formulas to calculate key metrics such as average wages by industry, total employees by industry, and comparisons by state. The insights gained aim to support policy decisions and workforce planning.

## Technologies Used

- **Excel**: For data analysis and processing.

## Installation

1. Clone the repository to your local machine using:

   ```bash
   git clone https://github.com/yourusername/us-labor-statistics-analysis.git
   ```

2. Open the `US_Labor_Statistics_Data.xlsx` file in Microsoft Excel or any compatible spreadsheet software.

## Usage

- Open the `US_Labor_Statistics_Data.xlsx` file and navigate through the worksheets to explore the data analysis.
- Review the calculations for key metrics to understand wage and employment trends.

## Key Metrics Calculated

- **Average Wage by Industry** : Calculated average annual wage using data from different industries.
- **Employees by Industry** : Total number of employees calculated with:

=SUMIFS(Data!E:E, Data!B:B, H4, Data!A:A, 'Data Prep'!$B$15)

- **Wage & Employee Trends** : Average wage trends determined with:

=AVERAGEIFS(Data!F:F, Data!B:B, 'Data Prep'!$B$3, Data!A:A, 'Data Prep'!K4)

- **Comparisons by State** : Employees per 1000 capita and total employees using:

=SUMIFS(Data!E:E, Data!B:B, 'Data Prep'!$B$3, Data!A:A, 'Data
Prep'!$B$15, Data!C:C, 'Data Prep'!O3)

## Findings

- Analyzed wage trends across different industries and states, providing insights into labor market conditions.
- Generated visualizations to illustrate wage disparities and employment levels, aiding in understanding regional workforce dynamics.
