# Automobile Sales Analysis During Recession Periods

## Project Overview

This project is a data visualization assignment from IBM's Data Visualization course. The goal is to analyze historical automobile sales data to understand how sales, consumer confidence, GDP, unemployment, and other factors have been impacted during recessionary periods. The project uses Python libraries like Matplotlib, Seaborn, and Folium to create insightful visualizations.

## Dataset

The dataset (`output.csv`) contains monthly data on automobile sales and related economic indicators from 1980 to 2023. It includes the following key variables:

*   **Date**: Month-end date of the sales observation.
*   **Recession**: A binary variable (1 for recession, 0 for normal period).
*   **Automobile_Sales**: The number of vehicles sold.
*   **GDP**: Per capita GDP in USD.
*   **Unemployment_Rate**: Monthly unemployment rate.
*   **Consumer_Confidence**: A synthetic index of consumer confidence.
*   **Seasonality_Weight**: A weight representing seasonal sales trends (e.g., higher sales in December).
*   **Price**: Average vehicle price.
*   **Advertising_Expenditure**: Advertising spend by the company.
*   **Vehicle_Type**: The type of vehicle sold (e.g., SuperminiCar, Sports, etc.).
*   **City**: The city of the sales office.

The dataset covers six recession periods:
1.  1980
2.  1981-1982
3.  1991
4.  2000-2001
5.  End of 2007 to mid-2009
6.  Feb-April 2020 (COVID-19 impact)

## Project Tasks & Visualizations

The project is structured as a Jupyter Notebook (`DV0101EN-Final-Assign-Part1-v1.jupyterlite.ipynb`) that walks through the following analysis tasks:

1.  **Task 1.1:** Create a **line chart** to show the fluctuation of average automobile sales from year to year, annotating the recession years.
    *   *Result:* A plot showing the overall trend of car sales, with noticeable dips during recession periods.

2.  **Task 1.2:** Create a **scatter plot** to analyze the correlation between advertising expenditure and automobile sales during non-recession periods.
    *   *Result:* The plot reveals that sales are volatile and not directly correlated with advertising spend alone, suggesting other market factors are at play.

3.  **Task 1.3:** Use a **bar chart** (via Seaborn) to compare the sales trend per vehicle type during a recession versus a non-recession period.
    *   *Result:* The plot highlights that sales for all vehicle types decline during a recession, with the most significant drops seen in "ExecutiveCar" and "Sports" categories.

4.  **Task 1.4:** Create **subplots** of line charts to compare GDP variation during recession and non-recession periods.
    *   *Result:* The plot shows that GDP is generally lower and more volatile during recessionary periods.

5.  **Task 1.5:** Develop a **bubble plot** to display the impact of seasonality on automobile sales for non-recession years, using `Seasonality_Weight` to represent the size of each bubble.
    *   *Result:* The plot shows a noticeable rise in sales in April and December, aligning with seasonal trends.

6.  **Task 1.6:** Create a **scatter plot** to identify the relationship between consumer confidence and automobile sales, and another to analyze the relationship between price and sales, during recessions.
    *   *Result:* The graphs indicate that during recessions, higher consumer confidence tends to boost sales, while higher prices tend to suppress them.

7.  **Task 1.7:** Create a **pie chart** to display the portion of advertising expenditure during recession and non-recession periods.
    *   *Result:* The pie chart shows that a much larger portion of the advertising budget is spent during non-recession times.

8.  **Task 1.8:** Create a **pie chart** to display the share of total advertising expenditure for each vehicle type during the recession period.
    *   *Result:* The chart shows that advertising spend is concentrated on lower-priced vehicle types during a recession.

9.  **Task 1.9:** Develop a **lineplot** to analyze the effect of the unemployment rate on vehicle type and sales during the recession period.
    *   *Result:* The plot shows that sales decline as unemployment rises, with the smallest cars (SuperMiniCar, SmallFamilyCar) showing the highest volatility.

10. **Task 1.10 (Optional):** Create a **choropleth map** to visualize the highest sales regions in the US during the recession period using Folium.

## Getting Started

### Prerequisites

Make sure you have Python 3.x installed on your system. It is recommended to use a virtual environment.

## License
This project is for educational purposes as part of an IBM Data Visualization course. The dataset is provided by IBM for the course.

## Author
**Puneet Tiwari**

## Acknowledgments
IBM Data Visualization Course
Skills Network Learning Platform
