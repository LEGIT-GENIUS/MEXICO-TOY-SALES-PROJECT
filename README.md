# MEXICO-TOY-SALES-PROJECT
![image](https://github.com/LEGIT-GENIUS/MEXICO-TOY-SALES-PROJECT/assets/139655319/a36029cd-529e-41fa-81ff-871c1e32538f)

# INTRODUCTION
The dataset contains records on the Sales & inventory for a fictitious chain of toy stores in Mexico called Maven Toys, it includes information on the product categories and description, stores daily sales transactions, and current inventory levels at each location. All records provided were slated from January 2022 to September 2023.

# DATA OVERVIEW
The dataset used for this project was presented in CSV excel file format and comprises of four different workbook namely:
1.	Inventories
2.	Sales 
3.	Stores 
4.	Location

And can be accessed on the webpage via the link: https://mavenanalytics.io/data-playground?page=6&pageSize=5 

# RECOMMENDED AND REQUIRED ANALYSIS
**1.	Which product categories drives the biggest profits? Is this the same across store locations?**

**2.	Can you find any seasonal trends or patterns in the sales data?**

**3.	Are sales being lost with out-of-stock products at certain locations?**

**4.	How much money is tied up in inventory at the toy stores? How long will it last?**

# TOOLS APPLIED IN THE PROCESS OF THE ANALYSIS

1.	Microsoft Excel 
2.	PowerBI

# SKILLS APPLIED DURING THE DATA AGGREGATION, CLEANING, AND ANALYSIS PHASE

**_1. Data cleaning_**

**_2.	Data transformation_**

**_3.	Cell referencing (absolute and relative) and formatting_**

**_4.	Filtering_**

**_5.	Data aggregation (mainly via the use of Xlook up function)_**

**_6.	Descriptive statistics_**

**_7.	Pivot table for summarizing data_**

**_8.	Data transformation on PowerBI_**

# ANSWERS TO BUSINESS QUESTIONS BASED ON THE ANALYSIS WITH THE USE OF MICROSOFT EXCEL AND POWERBI

**1.	Which product categories drive the biggest profits? Is this the same across store locations?**
The product category with the biggest profits is the Toy category with an approximated profit level of $1,079,527($1.08 million). However, this is not the same across all location, the product category driving the biggest profit in each location is written below;

* Airport: Electronics with its total profit valued at $108,197.

* Commercial: Electronics with its total profit valued at $287,574.
  
* Downtown: Toys with its total profit valued at $630,029.
  
* Residential: Toys with its total profit valued at $136,214.

**2.	Can you find any seasonal trends or patterns in the sales data?**

With regards to the seasonal trends in the sales pattern, emphasis is being laid on the monthly sales pattern for each distinctive year. The identified trends are as follows;

* A slight decrease in the sales from January to February, which is then accompanied by an increase in sales from February to march. In 2022, the sales between January and February decreased from $542,554.91 to $541,351.65 while in 2023, the sales between January and February decreased from $741,196.22 to $722,632.19. Also, in 2022, the sales between February and march increased from $541,351.65 to $589,485.19 while in 2023, the sales between February and March increased from $722,632.19 to $883,515.64.
  
* Also, in 2022, the volume of sales increased from march to April, decreased from April to May, and also decreased from May to June. This was a similar trend in 2023 as well.
   
* Also, sales dropped from July to august in both years. Given that the data that was made available stopped at September 2023, it was deem as wise not to go past September 2023 to identify the similar trends in the sales for both years.

**_However, despite the similarities in the monthly trends for each year, the following abnormalities were noted with regards to the sales trends;_**

* In 2022, there was an increase in sales between March and April which was not the same in 2023 because there was a decrease in sales between March and April.

* Also, there was a decrease in sales between June and July in 2022 while there was an increase in sales between June and July in 2023.

* In 2022, the sales level increased between august and September while the sales level decreased between August and September in 2023.

**3.	Are sales being lost with out-of-stock products at certain locations?**

Yes, apparently, when some products are out of stock, sales are being lost in certain locations but the differences lie the values and worth of sales that were actually lost in these locations. A breakdown of the lost in sales due to out-of-stock products in each location will be given below:

![image](https://github.com/LEGIT-GENIUS/MEXICO-TOY-SALES-PROJECT/assets/139655319/9e92ed8f-3255-49af-a278-3c8227abaa27)


Amounts in the diagram above are expressed in millions

**4.	How much money is tied up in inventory at the toy stores? How long will it last?**

About 29,742 units of items are tied up at the inventory level, valued at $300,210. Their valuation was do with respect to the cost of each item. In order to know how long this would last, an estimation of the monthly sales by the store needs to be conducted.

* In 2022, a total of 549,492 units were sold, making the average unit sold per-month to be equal to 45,791 (549,492/12).
   
* However, in 2023, a total of 541,073 units were sold, making the average unit sold per-month to be equal to 60,119 (541,073/9), considering the fact that the data in 2023 only comprises of records from January to September.
  
**So, given the following estimation, it is advisable to get the average of the monthly sales in 2022 and 2023 in order to get the proper monthly estimate for each month;**

45,791 + 60,119 = 105,910

102,910/2 = 52,955

Therefore, the actual average of units sold per-month is 52,955.

However, considering the amount of inventory that is tied up (29,742), it can be said that such won’t last more than a month.

# THE POWERBI DASHBOARD

![Screenshot 2024-01-29 221206](https://github.com/LEGIT-GENIUS/MEXICO-TOY-SALES-PROJECT/assets/139655319/045fe645-0585-4c4a-a04e-7297e9516304)

![Screenshot 2024-01-29 221351](https://github.com/LEGIT-GENIUS/MEXICO-TOY-SALES-PROJECT/assets/139655319/6f220e86-ff98-489b-836e-14bedaa6ee0c)

link to the interactive dashboard: https://app.powerbi.com/groups/me/reports/a60e9db5-d26a-4d6e-a042-3b98f5326d44/ReportSection?experience=power-bi

# ADDITIONAL INSIGHTS

This covers additional insights derived from the dataset that were not requested in the problem statement section but could provide additional insights for the prospect client which could the decision-making process in other case scenario.

* Of all the four (4) locations, over 58%of the overall sales took place at the Downtown store location. Making it the location with much more prospect in terms of sales.
  
* The most profitable month was in December 2022, which was also the month with the highest sales volume.
  
* In terms of sales, the product driving the most sale1s is Art & Crafts with a 30% share of the total sales followed by Toy with a 25% of the total sales volume. However, in 2022, Toy products have the largest volume of sales share accounting for 26% of total sales volume followed by Art & Crafts having a 22% share of the sales volume. Furthermore, in 2023, the case seems to be different Art and & Crafts had the most share of the sales volume with 38%, while Toy has 23% of the sales volume.
  
* Focusing on the different categories of products, the sales and profit pattern for electronic product happens to be on a steady decline from its initial position of $143,088 in January 20222. This is an indication that the product is not performing well in each location in terms of sales and profitability


![image](https://github.com/LEGIT-GENIUS/MEXICO-TOY-SALES-PROJECT/assets/139655319/c42f74af-574e-4700-b6fc-5843690fb62b)
