# US Debt Tracker | Excel

An interactive US Debt Tracker built in Excel, showcasing the intersection of data analysis and visual storytelling. This project, completed through Analyst Builder, documents the lifecycle of U.S. National Debt via data cleaning, trend analysis, and dynamic reporting. It serves as a practical application of my CompTIA Data+ skills, focusing on making high-level economic data accessible and actionable.

### 💡 Key Insights & Findings
* 16% increase of public debt in 2008. Could be due to **economic recession**.  

* Almost 20% increase of public debt in 2020. Most likely due to the global pandemic.

* Monthly average of total debt chart shows that January has the highest average total debt. This could be attributed to Christmas/Thanksgiving spending in December with statements coming in January.

* The lowest month average is April which could be attributed to IRS Tax Refunds which take place during this time.  


![Graphics Artworks Excel Visualisations Scrrenshot](images/Graphics_Artworks_Excel_Screenshot.png)


### 📁 Project Questions:
1. What was the Yearly Debt Percentage Increase for each year compared to the previous year?
2. Which months historically have seen the highest/lowest increases in Total debt?
3. What is the projected growth of the publicly held debt in the next few years?

**Data Dictionary:**
Debt Held by the Public - This is the portion of the US public debt that is held by individuals, corporations, foreign governments, and other entities outside of the US government.
Intragovernmental Holdings - This is the portion of the US public debt that is held by other US government agencies.
Total Public Debt Outstanding - Total Public Debt Outstanding

🛠️ Key Technical Skills includes:  
<ins>Data Cleaning</ins> The data set included dates as columns rather than rows and so the data need to be transposed.

<ins>Pivot Tables</ins> Creating pivot tables to understand the figures using aggregations such as averages and sums.

<ins>Data Visualisation</ins> To answer the questions for the project I created line charts and a column chart to convey the public debt in the US. 



### 🧹 Phase 1: Data Cleaning Highlights
The raw data contained several columns that had no meaning for my objective. It was also missing a brand column as I intended to append the 3 tables in MySQL. 

Date column data type: MySQL brought in the date column as a text field which had to be rectified using the STR_TO_DATE function.



### 📊 Phase 2: Exploratory Data Analysis
With the tables cleaned and joined, I exported a csv file that I could use in excel to perform EDA and build a dashboard to showcase the derived stats. 

Line chart to show trend from DEC 2021 - FEB 2026.  

Pie chart to show a split of Large print run vs a Medium print run during DEC 2021 - FEB 2026.

Bar chart to show the number of print runs during DEC 2021 - FEB 2026.

KPI card to show the number of individual artworks sent to print during DEC 2021 - FEB 2026.
