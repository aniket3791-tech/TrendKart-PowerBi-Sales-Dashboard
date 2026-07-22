# Data Model

The dashboard follows a Star Schema data model.

## Fact Table

- Orders

## Dimension Tables

- Customers
- Products
- Returns
- Calendar

## Relationships

A Calendar table was created and marked as the official Date Table to support time-intelligence calculations.

The model enables efficient filtering and DAX calculations across the report.