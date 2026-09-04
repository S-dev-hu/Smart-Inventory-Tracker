# Smart-Inventory-Tracker
Smart-Inventory-Tracker
│
├── README.md
├── Inventory_Tracker.xlsx
├── Sample_Data.csv
├── Dashboard_Screenshot.png
├── LICENSE
│
└── Documentation
    ├── User_Guide.md
    └── Technical_Overview.md
    | Item ID | Product Name | Category | Quantity | Min Stock | Unit Cost | Supplier |
| ------- | ------------ | -------- | -------- | --------- | --------- | -------- |
| Date | Item ID | Product | Quantity Added | Received By |
| ---- | ------- | ------- | -------------- | ----------- |
| Date | Item ID | Product | Quantity Removed | Issued To |
| ---- | ------- | ------- | ---------------- | --------- |
Total Products
Total Stock Value
Low Stock Items
Charts
Inventory Trend
=IF(D2<=E2,"REORDER REQUIRED","STOCK OK")
=IF(D2<E2,"Order "&(E2*2-D2)&" Units","No Action")
Inventory_Tracker.xlsx
Item ID,Product Name,Category,Quantity,Min Stock,Unit Cost,Supplier
IT001,Laptop,Hardware,25,10,12000,Dell
IT002,Mouse,Accessories,100,30,150,Logitech
IT003,Keyboard,Accessories,80,20,350,Logitech
IT004,Monitor,Hardware,15,10,2500,Samsung
Sample_Data.csv
README.md
# Smart Inventory Tracker

## Overview

An AI-powered inventory management spreadsheet designed to help organizations track stock levels, monitor inventory movements, forecast demand, and generate intelligent reorder recommendations.

## Features

- Inventory Tracking
- Stock In / Stock Out Management
- Dashboard Reporting
- Low Stock Alerts
- AI Reorder Recommendations
- Demand Forecasting

## Technologies Used

- Microsoft Excel
- CSV
- Data Analysis
- AI-assisted Inventory Management

## Screenshots

Add dashboard screenshot here.

## Author

Sibusiso Maseko
Johannesburg, South Africa
User_Guide.md
# User Guide

## Adding Inventory

1. Open Inventory Master
2. Add a new item
3. Enter quantity and supplier details

## Recording Stock In

Open Stock In sheet and capture incoming stock.

## Recording Stock Out

Open Stock Out sheet and capture issued stock.

## Dashboard

Dashboard updates automatically.
Technical_Overview.md
# Technical Overview

The Smart Inventory Tracker uses Excel formulas to automate inventory calculations.

## AI Features

- Low stock detection
- Reorder recommendations
- Demand forecasting

## Formula Examples

```excel
=IF(D2<=E2,"REORDER REQUIRED","STOCK OK")
```

```excel
=FORECAST.LINEAR(...)
```
MIT License

Copyright (c) 2026 S-dev-hu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
