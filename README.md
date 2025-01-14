# instacart-eda-case-study
Instacart EDA Project
This repository contains the exploratory data analysis (EDA) project for Instacart's grocery delivery data. The project involves cleaning and analyzing data to uncover customer shopping patterns and trends.

## Project Objective
The goal of this project is to analyze modified Instacart data to gain insights into customer shopping habits. The dataset, originally released during a Kaggle competition, has been adapted with missing and duplicate values to simulate real-world challenges.

## Data Description

The project uses the following datasets:

instacart_orders.csv
Details customer orders, including the day and time of orders and the time since the last order.

products.csv
Provides details about products, including their IDs, names, aisles, and departments.

order_products.csv
Links products to their respective orders, detailing the sequence and reorder status.

aisles.csv
Contains aisle categories for products.

departments.csv
Contains department categories for products.

## Key Tasks

Data Preprocessing

Handle missing values.
Remove duplicate entries.
Verify and correct data types.
Exploratory Data Analysis

Analyze shopping behaviors by day and hour.
Explore customer ordering patterns.
Identify popular and frequently reordered products.
Visualizations

Create plots to display trends and distributions, ensuring they are clear and well-labeled.

## Notebooks
EDA_final_project_template.ipynb

Contains the analysis, code, and visualizations for the project. Each step includes markdown explanations for clarity.

## How to Use

1. Clone the repository:
   
   git clone https://github.com/yourusername/instacart-eda-project.git

3. Open the Jupyter Notebook
   
     jupyter notebook EDA_final_project_template.ipynb

5. Follow the steps outlined in the notebook to understand the analysis and results.

## Key Insights

The time and day customers typically place orders.
Products with the highest reorder rates.
Patterns in the number of items customers add to their carts.
Feedback and Revisions
The project has undergone a thorough review process, ensuring clarity and quality. Reviewer comments are included in the notebook for reference.
