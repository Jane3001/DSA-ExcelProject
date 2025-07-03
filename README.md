# DSA-EXCEL PROJECT
## Project Topic: Amazon Product Review Analysis using Excel

### Project Overview
Analyzing Amazon Product and Customer review data to uncover trends and insights that can guide product improvement, marketing strategies and customer engagement. The objectives of the project is to analyze pricing and discount effectiveness, identify top-performing products, visualize rating distribution and estimate potential revenue across product categories. The final output is a dynamic Excel dashboard showcasing high-level metrics and product insights.

### Tools Used
- Microsoft Excel (Data cleaning, analysis, visualization)
- Pivot Tables (Aggregation of key metrics)
- Excel Charts (Visual display of trends and comparisons)
- Excel Formulas (Calculated columns for discount of 50% or more, potential revenue, propducts by rating and number of review combined)

### Data Cleaning & Preparation
The raw dataset contained product-level data scraped from Amazon product pages. Before analysis, the dataset was cleaned and prepared in Microsoft Excel using the following steps:
- Checked for duplicates
- Handled missing and inconsistent data
    - Verified that all essential columns had valid data.
    - Replaced missing or invalid values (in  actual price and rating).
- Converted to Excel Table using Ctrl + T. This allow for easy sorting, filtering, and referencing in pivot tables.
- Converted Text to proper datatypes and ensured that numeric fields like Actual Price, Discounted Price, Rating, and Rating Count were formatted as numbers.
- Created New Calculated Columns
    - Potential Revenue (=Actual Price * Rating Count)
    - Price Range Buckets (Products were categorized into three price ranges:=IF([@Actual_Price]<200,"<200",IF([@Actual_Price]<=500,"200–500",">500"))
- Validated data integrity by cross-checking calculations for accuracy.

![Data Cleaning 1](https://github.com/user-attachments/assets/e4f4ae31-792a-4613-a6b2-1f1fd716922f)

![Data Cleaning 2](https://github.com/user-attachments/assets/2cd39adc-423a-43d8-a7b8-719d6d72f92c)

### Exploratory Data Analysis (EDA)
Exploratory Data Analysis was conducted using Pivot Tables, charts, and Excel formulas to uncover patterns, trends, and key insights from the Amazon product review data.
- Average Discount % by product category helped identify categories with frequent price reductions which is Home Improvement category
- Pivot Table was used to count how many products belong to each category.
- Total reviews by category revealed that Electronics had the most customer engagement
- Average Actual Price vs. Discounted Price is compared across categories
- Distribution of Products with ≥50% discount highlight heavily discounted products
- Rating Distribution:
      - Top rated products identified products with the highest average ratings.
      - Most reviewed products highlighted products with the highest number of reviews.
- Revenue Estimations
      - Potential revenue by category calculated as:Potential Revenue = Actual Price × Rating Count showed that Electronics could drive the most sales based on popularity and price.
- Products were bucketed into <200, 200–500 and >500. This helped assess product distribution across price tiers.
- Discount % vs Rating explored whether deeper discounts affected customer ratings using a line chart.

![Pivot Table 1](https://github.com/user-attachments/assets/bd373adf-cd22-4515-8c9d-cb37d9ac6242)

![Pivot Table 2](https://github.com/user-attachments/assets/090c59c9-5f01-4a7d-9b4a-e882030ed381)

![Pivot Table 3](https://github.com/user-attachments/assets/315825ab-ce41-4bb2-8396-e58c4df231df)

![Pivot Table 4](https://github.com/user-attachments/assets/25d17c57-b4b0-4650-87ff-defdb019da48)

![Pivot Table 5](https://github.com/user-attachments/assets/19be406d-902c-4471-8486-828f19f8837c)

### Findings
Based on the exploratory data analysis performed using Excel, several key insights were uncovered from the Amazon product review dataset:
- Product Category Trends
     - Home & Kitchen and Electronics had the highest number of products listed.
     - Electronics has the highest total number of reviews, indicating strong customer engagement.
- Pricing and Discounts
    - Categories like Home Improvement and Computer&Accesories offered higher average discounts (58% and 53% respectively).
- Ratings Insights
    - Most products had ratings between 3.5 and 4.5, with very few below 2.0.
- Electronics generated the highest potential revenue, driven by both high prices and review volume.
- The majority of products were priced above ₹500, though low-priced items (<₹200) still received significant customer attention.

### Recommendations
Based on the insights generated from the analysis, the following recommendations are proposed to enhance product visibility, pricing strategy, and customer engagement on the Amazon platform:
- Allocate more marketing budget and ad spend to categories like Electronics which show high engagement and revenue potential.
- Promote top-rated products in low-competition categories to gain a competitive edge
- Review products offering ≥50% discounts for profitability concerns — ensure discounts are justified by demand or inventory needs.
- Encourage satisfied customers to leave reviews, especially for products with high ratings but few reviews.
- Track products with high Potential Revenue and ensure stock availability, fast shipping, and enhanced listing details.
- Evaluate how pricing and review volume influence estimated revenue and adjust strategy accordingly.




