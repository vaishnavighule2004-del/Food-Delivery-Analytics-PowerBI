# Food-Delivery-Analytics-PowerBI
Power BI project on the topic "Food Delivery Analysis" using PowerBI. 

# 🍔 Zomato Food Delivery Analytics Dashboard

![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-107C41?style=for-the-badge&logo=microsoftexcel&logoColor=white)

An end-to-end interactive Power BI dashboard designed to analyze and visualize global food delivery data. This project transforms raw, unstructured restaurant data into actionable operational insights regarding sales trends, geographical footprints, and customer preferences.

## 📊 Project Overview
The primary objective of this project was to clean, model, and visualize a massive dataset of over 9,500 global restaurants to uncover operational gaps in the food delivery market. 

**Key Business Insights Discovered:**
* **Delivery Gaps:** Over 74% of listed restaurants in the dataset do not offer online delivery, revealing a massive untapped market segment.
* **Geographical Density:** Mapped restaurant footprints across 15 countries and 141 distinct cities to analyze regional market saturation.
* **Customer Preferences:** Analyzed the direct correlation between specific cuisine types (e.g., North Indian, Fast Food) and average customer ratings.

## 🗂️ Repository Structure
This repository is organized to separate the raw data, visual assets, and presentation materials:

* **`DataSet/`** - Contains the cleaned raw data file (`restaurant_data_cl.xlsx`) used to power the dashboard.
* **`Dashboard Snippets/`** - High-resolution screenshots of the dynamic UI and active map visuals.
* **`Presentation/`** - The slide deck used to present the data architecture, DAX methodology, and business insights.
* **`Food_Delivery.pbix`** - The fully functional Power BI dashboard file.

## 🛠️ Architecture & Technologies Used
1. **Power Query (Data Pipeline):** Engineered the data ingestion process. Handled deduplication, treated null values, and standardized data types (e.g., reformatting text-based date keys into valid date hierarchies).
2. **Relational Data Modeling:** Architected a Star Schema within the Model View, establishing robust One-to-Many relationships between dimension tables (Countries) and fact tables (Restaurants).
3. **DAX & Aggregations:** Leveraged the VertiPaq engine and implicit measures for dynamic aggregations (distinct counts, averages) to optimize visual rendering and cross-filtering speed.
4. **Data Visualization:** Built an interactive frontend UI with dynamic slicers, clustered bar charts, and global map visuals using Power BI.

## 📷 Dashboard Preview
*(A live preview of the interactive dashboard)*
![Dashboard Preview](Dashboard%20Snippets/SS1.png)

## 👨‍💻 Contributors
* **Roshan** - Backend Architecture & Data Modeling
* **Vaishnavi** - Data Pipeline (Power Query) & Frontend UI
