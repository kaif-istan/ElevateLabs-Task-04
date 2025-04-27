# Power BI KPI Dashboard - Sales Analysis

## Project Overview
This project demonstrates how to create a Key Performance Indicator (KPI) Dashboard in Power BI using the "Superstore" dataset from Kaggle. The dashboard displays important metrics such as Total Sales, Total Orders, and Average Sales, providing insights into the business performance.

### Dataset:
The dataset used for this project is the "Sales Forecasting" dataset, available on Kaggle. It contains transaction-level data for sales, orders, and products from a Superstore.

You can download the dataset from the following link:
[Sales Forecasting Dataset on Kaggle](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)

## Steps for Dashboard Creation

### 1. Load the Dataset in Power BI
- Open Power BI Desktop.
- Load the "Superstore" dataset into the Power BI data model.

### 2. Create a Report View
- Click on the “Report” view icon (the page symbol) in the left panel.
- This is where the KPI dashboard will be built.

### 3. Create KPI Cards
KPI cards are used to display key metrics. Follow these steps to create each of the cards:

#### 3.1 Total Sales Card
- In the top ribbon, select the **Card** visualization from the Visualizations pane.
- Drag **Sales** into the **Values** area.
- The card will now display the sum of sales.
- Go to the **Format** pane, turn on **Data label**, and add a title: "Total Sales".
- Format the numbers (e.g., currency style) under **Data label**.

#### 3.2 Total Orders Card
- Copy the "Total Sales" card (Ctrl + C, then Ctrl + V).
- In the **Fields** pane, drag **Order ID** into the **Values** area.
- Click the dropdown next to **Order ID** and select **Count (Distinct)**.
- Update the title to "Total Orders".

#### 3.3 Average Sales Card
- Copy the "Total Sales" card again.
- Replace the **Sales** field with **Sales** again.
- Click the dropdown next to **Sales** and select **Average**.
- Update the title to "Average Sales".

### 4. Align and Style the Cards
- Arrange the three KPI cards side by side on the canvas.
- Ensure that the cards use the same font style, size, and color for consistency.
- Optionally, add borders, shadows, or background colors to enhance the design.

## Conclusion
This project provides a simple yet effective way to visualize key sales metrics in Power BI. The dashboard allows users to track Total Sales, Total Orders, and Average Sales, offering valuable insights into the business performance at a glance.

## Requirements:
- Power BI Desktop
- "Sales Forecasting" dataset from Kaggle

## Acknowledgements:
- [Sales Forecasting Dataset on Kaggle](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)
