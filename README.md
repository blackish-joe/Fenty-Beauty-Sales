<h2>Fenty-Beauty-Sales</h2>

![fenty image](https://github.com/blackish-joe/Fenty-Beauty-Sales/assets/59397702/13d3f8ca-89e1-41b9-8f70-865d5b83bc1e)
This datasent can be downloaded <a href="https://shorturl.at/QEV6B"> Here </a>

# Sales Dataset Analysis

## Overview
This project analyzes a dataset on sales of makeup accessories obtained from a research study on YouTube.
The objective of this analysis is to identify patterns and trends in sales data specifically focused on the first quarter.

## Table of Contents
- Overview
- Data Description
- Tools Used
- Analysis and Insights
- How to Use This Repository
- Conclusion
- Future Improvements

## Data Description
The dataset used for analysis consists of sales data for makeup accessories collected from a YouTube research study. 
It comprises 759 records across 11 columns, encompassing various data types including datetime, integer, and object formats. 
The dataset provides comprehensive insights into sales transactions and related attributes over the specified period, 
facilitating detailed analysis and exploration of sales patterns within the first quarter.

## Tools Used
The tool use for this analysis is:
Python (including pandas, plotly, re)

## Analysis and Insights
From the imported dataset the dataframe consist of 11 columns

![Screenshot 2024-06-26 235211](https://github.com/blackish-joe/Fenty-Beauty-Sales/assets/59397702/c240ceb6-f299-4a79-9809-d3db0bcf1860)

for clarity and good data cleaning the gender columns was replace and from M to Male, F to Female
I also convert the date to a pandas datetime for easier timeseries analysis.
Looking across the data, we need to add day and month to corresponding our sales for the day and month to know
specific day and month with high sales.
from our analysis the <h4><b>Total sales : $51279.0<b></h4>
The Total sales by Gender shows us that females are the frequent customers at Fenty Beauty

![gender sales](https://github.com/blackish-joe/Fenty-Beauty-Sales/assets/59397702/3f51f956-07b5-46be-b88f-56610eb2b6d7)


with Product categories ranging from Lipstick, Lipgloss, Concealer, Foundation, Highlighter, to Contour.
which shows that Highlighter has the highest sales with over 14k unit sold, Foundation came seconf with over 12k unit solds, and the lowest been Contour with 4k unit sold shows that it is the least patronize.


![categories sales](https://github.com/blackish-joe/Fenty-Beauty-Sales/assets/59397702/bd712dc1-b901-4fe6-9a90-8b2dc0144549)


I deduce the top selling product is Match Stix Contour Skinstick under the category of Contour which is lowest in revenue due to low price of the product.


![Screenshot 2024-06-27 001820](https://github.com/blackish-joe/Fenty-Beauty-Sales/assets/59397702/c1f87f46-abc5-4406-b12c-5a5ce1536d14)


![top product](https://github.com/blackish-joe/Fenty-Beauty-Sales/assets/59397702/e154cf38-0713-4e87-a74a-671a75daa032)


This lead to month with the highest revenue and discovered that March due to cold nature of the weather which allows for makeup to last longer when apply to the face.
with both New York and Los Angelos both dominating the city with higest revenue .


![month](https://github.com/blackish-joe/Fenty-Beauty-Sales/assets/59397702/bf89b7f3-01b6-4279-b819-36fca8f839e8)

![city](https://github.com/blackish-joe/Fenty-Beauty-Sales/assets/59397702/7032cc83-668d-4437-9a78-2665fd523345)


And lastly it show the week sales in which friday and saturday have high sales turnover.


![days](https://github.com/blackish-joe/Fenty-Beauty-Sales/assets/59397702/0a7a1146-4d4a-4609-aa8f-86ded6b5cd77)


## How to Use This Repository
Provide instructions on how to clone, install dependencies, and run your code locally. For example:
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/sales-analysis.git
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```
   python analyze_sales_data.py
   ```

## Conclusion
### Summary of Findings
1. **Sales Trends:** There was a noticeable increase in sales in March compared to January and February. This trend suggests a potential seasonal influence or successful promotional activities during this period.
2. **Top-Selling Category:** Highlighter and foundations were the top-selling makeup category, indicating a strong consumer preference for these items in the first quarter.
3. **Customer Demographics:** A significant portion of sales came from Los Angeles and New York, highlighting the target market for makeup accessories.
4. **Top Customers:** the data shows the company top five customer.
   
![Screenshot 2024-06-27 004612](https://github.com/blackish-joe/Fenty-Beauty-Sales/assets/59397702/1fa536cd-6cca-453c-a488-04c1487ed594)

5. **Average Order Value:** The average order value was highest in February, possibly due to special events or promotions around Valentine’s Day.

### Implications
- **Marketing Strategies:** The insights into top-selling products and customer demographics can help businesses tailor their marketing campaigns and product offerings to better meet customer preferences.
- **Seasonal Promotions:** The increase in sales in March suggests that seasonal promotions and marketing efforts can significantly boost sales. Businesses should consider planning special promotions or product launches during peak sales periods.
- **Targeted Advertising:** Understanding that the younger demographic is a key consumer group, businesses can focus their advertising efforts on platforms and channels that are popular among this age group.


## Future Improvements

### Potential Enhancements and Analyses
1. **Detailed Customer Segmentation:**
   - Perform a deeper segmentation analysis to identify specific customer personas based on demographics, purchasing behavior, and preferences. This can help in creating more targeted marketing strategies.

2. **Predictive Sales Modeling:**
   - Develop predictive models to forecast future sales trends using machine learning algorithms. This can aid in inventory management, demand planning, and setting realistic sales targets.

3. **Seasonal Impact Analysis:**
   - Extend the analysis beyond the first quarter to understand how sales fluctuate throughout the year. This can reveal seasonal trends and help businesses plan better for peak and off-peak periods.

5. **Product Recommendation System:**
   - Implement a recommendation system based on historical sales data and customer behavior to suggest products to customers, thereby potentially increasing sales and enhancing customer experience.

6. **Geographical Analysis:**
   - Conduct a geographical analysis to identify which regions have the highest sales and tailor regional marketing campaigns accordingly. Understanding regional preferences can help in optimizing supply chain and distribution strategies.

7. **Price Sensitivity Analysis:**
   - Analyze the impact of pricing changes on sales volume to understand price elasticity. This can help in setting optimal pricing strategies to maximize revenue.

8. **Cross-Selling and Up-Selling Opportunities:**
   - Identify opportunities for cross-selling and up-selling by analyzing purchase patterns. This can help in increasing the average order value and enhancing customer satisfaction by offering complementary products.


---

copyright Joseph (Blackish-Joe)
