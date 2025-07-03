# DSA-ExcelProject

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

