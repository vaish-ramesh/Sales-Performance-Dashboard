# 📊 Sales Dashboard

An interactive sales analytics dashboard built in Excel, visualizing revenue, profit, and order trends across products, categories, regions, and payment modes.

## Demo

https://github.com/vaish-ramesh/Sales-Performance-Dashboard/blob/main/Sales%20Dashboard.mp4

## Key Insights

- Electronics drives the highest revenue but Office Supplies has more consistent profit margins
- California and New York account for the majority of high-value orders
- COD is the most used payment method despite carrying the highest fulfilment risk
- Bulk orders (15+ units) don't always yield higher profit — margin drops significantly in the Furniture category
- Sales peak in Q4, with a noticeable dip in mid-year months

## Dataset

The dashboard is powered by a structured sales dataset (`Sales Dashboard.xlsx`) with the following fields:

| Field | Description |
|---|---|
| `Order ID` | Unique order identifier |
| `Revenue` | Total revenue per line item |
| `Profit` | Profit earned per line item |
| `Profit Margin %` | Calculated profit margin |
| `Quantity` | Units sold |
| `Category` | Product category (Electronics, Furniture, Office Supplies) |
| `Products` | Specific product (Laptops, Phones, Chairs, Pens, etc.) |
| `Payment Mode` | UPI, Credit Card, Debit Card, COD, EMI |
| `Order Date` | Date of the order |
| `Customer Name` | Customer name |
| `State / City` | Geographic location of the order |

## Features

- **Revenue & Profit Tracking** — monitor top-line revenue and profit side-by-side
- **Category Breakdown** — compare performance across Electronics, Furniture, and Office Supplies
- **Product-Level Analysis** — drill down into individual products (Laptops, Printers, Phones, Binders, etc.)
- **Geographic Insights** — sales distribution across US states and cities
- **Payment Mode Analysis** — understand customer payment preferences (UPI, COD, EMI, Credit/Debit Card)
- **Profit Margin Monitoring** — track margins at the order and product level

## Files

```
sales-dashboard/
├── Sales Dashboard.xlsx   # Excel workbook with data and dashboard
├── Sales Dashboard.mp4    # Demo walkthrough video
└── README.md
```

## Getting Started

1. Download `Sales Dashboard.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. Enable content/macros if prompted
4. Use the slicers and filters to explore the data

## Tech Stack

- **Microsoft Excel** — pivot tables, charts, slicers, and conditional formatting
