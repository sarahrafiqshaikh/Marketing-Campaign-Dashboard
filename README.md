# Marketing Campaign Data Analysis and Dashboard

This project involves analyzing and visualizing the marketing campaign dataset to gain insights into customer demographics, spending habits, engagement, and campaign responses using Power BI.

## Dataset

The dataset contains the following features:
- Customer ID (`ID`)
- Age (`Age`)
- Education level (`Education`)
- Marital status (`Marital_Status`)
- Income (`Income`)
- Spending on various products (`MntWines`, `MntFruits`, `MntMeatProducts`, `MntFishProducts`, `MntSweetProducts`, `MntGoldProds`)
- Number of purchases by channel (`NumDealsPurchases`, `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases`)
- Campaign responses (`AcceptedCmp1`, `AcceptedCmp2`, `AcceptedCmp3`, `AcceptedCmp4`, `AcceptedCmp5`)

## Project Structure
- `Marketing_Campaign_Analysis.pbix`: Power BI file containing the full analysis and dashboard
- `README.md`: This file, providing an overview of the project
- `marketing_campaign.xlsx`: Dataset used for the project

## Requirements

- Power BI Desktop

## Usage

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Open `Marketing_Campaign_Analysis.pbix` in Power BI Desktop.
3. Interact with the dashboard to explore the data.

## Dashboard Visuals

1. **Slicers**:
   - **Marital Status Slicer**: Filter data by marital status.
   - **Education Slicer**: Filter data by education level.

2. **Demographic Analysis**:
   - **Age Distribution Histogram**: Visualizes the age distribution of customers.
   - **Education Levels Pie Chart**: Displays the distribution of education levels among customers.

3. **Customer Engagement**:
   - **Spending on Product Categories Stacked Column Chart**: Shows spending on different product categories.
   - **Number of Purchases by Channel Clustered Bar Chart**: Illustrates the number of purchases made through various channels.

4. **Campaign Responses**:
   - **Campaign Responses Clustered Column Chart**: Analyzes responses to different marketing campaigns.
   - **Marital Status Bar Chart**: Displays the distribution of marital statuses among customers.

## Data Cleaning Steps

1. **Handle Missing Values**:
   - Replace missing values in the `Income` column with the median value.
2. **Create New Columns**:
   - Calculate the `Age` column from the `Year_Birth` column if not already present.

## Author
Sarah Rafiq Shaikh
