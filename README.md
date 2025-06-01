# Supply Chain Performance Overview

## 🎯 Project Goal:
- Use dial gauges to create measures for start value, end value and target values in order to depict supply chain performance
- Use tooltips to provide additional insight without cluttering the main dashboard
- Using play axis to animate the impact of logistics cost on delivery efficiency


## 📁 Files Included
<a href="https://github.com/PyKrishanu/Supply-Chain-Overview/blob/main/Supply%20Chain%20Performance%20Overview%20PowerBI%20File.pbix">PBIX</a>
<a href="https://github.com/PyKrishanu/Supply-Chain-Overview/blob/main/Supply%20Chain%20Performance%20Overview_model_view.JPG">Model view</a>
<a href="https://www.kaggle.com/datasets/ziya07/bdt-mba-supply-chain-dataset"> Kaggle Dataset Link</a>

## 📊 𝐖𝐡𝐚𝐭 𝐢𝐭 𝐫𝐞𝐯𝐞𝐚𝐥𝐬:
- ✅ Region wise inventory condition score, resource utilization and delivery efficiency
- ✅ Identify the relationship between logistics cost vs. delivery efficiency 
- ✅ Highlight supply chain performance such as average downtime hours, logistics cost, inventory levels and supply chain efficiency

 ## 📊 Dashboard Preview
 <a href="https://github.com/PyKrishanu/Supply-Chain-Overview/blob/main/Supply%20Chain%20Performance%20Overview.JPG">Dashboard</a>

💡 Tools & Skills Used:
 Power Query for data cleaning and data wrangling
 DAX for creating date table, start value, end value, target values and formatting dates
 Create Dial gauges, tools tips, play axis in scatter plot and use of drill through
Organizing all the measures in respective folders in model view

 ## 🧪 Process Followed
 - Imported `bdt_mba_supplychain_dataset_2024.csv`containing relevant information on Location, Condition Score, Resource Utilization, Delivery Efficiency, Downtime Hours, Inventory Level, Logistics Cost and Supply Chain Efficiency Label.
 - Used **Power Query** to clean and standardize:
 - Created a Date Table and built hierarchy of Month Year 
 - Defined relationships between fact table and date table
 - Designed Power BI report with visuals like:
 - Dial Gauges, ArcGIS Map, Scatter Plot, Card, Line Chart, Ribbon Chart and slicer
 - Created measures for dial gauges such as start value, end value, actual start, actual end and target values
 - Formatted the dial gauges as per the assigned values
 - Created a separate page for tooltips and changed the page type to tooltips 
 
## ⚠️ Challenges Faced
- Creating and assigning the dial gauge values correctly

## ✅ Final Conclusion
The project provides an overview of supply chain metrics such as inventory condition score, resource utilization, delivery efficiency, average downtime and supply chain efficiency.
Future improvements may include providing supply chain performance based on excluded variables such as 'temperature' and 'vibration'. 
