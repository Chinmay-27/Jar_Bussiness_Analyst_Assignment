# Jar_Bussiness_Analyst_Assignment
 
**Business Analysis Project for Jar**

**Project Overview**

This project is a business analysis assignment for the Business Analyst
Intern role at Jar. The analysis is divided into three main parts:

1.  **Sales and Profitability Analysis**

    -   Merge the **List of Orders** and **Order Details** datasets
        based on Order ID.

    -   Calculate total sales (Amount) for each product category.

    -   Compute the average profit per order and profit margin (profit
        as a percentage of sales) for each category.

    -   Identify top-performing and underperforming categories and
        suggest possible reasons for the performance differences.

2.  **Target Achievement Analysis**

    -   Analyze the **Sales Target** dataset for the Furniture category.

    -   Calculate the month-over-month percentage change in target
        sales.

    -   Visualize the trends to identify months with significant target
        fluctuations and suggest strategies to better align targets with
        actual performance.

3.  **Regional Performance Insights**

    -   Identify the top 5 states with the highest order counts from the
        **List of Orders** dataset.

    -   For these states, calculate the total sales and average profit.

    -   Visualize regional disparities in sales and profitability, and
        recommend regions or cities to prioritize for improvement.

**File Structure**

-   **List_of_Orders_55FFC79CF8.csv**\
    Contains order-level data including Order ID, Order Date,
    CustomerName, State, and City.

-   **Order_Details_19795F61CF.csv**\
    Contains detailed information for each order, including Order ID,
    Amount, Profit, Quantity, Category, and Sub-Category.

-   **Sales_target_DD2E9B96A0.csv**\
    Contains monthly sales target data for the Furniture category. The
    date is stored in a \"Mon-yy\" format and is converted to a
    consistent \"dd-mm-yyyy\" format for analysis.

-   **Main.ipynb**\
    A Jupyter Notebook that includes all the analysis code: data import,
    cleaning, merging, computation of metrics, visualization, and
    insights.

-   **README.md**\
    This file provides an overview of the project, explains the file
    structure, and details how to run the analysis.

**Setup and Installation**

1.  **Environment Setup**\
    Ensure you have Python 3.7 or higher installed. Install the required
    Python libraries using pip:

2.  pip install pandas numpy matplotlib seaborn

3.  **Running the Notebook**

    -   Open the Main.ipynb file in Jupyter Notebook or your preferred
        IDE (e.g., VSCode or PyCharm).

    -   Run the cells sequentially to perform the analysis and generate
        the visualizations.

**My Approach**

For this project, my approach was as follows:

-   **Thoroughly Understand the Data:**\
    I began by exploring and cleaning the three datasets, ensuring
    consistent date formats and checking for missing values.

-   **Data Merging and Transformation:**\
    I merged the order-level data with the detailed order information
    using a common key (Order ID). This integration provided a
    comprehensive dataset for analyzing sales and profitability.

-   **Metric Computation:**\
    I computed key performance indicators such as total sales, total
    profit, average profit per order, and profit margin for each product
    category. For target achievement, I calculated the month-over-month
    percentage change in target sales.

-   **Visualization and Insights:**\
    I created clear visualizations (bar charts and line plots) to
    illustrate performance trends, identify top-performing and
    underperforming categories, and highlight regional disparities.
    These visualizations helped in drawing actionable insights and
    suggesting strategic improvements.

-   **Regional Analysis:**\
    I identified the top 5 states with the highest order count and
    analyzed their sales and profitability to recommend areas for
    improvement.

**Author**

-   **Name:** Chinmay Raut

-   **LinkedIn:** [Chinmay
    Raut](https://www.linkedin.com/in/chinmayraut276/)

**Analysis and Insights**

-   **Sales & Profitability:**\
    The analysis identifies which product categories perform best and
    which underperform based on average profit per order and profit
    margin. Possible reasons for these differences include pricing
    strategies, cost structures, market demand, and operational
    efficiencies.

-   **Target Achievement:**\
    The analysis of the Furniture category reveals months with
    significant changes in target sales. Strategies such as historical
    benchmarking, seasonality adjustments, and rolling averages are
    suggested to better align target expectations with actual
    performance.

-   **Regional Disparities:**\
    Visualizations highlight regional differences in sales and
    profitability. Regions with high sales but low profitability may
    require focused interventions (such as revising pricing models or
    improving operational efficiencies). Conversely, regions with high
    profitability despite lower sales could serve as benchmarks for best
    practices.

**Conclusion**

This project provides a comprehensive analysis of sales data, target
achievement, and regional performance for Jar. The insights derived from
this analysis can inform strategic decisions, optimize pricing and cost
management, and identify areas for targeted improvements.

