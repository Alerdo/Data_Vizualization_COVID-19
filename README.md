# COVID-19 Data Analysis Project
## COVID-19 Insights in England

## Overview

This project involves analyzing and visualizing COVID-19 data to understand the impact and trends of the pandemic. Below are the steps and key insights derived from the analysis.

## Data Cleansing Step

### 1. Excel File Adjustments
- Removed headers and footers for clarity.
- Unified column headers for consistency.

### 2. Data Processing with Pandas
- Transformed 'Time period April 27/December 18' into "Date Time Period" datetime column.
- Selected the last record of each month to simplify the x-axis in visualizations.

### 3. Visualization and Analysis
- Added confidence intervals for COVID-19 case percentages.
- Corrected data import issues in df_a1 regarding percentage calculations.


### 4. Modifications in Sheet 1E
- Merged columns for improved data handling in Pandas.

### 5. Analysis of Death Rates Excel File
- Created an additional sheet for easy data access.
- Added a column to compare COVID-19 deaths with other causes.
- Converted death rate percentages to numerical values for analysis.

### 6. Enhancements in Data Visualization
- Implemented FuncFormatter in Matplotlib for percentage symbols on y-axes.
- Customized x-axis ticks on bar plots for clearer display of COVID-19 cases.

## Conclusion

### Key Conclusions

#### Based on the Initial COVID Data for 2020:

1. **Seasonal Trends in COVID-19 Cases**:
   - An increase in COVID-19 cases is observed as winter approaches, a trend consistent over the past three years when comparing case rates across different years.

2. **Age Group Most at Risk**:
   - The age group of 65 and older has been at higher risk throughout the pandemic, with severe impacts in this demographic sometimes accounting for up to 60% of all deaths in certain periods.

3. **Pandemic Hotspots**:
   - London, the Southeast, and the East of England have been major hotspots for COVID-19, showing higher overall case numbers compared to other regions.

#### Insights from a Three-Year Trend Visualization:

4. **Analysis of COVID-19 Case Trends**:
     - The visualization of COVID-19 cases over three years indicates that the peak occurred in the March-April period of 2020, with a record of 4,141,600 positive cases, demonstrating the extensive reach of the virus at its peak.
    - Additionally, there is a noticeable decreasing trend in case numbers since this peak, suggesting a gradual decline in the spread of the virus.

   
   "The data on COVID-19 in England shows the virus's severity, particularly among those over 65, necessitates targeted measures in hard-hit regions like London, the Southeast, and East of England, and shows a trend of peaking followed by a gradual decrease in cases."
