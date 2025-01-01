# CSV Data Transformation and Modeling in Power BI

## Project Overview
This project demonstrates a small-scale workflow for:
1. Cleaning and transforming three CSV files: `sales2017_raw.csv`, `producthierarchy.csv`, and `store_cities.csv`.
2. Creating a data model in Power BI for insightful analysis.

## Features
- **Data Cleaning:** Handles missing values, removes duplicates, and standardizes columns.
- **Transformation:** Optimizes data for analysis using normalization and joins.
- **Data Modeling:** Constructs relationships between `sales`, `product`, and `store` tables for visualization in Power BI.
- **Insights:** Generates key metrics such as sales performance by product and store.


### Tools Used
- Microsoft Power BI
- Excel


## Data Description
### sales2017_raw.csv
- `order_id`: Unique identifier for orders.
- `product_id`: Identifier linking to the `producthierarchy` table.
- `store_id`: Identifier linking to the `store_cities` table.
- `order_date`: Primary order date.
- `order_date_2`: Secondary order date (alternative format).
- `sales`: Quantity sold.
- `revenue`: Revenue generated from sales.
- `stock`: Remaining stock.
- `price`: Unit price of the product.
- `promo_type_1`: First promotion type.
- `promo_bin_1`: Indicator for first promotion type.
- `promo_type_2`: Second promotion type.
- `promo_bin_2`: Indicator for second promotion type.
- `promo_discount_2`: Discount applied in the second promotion.
- `delivery_date_format1`: First delivery date format.
- `delivery_date_format2`: Second delivery date format.

### producthierarchy.csv
- `product_id`: Unique identifier for products.
- `product (brand)`: Name and brand of the product.
- `type`: Type of the product.
- `length x depth x width (in cm)`: Product dimensions.
- `category || sub_category`: Product category and subcategory.

### store_cities.csv
- `store_id`: Unique identifier for stores.
- `storetype_id`: Type of store.
- `store_size`: Size of the store.
- `city_id`: Identifier for the city.
- `state - state abr - city`: State, state abbreviation, and city information.
- `lat / long`: Latitude and longitude coordinates.

## Power BI Features
- Interactive visualizations of sales by product and store.
- Drill-down analysis of sales trends over time.
- Highlights for top-performing products and stores.

## Future Enhancements
- Add forecasting capabilities using historical sales data.
- Incorporate additional datasets for enriched analysis.
- Automate the data extraction and loading process.



Contributions are welcome! Please create an issue or submit a pull request for any enhancements or bug fixes.


This project is licensed under the [MIT License](LICENSE).


---

Feel free to customize the project with your specific details and insights!
