# ETL Process

Data transformation was performed using Power Query.

## Data Sources

- Orders.csv
- Customers.csv
- Products.csv
- Returns.csv

## Cleaning Steps

### Orders

- Removed cancelled orders
- Created Revenue column
- Verified data types

### Products

- Removed duplicate Product IDs
- Replaced missing MRP values
- Converted MRP to numeric datatype
- Standardized category names

### Customers

- Converted M/F into Male/Female
- Trimmed city names
- Standardized payment method values

### Final

After cleaning, all tables were loaded into Power BI for modeling.