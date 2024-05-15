# Swikriti E-Commerce Sales Dashboard

Welcome to the Swikriti E-Commerce Sales Dashboard

![](https://github.com/swatisahu1998/E-Commerce-Sales-Dashboard-Using-PowerBI/blob/main/Dashboard.jpg)

This all-encompassing dashboard typically incorporates numerous pivotal facets. Firstly, it provides a concise Sales Overview,  encapsulating pivotal statistics like overall revenue, order quantities, and average order value (AOV), often in conjunction with historical data for discerning enduring trends and patterns.  Sales by Product Category graphs furnish insights into the primary revenue-driving product categories, facilitating judicious inventory and promotional determinations. Furthermore, geographical Sales by Region illustrations shed light on regional sales disparities, guiding targeted market expansion endeavors. 
Customer Segmentation assessments categorize customers based on diverse attributes such as demographics or purchasing habits, empowering tailored marketing ventures.  Sales Funnel Analysis dissects the customer journey, spotlighting potential bottlenecks to conversion. The Top Selling Products segment accentuates the most successful items,  offering guidance for inventory management tactics. Metrics gauging Marketing Campaign Performance aid in assessing the effectiveness of promotional endeavors, assisting in refining marketing strategies. Insights into Customer Retention and Churn Rate inform strategies for fostering customer loyalty. Inventory Management metrics ensure optimal stock levels, averting stock shortages. Financial Metrics, including profit margins and order profitability, provide a snapshot of the enterprise's financial well-being. Finally, the integration of Custom KPIs allows for tracking against specific business objectives. In essence, a Power BI eCommerce Sales Dashboard empowers enterprises with actionable insights, fostering a culture of data-driven decision-making to elevate overall performance and profitability in the fiercely competitive landscape of online retail."This Power BI report provides a comprehensive analysis of your e-commerce sales data, allowing you to gain valuable insights into your business performance. Below is a detailed overview of the dashboard along with instructions on how to use it effectively.

## Key Metrics:

### Total Sales:
- View the total sales revenue generated for each quarter.
- Gain insights into your revenue trends over time.

### Total Quantity Sold:
- Analyze the total quantity of products sold in each quarter.
- Understand the demand for your products throughout the year.

### Total Profit:
- Track the total profit earned for each quarter.
- Monitor the profitability of your business over time.

### Average Order Value (AOV):
- Calculate the average order value for each quarter.
- Understand the average spending habits of your customers.

## Analysis by Quarter:

### Sum of Sales by States:
- Visualize the distribution of sales across different states.
- Identify regions with the highest and lowest sales performance.

### Sum of Quantity by Payment Mode:
- Analyze the quantity of products sold based on different payment modes.
- Understand how customers prefer to make payments for their purchases.

### Profit by Month:
- Explore the profitability of your business on a monthly basis.
- Identify months with higher profits and potential areas for improvement.

### Top Buyer:
- Identify your top customers based on their total spending.
- Build stronger relationships with your most valuable customers.

### Total Quantity by Category:
- Analyze the quantity of products sold within each product category.
- Identify which categories contribute the most to your overall sales.

### Sum of Profit by Subcategory:
- Drill down into the profitability of different product subcategories.
- Identify which subcategories are driving the most profit for your business.

**Data Analysis and Visualization Workflow:**

1. **Data Ingestion**: Imported the dataset, formatted as a CSV file, into Power BI Desktop to initiate the analysis process.

2. **Data Profiling**: Navigated to the Power Query Editor and activated the "column distribution," "column quality," and "column profile" options within the View tab. Ensured a comprehensive view of the dataset's structure and quality to lay a robust foundation for subsequent analysis.

3. **Extended Profiling**: Recognized the default limitation of profile display to 1000 rows and opted to profile the entire dataset for a more exhaustive understanding of its characteristics.

4. **Data Integrity Check**: Conducted a meticulous inspection of each column and identified the "Arrival Delay" column as the sole instance containing errors and empty values.

5. **Null Value Handling**: Deliberated on the treatment of null values within the "Arrival Delay" column, ultimately deciding to exclude them from calculations due to their minimal presence (less than 1%).

6. **Visual Theming**: Transitioned to the report view and curated the visual aesthetics by selecting a suitable theme under the View tab, ensuring a cohesive and visually appealing presentation.

7. **Rating Representation**: Acknowledging the dataset's inclusion of various ratings, introduced a dedicated visual element using the ellipses menu within the Visualizations pane, aimed at effectively portraying rating distributions.

8. **Interactive Filters**: Enhanced user engagement and exploration capabilities by integrating visual filters (slicers) for key categorical fields such as "Class," "Customer Type," "Gate Location," and "Type of Travel."

9. **Key Metric Display**: Introduced two cardinal visuals onto the canvas, each illustrating the average departure and arrival delays in minutes. Applied visual-level filtering to exclude null values from calculations, ensuring precision in the derived metrics.

10. **Customer Sentiment Analysis**: Enriched the analytical landscape by incorporating a bar chart, delineating the count of satisfied and neutral/unsatisfied customers. Augmented the visualization by incorporating the "Gender" field into the Legends bucket, facilitating nuanced insights into gender-specific sentiment trends.

11. **Ratings Visualization**: Leveraged the Ratings Visual to effectively communicate the spectrum of ratings encompassed within the dataset, providing a comprehensive overview of customer feedback and sentiment.

## How to Use:

1. **Download and Install Power BI Desktop:** If you haven't already, download and install Power BI Desktop from the official Microsoft website.
2. **Open the Power BI Report:** Open the Swikriti salesproject(1).pbix file using Power BI Desktop.
3. **Explore the Dashboard:** Navigate through the different tabs to explore each analysis.
4. **Customize Views:** Utilize the interactive features such as filters and slicers to customize the view according to your needs.
5. **Gain Insights:** Gain valuable insights into your e-commerce sales performance and make data-driven decisions to drive growth.

## Author Details:

- **Author:** [Swati Sahu](https://github.com/swatisahu1998)

