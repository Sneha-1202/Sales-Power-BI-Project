# Sales Data Analysis


## Project Statement:

The Sales Data Dashboard goes beyond just numbers, offering insights into sales trends over time and the connection between sales and profits. It provides a clearer perspective, making decision-making more informed and strategic.

## Key features include:

-Top & Bottom 5 Products: Identifies the best and worst-performing products, allowing the company to optimize inventory, pricing, and marketing strategies.


-Discount & Order Insights: Displays the average discount offered and the total number of orders placed, helping in evaluating the impact of discounts on sales and profits.


-Interactive Filters (Slicers): Users can filter data based on key metrics like discounts, net sales, and profit per order, providing a customizable view of performance.


-City-wise Sales Analysis: Shows sales distribution across different cities, helping the company focus on high-profit areas while strategizing for cities with low or negative profits.


These insights allow businesses to optimize pricing, target profitable markets, and enhance overall sales performance.
### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Since by default, profile will be opened only for 1000 rows so we need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present .
- Step 5: One card visual was added to show to the total number of orders placed.
- Step 6- Using visual level filter from the filters pane, the top and bottom 5 sales/profit/quantity sold values calculated.
- Step 7-First Approach -Providing two different date slicers - Date filter1 and Date filter 2 for the user to choose between the dates for the categories - “Sales “ , “Profit “ and “Quantity Sold”.
- Step 8 : Creating new measures  using DAX since the relationship between Date filter 2 and  Fact Table is inactive.
- Step 9 : Second Approach - Using Edit Interactions to compare Profit/Sales/Quantity sold between any 2 periods selected by the user.
- Step 10- Creating a table visual to show all the remaining fields for each order that could be filtered using visual filters along with a new measure to make the slicers interact among themselves.
- Step 11- Publishing the report to Power BI Service.
