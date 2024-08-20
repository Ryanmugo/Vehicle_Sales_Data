# Vehicle Sales Analysis

## Project Overview

This analysis was conducted to provide insights into vehicle sales, identify opportunities for cost reduction, and propose strategies for improving profits and sales in the upcoming year (2013). The analysis was performed using two primary tools: Excel and Tableau.


## Key Objectives:

  - **Reduce Production Costs:** Assess potential savings through cost reduction strategies.
  - **Improve Profit Margins:** Identify high-margin products and areas where profitability can be enhanced.
  - **Boost Sales**: Analyze sales trends to recommend strategies for increasing sales in 2013.

### 1. Excel Analysis

#### 1.1 Data Preparation

   - **Data Cleaning:** The raw dataset was first cleaned in Excel. This involved:

        - **Removing Duplicate Records:** Ensured that there were no duplicate entries to maintain data accuracy.
        - **Handling Missing Data:** Missing data points were either filled based on available information or removed if they were insignificant.
        - **Standardization:** Ensured that all data was in a consistent format for easier analysis (e.g standardizing date formats).

#### 1.2 Analysis Approach

   - **Overall Summary:** The analysis in Excel provided a broad, unfiltered overview of the entire dataset without focusing on specific years or quarters.
   - **Pivot Tables:** Pivot tables were used extensively to:

       - Summarize total sales by manufacturer.
       - Identify the top 10 best-selling cars across the period.
       - Analyze peak sales during specific launch periods.
       - Determine the best-performing cars in terms of fuel efficiency, profit margins and pricing.

#### 1.3 Key Findings from Excel

   - **Top 10 Best-Selling Cars:** Identified Toyota as the top-selling manufacturer with total sales of 568,133 units.
   - **Profit Margins:** Toyota also led in profit margins, indicating strong profitability.
   - **Fuel Efficiency:** Dodge and Toyota stood out for their balance of fuel capacity and efficiency.
   - **High-Priced Cars:** Dodge had the highest total price among the analyzed cars.
   - **Cars with Below-Average Margins:** Chevrolet had the lowest profit margins, highlighting potential areas for improvement.

#### 1.4 Limitations of Excel Analysis

  - **Lack of Time-Baed Filtering:** The Excel analysis did not segment data by specific years or quarters. It provided a comprehensive overview of the entire dataset without temporal filters, which was later addressed in the Tableau analysis.


### 2. Tableau Analysis

#### 2.1 Data Import and Preparation

   - The cleaned data from Excel was imported into Tableau for further analysis.
   - **Filtering by Year and Quarter:** Tableau allowed for dynamic filtering of the data by year and quarter, enabling a more granular analysis of trends over time.


#### 2.2. Analysis Approach

  - **Sales Trend Over Time:** Tableau's visualization capabilities were used to analyze sales trends across diferent quarters in 2011 and 2012.
  - **Cost Reduction Impact:** Simulated the impact of a 5% reduction in production costs on overall savings and profitability.  
  - **Performance Shift Analysis:** Compared performance shifts between specific quarters (e.g Q2 2011 vs Q2 2012) to identify changes in sales strategies or market conditions.
  - **Detailed Product Analysis:** Tableau was used to drill down into specific products, manufacturers and periods to extract actionable insights. 

#### 2.3 Profit Margin by Manufacturer

  - **Significant Decline in Q1 2012:** Noticed a sharp decline in sales in Q1 2012 compared to Q1 2011, indicating potential market or internal challenges.
  - **Strong Year-End Performance in 2011:** Q4 2011 showed a significant peak in sales, possibly due to successful promotions or seasonal demand.
  - **Partial Recovery in Q2 2012:** After a poor Q1 2012, sales recovered in Q2, suggesting that some corrective actions might have been taken.
  - **Cost Savings Potential:** Demonstrated that a 5% reduction in production costs could lead to significant savings, particularly in a year with higher sales.

#### 2.4 Advantages of Tableau Analysis

  - **Time-Based Filtering:** Unlike Excel, Tableau provided the flexibility to filter and analyze data by specific time periods (year and quarter), offering deeper insights.
  - **Interactive Visualizations:** Tableau's interactive dashboards allowed for real-time exploration of data, making it easier to identify trends and patterns.


### 3. Recommendations

Based on the analysis conducted using Excel and Tableau, the following recommendations are proposed:

  - **Implement Cost Reduction Strategies:** Focus on reducing production costs by at least 5% to improve profitability, especially during low sales periods.
  - **Enhance Q4 Promotions:** Replicate successful strategies from Q4 2011 to boost year-end sales in 2013.
  - **Monitor Market Trends:** Keep a close watch on market conditions and consumer preferences to avoid drastic declines like those observed in Q1 2012.
  - **Invest in High-Margin Products:** Prioritize the production and marketing of high-margin products, such as those from Toyota and Dodge, to maximize profits.
  - **Address Below-Average Margins:** Investigate and address the factors leading to low profit margins for manufacturers like Chevrolet.


### 4. Conclusion

The combination of Excel and Tableau provided a comprehensive analysis of vehicle sales data, from broad overviews to detailed time-based insights. While Excel offered a solid foundation for understanding overall trends, Tableau enabled deeper exploration, particularly with its powerful filtering and visualization capabilities. Together, these tools allowed for a thorough analysis that informed strategic recommendations for improving sales and profitability in 2013. 
 
  
 
