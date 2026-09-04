# Smart-Inventory-Tracker
# Smart Inventory Tracker

An AI-assisted inventory management solution built with Microsoft Excel that helps organizations monitor stock levels, track inventory movements, identify low-stock items, and generate intelligent reorder recommendations.

This project demonstrates practical skills in inventory management, data analysis, spreadsheet automation, reporting, and business process optimization.

---

## Project Overview

Managing inventory manually can lead to stock shortages, excess inventory, and inaccurate reporting. The Smart Inventory Tracker provides a centralized solution for tracking inventory while automating key calculations and stock management processes.

The system enables users to:

* Monitor inventory levels in real time
* Record stock received and issued
* Identify low-stock items automatically
* Generate reorder recommendations
* Analyze inventory trends through dashboards
* Improve inventory visibility and decision-making

---

## Key Features

### Inventory Management

* Track all inventory items in a centralized spreadsheet
* Store product details, suppliers, quantities, and costs
* Monitor available stock levels

### Stock In Tracking

* Record incoming inventory
* Capture receiving dates and responsible personnel
* Maintain inventory history

### Stock Out Tracking

* Record inventory issued to users or departments
* Maintain stock movement records
* Improve inventory accountability

### Low Stock Alerts

Automatically identifies items that have reached or fallen below minimum stock levels.

Example formula:

```excel
=IF(D2<=E2,"REORDER REQUIRED","STOCK OK")
```

### AI-Assisted Reorder Recommendations

Provides intelligent reorder suggestions based on current stock levels and minimum stock thresholds.

Example formula:

```excel
=IF(D2<E2,"Order "&(E2*2-D2)&" Units","No Action")
```

### Dashboard Reporting

Interactive dashboard displaying:

* Total Products
* Total Inventory Value
* Low Stock Items
* Inventory Trends
* Inventory Movement Analytics

---

## Technologies Used

* Microsoft Excel
* CSV Data Files
* Excel Formulas
* Data Analysis
* Inventory Management Principles
* Business Reporting

---

## Project Structure

```text
Smart-Inventory-Tracker/
│
├── README.md
├── Inventory_Tracker.xlsx
├── Sample_Data.csv
├── Dashboard_Screenshot.png
├── LICENSE
│
└── Documentation/
    ├── User_Guide.md
    └── Technical_Overview.md
```

---

## Sample Inventory Data

| Item ID | Product Name | Category    | Quantity | Min Stock | Unit Cost | Supplier |
| ------- | ------------ | ----------- | -------- | --------- | --------- | -------- |
| IT001   | Laptop       | Hardware    | 25       | 10        | 12000     | Dell     |
| IT002   | Mouse        | Accessories | 100      | 30        | 150       | Logitech |
| IT003   | Keyboard     | Accessories | 80       | 20        | 350       | Logitech |
| IT004   | Monitor      | Hardware    | 15       | 10        | 2500      | Samsung  |

---

## Skills Demonstrated

This project showcases:

* Inventory Management
* Data Analysis
* Business Process Automation
* Spreadsheet Development
* Reporting & Dashboard Design
* Problem Solving
* Documentation
* Data Validation
* Stock Control

---

## Business Value

Organizations can use this solution to:

* Reduce stock shortages
* Improve inventory visibility
* Enhance reporting accuracy
* Support purchasing decisions
* Streamline inventory operations
* Improve operational efficiency

---

## Future Enhancements

Planned improvements include:

* Power BI Dashboard Integration
* Python-Based Inventory Analytics
* Automated Email Alerts
* Barcode Scanning Support
* Inventory Forecasting Models
* SQL Database Integration
* Web-Based Inventory Portal

---

## Documentation

Detailed documentation is available in:

* User_Guide.md
* Technical_Overview.md

---

## Author

**Sibusiso Maseko**

Aspiring Software Developer | IT Support Specialist | Data & Business Solutions Enthusiast

South Africa

GitHub: https://github.com/S-dev-hu

---

## License

This project is licensed under the MIT License.

