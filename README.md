# **[Inventory-Dashboard](url)**
## **Introduction**
This is an analysis of the Inventory of a manufacturer. 

This is a project that shows my ability to: 
- Use Power Query Editor to shape data of a database about the current inventory of a manufacturer.
- Use Power BI for analyzing and visualizing metrics: Distribution of YTD Revenue, Current Stock Value, and Inventory Turnover by ABC & XYZ classification; ABC Pareto Chart; Safety Stock & Reorder Points.
## **Business Request & User Stories**
The business request for this data analyst project was an inventory dashboard for Supply Chain managers. Based on the request from the business we following user stories were defined to fulfill delivery and ensure that acceptance criteria were maintained throughout the project.
<img width="875" alt="image" src="https://github.com/YenDo123123/Inventory-Dashboard/assets/140786495/42631269-1c4d-4056-af87-c1776ed8b116">

## **Skills and Concepts demonstrated**
- Microsoft Power BI
  - Shaping data before the data analysis using Power Query Editor.
  - Data modeling
  - Performing DAX functions to calculate columns and measures in row and filter contexts for solving mathematical formulas.
  - Performing DAX's date and time intelligence functions and quick measures to create complex DAX code. 
  - Showing the information in the dashboard selectively with a Filter pane.
  - Data Visualization with proper charts.
 
##  **The Inventory Power BI Dashboard**

<img width="596" alt="image" src="https://github.com/YenDo123123/Inventory-Dashboard/assets/140786495/82e3b5f9-8f45-4798-b0af-8b60bed716ee">

## **Analysis**
- The Inventory Turnover Ratio of 2.61 shows that selling its inventory at a good rate and that it is managing its inventory efficiently. However, the company needs to compare it with the previous result and industry benchmark.
- Currently, 252 SKUS out of 303 SKUs need to be ordered. In particular, 3.3% of SKUs are out of stock and 13.86% of SKUs are below reorder point.
- Pareto principle for inventory which is an 80/20 rule that states that 80% of profit should come from 20% of the inventory. 
- In terms of 9 groups by ABC XYZ Analysis, below are the characteristics of each group in ABC XYZ Analysis:

<img width="596" alt="image" src="https://github.com/YenDo123123/Inventory-Dashboard/assets/140786495/264b4dde-79e4-4bef-8118-a39c1ab74c2e">

- We can see that:
  - Currently, most of the revenue of the company comes from AX and AY groups. It seems that the company's inventory policy work well. 
  - The stock value of groups BZ and CZ are far higher than that of others. Companies should reduce them to reduce the risk of obsolete and inventory costs. 
  - The Inventory Turnover Ratio of the AX group is the highest, and those of the BY, BZ, CA, CB, and CZ groups are lower than average. It illustrates a good sign for sales. 

- Besides that, below inventory policies should be considered to be applied to each group. Inventory policies may include:
  - Degree of automation and timing of replenishment processes (red text).
  - Mutually agreed upon inventory parameters for ABC items (blue text).
  - Inventory control, such as cycle counting frequencies (green text).

<img width="596" alt="image" src="https://github.com/YenDo123123/Inventory-Dashboard/assets/140786495/f6086544-179d-4816-8fc8-049333c1a8bd">

- Overall, following up and adhering to the Safety Stocks and Reorder points are necessary to meet up unexpected demands or supply disruptions. On-time production should be increased and regular inventory audits be carried out to ensure optimum inventory levels and reduced risk of overstocking or stockouts.
