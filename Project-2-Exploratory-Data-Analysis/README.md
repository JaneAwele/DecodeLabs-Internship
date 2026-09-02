 Project 2: Exploratory Data Analysis

Week 2 of my Data Analytics Internship at DecodeLabs

About the Dataset
The same e-commerce dataset from Project 1 (1,200 orders, 14 columns), this time 
analyzed to understand the patterns, trends, and distributions hidden inside it.

What I Did
The goal here wasn't to clean the data anymore, it was to actually understand it.

I calculated basic statistics (mean, median, count) for Quantity, Unit Price, and 
Total Price, then broke revenue and order counts down by Product, Order Status, 
Payment Method, and Referral Source to look for trends.

To find outliers, I used the IQR (Interquartile Range) method, calculating Q1, Q3, 
and a statistical upper bound, then flagging any order with a Total Price above that 
line as unusually high.

 Key Findings
1. Order values are right-skewed, the average order value is higher than the 
  median, meaning a handful of large orders are pulling the average up.
2. 8 statistical outliers** were identified, all sharing the same pattern: the 
  maximum quantity (5) combined with a high unit price, legitimate large orders, 
  not data errors.
3. Cancelled orders were the most common order status (250 orders), worth 
  flagging as a potential business concern if this were a real store.
4. Instagram was the top referral source, (259 orders), suggesting it's an 
  important acquisition channel.
5. Revenue was spread almost evenly across all products and channels, no single 
  category dominated.

Key Takeaway
Descriptive statistics only tell half the story. The real insight came from combining 
the numbers with context, a high mean vs. median told me the data was skewed before 
I even looked at a single chart, and the IQR method gave me an objective way to say 
"this is unusual" instead of just eyeballing it.

 Skills & Tools
Data analysis, descriptive statistics, analytical thinking · Microsoft Excel 
(QUARTILE, SUMIF, COUNTIF, INDEX/MATCH, LARGE)


📁 [View deliverable](Dataset%20for%20Data%20Analytics%202.xlsx)

Note: this is an Excel file, click Download on the file page to open it and see 
the full analysis, including live formulas.
