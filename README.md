# Online Retail Sales Summary


### Project Overview 

This project summarizes the key details of a retail sales of an online store which occured between 12/01/2010 and 
12/09/2011. The aim is to identify key performance indicators and sales trends useful for management decision-making to drive more sales. 

### Data Source

[Download_here](https://docs.google.com/spreadsheets/d/1WelShCOKNbUkm8Boi9LZP5JEcH-KpXUv/edit?usp=drivesdk&ouid=104813495679773169446&rtpof=true&sd=true)

### Tools

- Microsoft Excel: Data Cleaning
- Microsoft Power BI: Data analysis and visualization


### Data Cleaning  

The following tasks were performed:

- Data loading and inspection
- Rows with Quantity or Unit price columns less <=0 were removed
- Total price was calculated (Quantity * Unit price)
- Data formatting in preparation for the analysis.
The cleaned data is saved on another excel sheet in the same document and labeled 'dup'

### Data Analysis 

The data was analyzed to find out the following:

1. The total amount of sales made during the period under consideration
2. The total quantity of goods sold during the outlined period
3. Apart from UK, what are the top countries where sales were generated?
4. Best performing sales month


The visualization was done using Power BI. Find [dashboard](https://github.com/AdeyilolaAyomide/Online-Retail-Sales-Summary/blob/067eafdfb05c1233758d3f74446e9f7a19f6fc63/Online%20sales%20summary.pbix). Find [pdf_version](https://github.com/AdeyilolaAyomide/Online-Retail-Sales-Summary/blob/067eafdfb05c1233758d3f74446e9f7a19f6fc63/Online%20sales%20summary.pdf)

### Results 

The results are as follows:

1. The total amount of sales during the outlined period is $10.66M
2. The total quantity sold: 5.59M products
3. Sales from United Kingdom contributed 84.6% of the total purchase. Apart from UK, purhcase was made from 37 other countries. The top 10 are: Netherlands, EIRE, Germany, France, Australia, Spain, Switzerland, Belgium, Sweden and Japan in descending order.
4. The highest purchase was recorded in November, 2011. Based on MoM% change, May 2011 recorded the highest purchase compared to the previous month with an increase of 43.27% compared to April, 2011.

### Recommendation 
1. The store should reinforce marketing in the top 10 countries (apart from UK) that contributed to the purchase from the online store in order to increase visibility and drive more sales in those countries.
2. The store experienced more sales between September - November, 2011 compared to the previous month. This is suggestive of a seasonal influence on the sales. Hence, more marketing activities should be targeted towards the that period.  

### Limitations 
1. The sales record for the December, 2011 is not complete (spans between 1st and 9th day of the month) hence the month of December could not be well accounted for in the analysis
2. Data rows deleted during data cleaning are unaccounted for in the analysis.