### 5. Fuel Capacity and Efficiency

- **Top Manufacturers by Fuel Capacity:**
  - **Dodge:** 125.4 units
  - **Toyota:** 80.6 units
  - **Jeep:** 59.5 units

- **Top Manufacturers by Fuel Efficiency:**
    - **Toyota:** 133 units
    - **Dodge:** 125 units
    - **Nissan**: 71 units
      
  - **Insights:** Dodge has the highest fuel capacity, which might appeal to a different customer segment compared to the highly efficient Toyota vehicles.

### 6. Pricing and Profitability

- **Top 3 Manufacturers by Price:**
    - **Dodge:** $161,750
    - **Acura:** $91,900
    - **Lincoln:** $82,410

- **Average Price:** $27,455.70
- **Average Profit Margin:** $11,040.40

## Advanced Analysis

## 1. Trend Analysis

- **Sales Over Time:**

    - Significant peaks in sales were observed during specific months, particularly in September and August of 2011.
    - The seasonal trend suggests that targeted marketing during these months could amplify sales.
 
## 2. Profitability Across Models

- **Profit Margins:**

    - Toyota and Dodge have the highest profit margins, making them the most profitable manufacturers.
    - Models with lower-than-average profit margins were identified, offering an opportunity for price adjustment or cost reduction strategies.

## 3. Linear Regression Analysis

- **Relationship Between Sales Volume and Profitability:**

   - A linear regression model was used to analyze the relationship between sales volume and profitability.
   - The analysis indicated a positive correlation, meaning that as sales volume increases, profitability tends to rise. This underscores the importance of driving sales to boost overall profit.

## Recommendations

## 1. Sales Improvement Opportunities
  - **Focus on High-Margin Models**

     - **Toyota and Dodge:**
         - **Toyota:** $568,133
         - **Dodge:** $507,261

     - **Profit Margins:**
         - **Toyota:** $113,626.60
         - **Dodge:** $101,452.20
           
     - **Strategy:** Increase marketing efforts for Toyota and Dodge during the months of August and September, where sales are highest. For instance, a 10% increase in marketing budget could lead to a potential sales increase of 5-7% during these periods, translating to an additional $25,000 to $35,000 in sales.




## 2. Cost Reduction Strategies

  - **Optimize Productions Costs**

     - **Average Production Costs:** $44,161.62
     - **Potential Savings:** By renegotiating supplier contracts or implementing lean manufacturing techniques, we could aim to reduce production costs by 5-10%. This could result in savings of approximately $2,200 to $4,400 per vehicle, improving overall profit margins by 5-8%.

## 3. Customer Retention and Expansion

**Objective:** Increase customer retention and repeat purchases by implementing a loyalty program.

**Strategy and Potential Impact:**

  - **Customer Retention Increase:** By introducing a loyalty program, we anticipate an increase in repeat customers by 10%.
  - **Sales Growth:** This increase in repeat customers is expected to lead to a 3% rise in total sales.
  -  **Financial Impact:** Considering the average sale per customer is $30,000, this strategy could result in approximately $90,000 in additional sales annually.

**Example Calculation:**
  - If our current total sales amount to $3 million annually, a 3% increase would add $90,000 to our annual revenue.
  - This strategy not only boosts sales but also enhances customer satisfaction and brand loyalty, which is crucial for long-term business sustainability and growth.

## Visualization and Reporting

  - The analysis was visualized using Tableau, creating dashboards to provide actionable insights and support decision-making.

  **Dashboards Created:**

   -**1. Sales Trends Over Time:** Visualizes sales fluctuations and peak periods across 2011 and 2012.
   -**2. Top-Selling Vehicles:** Highlights the best and worst-performing vehicle models.
   -**3. Profit Margin Across Car Models:** Shows profitability across different manufacturers.
   -**4. Sales Volume vs. Profitability (Linear Regression):** Analyzes the relationship between sales volume and profitability.

   **Dashboard Overview:**

   - To see an image of the dashboard, click the image below:

   [![Vehicle Sales Dashboard](https://github.com/Ryanmugo/Vehicle_Sales_Data/blob/main/Vehicle%20Sales%20Dashboard.png)](https://github.com/Ryanmugo/Vehicle_Sales_Data/blob/main/Vehicle%20Sales%20Dashboard.png)

## Conclusion

The analysis done provides actionable insights into the vehicle sales landscape, identifying both opportunities for growth and areas for cost reduction. By imlementing the recommended strategies, the business can:

  - **Increase Sales:** A potential 5-10% increase, adding $110,000 to $220,000 to total sales.
  - **Reduce Costs:** Potential savings of 8-10% in production and logistics, translating to $140,000 to $190,000 annually.
  - **Improve Profit Margins:**  Optimizing sales and cost strategies could result in a 7-12% improvement in overall profit margins.

By focusing on these strategies, the business can enhance its market position and drive significant economic value.

## Appendices 

## Sales Statistics 

  - **Average Sales:** $55,202.03
  - **Median Sales:** $31,723.50
  - **Total Sales(2011-2012):** $2,208,081

## Price Statistics

  - **Average Price:** $27,455.68
  - **Median Price:** $23,139.00

## Profit Margin Statistics

  - **Average Profit Margin:** $11,040.41
  - **Median Profit Margin:** $6,344.70

## Cost of Production Statistics

   - **Average Cost of Production:** $44,161.62
   - **Median Cost of Production:** $25,378.80
