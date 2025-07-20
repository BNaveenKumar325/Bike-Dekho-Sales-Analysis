The main objective of this analysis was to explore and understand the sales trends in the biking industry by examining various customer attributes such as demographics, income, occupation, and preferences.
We used Microsoft Excel as a complete tool for this process ,starting from data cleaning to dashboard creation to generate actionable business insights.

Objective of the Analysis :
The aim of this project was:
•	To clean and organize raw sales data for meaningful analysis,
•	To perform exploratory data analysis using Excel formulas and PivotTables,
•	To identify key patterns in customer behavior, sales performance, and bike preferences,
•	And finally, to present all this using a visual, interactive dashboard that can help management make data-driven decisions.
Dataset Overview :
The dataset we used was provided in an Excel sheet named Raw Data.xlsx.
It consisted of customer-level transactional and demographic data, including:
•	Customer Name, Gender, Age, Region, Marital Status, and Income
•	Occupation and Product Line (type of bike)
•	Sales and Unit Sold information
•	Birth Date or Age (which we used to segment customers)

The dataset had some irregularities and required preprocessing before we could begin the actual analysis.
Data Cleaning and Preparation :
In the first phase, we cleaned and structured the raw data to make it usable.
Step 1: Removed Duplicates
We used the “Remove Duplicates” option under the Data tab to eliminate any repeated records that could skew the analysis.
 
Step 2: Handled Missing Values
Using filters, we searched for blanks in each column.
Where critical information like income or product category was missing, we either replaced it with ‘N/A’, imputed logical values, or removed the row if necessary.
Step 3: Standardized Formats
•	All date columns were converted to short date format.
•	Currency and income columns were formatted with the proper Indian Rupee symbol and comma separators.
Step 4: Created Calculated Colum
•	We also categorized customers into age groups like <30, 30-45, and >45.
This preprocessing ensured that our data was clean, uniform, and analysis-ready.

Exploratory Data Analysis (EDA) using PivotTables :
After cleaning, we moved on to the core of our analysis , using PivotTables and Excel formulas to uncover trends and insights.
Here are the main analyses we performed:
Sales by Gender
We created a PivotTable with Gender in Rows and Sales in Values.
 
Insight: Males accounted for a significantly higher number of purchases than females, indicating a male-dominant customer base.
Sales by Region
We used Region in Rows and summed up Sales or Units Sold.
 
Insight: The Western region recorded the highest sales, suggesting a stronger biking culture or better marketing presence in that zone.
Product Line Preferences by Age Group
We grouped customers into age bands and cross-tabulated them with bike types.
 
Insight: Customers aged 30–45 preferred mountain bikes, while those under 30 leaned more toward standard or road bikes.
Occupation vs Income vs Sales
We compared Occupation types with both Income and Total Sales.
 
Insight: Professionals and businesspeople contributed to the highest sales figures, confirming that higher income groups drive premium bike sales.
Marital Status vs Customer Count
We counted how many customers were single vs married.
 
Insight: Married individuals were more likely to purchase bikes, possibly due to family utility or stable income sources.

Visualization using PivotCharts :
We visualized our findings using PivotCharts:
•	Column Charts: Used for sales comparison across regions or gender.
•	Pie Charts: Showed product line preferences or gender split.
•	Line Charts: Represented time-based sales (if date-wise sales were available).

•	Bar Charts: Compared average income across occupations.

     

 
To make the visuals interactive:
•	We added slicers for Region, Gender, and Product Line.
•	This helped viewers filter and explore data dynamically.
•	All charts were formatted with readable labels, data bars, and color-coded categories for clarity.
 
Dashboard Design :
We then built an executive-style dashboard in a separate Excel sheet.
It included:
•	Clean layout with minimal distractions
•	Well-spaced visual elements like pie, column, and bar charts
•	Filters (slicers) to interactively change views based on user selection
•	Each element was aligned to provide a storyline , from customer demographics to sales breakdown and regional performance.
•	We avoided clutter and ensured consistency in fonts, color schemes, and chart types.
 
Key Business Insights :
Summarizing the most important insights from our analysis:
Demographics:
•	Married males aged 30–45 form the most frequent buyer segment.
•	Marketing should be tailored for this audience.
Regional Performance:
•	The Western region was the highest-selling zone.
•	This region can be prioritized for new launches or dealership expansion.

Income Impact:
•	Customers with higher income and professional occupations bought more premium bikes.
•	Financing or premium segment promotions could be targeted here.
Sales Distribution:
•	A few regions and occupations account for most of the sales.
•	This suggests focusing on high-conversion clusters.
These insights can guide targeted marketing, product planning, and regional strategies for Bike Dekho.
