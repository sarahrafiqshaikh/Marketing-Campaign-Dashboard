# Marketing Campaign Data Analysis and Dashboard

This project involves analyzing and visualizing a marketing campaign dataset to gain insights into customer demographics, spending habits, engagement, and campaign responses using Power BI.

## Dataset

The dataset contains the following features:

- **Customer ID (ID)**
- **Age (Age)**
- **Education level (Education)**
- **Marital status (Marital_Status)**
- **Income (Income)**
- **Spending on various products:** 
  - MntWines
  - MntFruits
  - MntMeatProducts
  - MntFishProducts
  - MntSweetProducts
  - MntGoldProds
- **Number of purchases by channel:** 
  - NumDealsPurchases
  - NumWebPurchases
  - NumCatalogPurchases
  - NumStorePurchases
- **Campaign responses:** 
  - AcceptedCmp1
  - AcceptedCmp2
  - AcceptedCmp3
  - AcceptedCmp4
  - AcceptedCmp5

## Project Structure

- **Marketing_Campaign_Dashboard.pbix:** Power BI file containing the full analysis and dashboard.
- **README.md:** This file, providing an overview of the project.
- **marketing_campaign.xlsx:** Dataset used for the project.

## Requirements

- Power BI Desktop

## Usage

1. Download and install Power BI Desktop.
2. Open `Marketing_Campaign_Dashboard.pbix` in Power BI Desktop.
3. Interact with the dashboard to explore the data.

## Dashboard Visuals

### Slicers

- **Marital Status Slicer:** Filter data by marital status.
- **Education Slicer:** Filter data by education level.
- **Income Slicer:** Filter data by income range.
- **Age Group Slicer:** Filter data by different age groups.

### Demographic Analysis

- **Age Distribution Pie Chart:** Visualizes the age distribution of customers across different age groups.
- **Education Levels Pie Chart:** Displays the distribution of education levels among customers.
- **Marital Status Bar Chart:** Shows the distribution of marital statuses among customers.

### Customer Engagement

- **Spending on Product Categories Stacked Column Chart:** Shows spending on different product categories (Wines, Fruits, Meat Products, etc.).
- **Number of Purchases by Channel Clustered Bar Chart:** Illustrates the number of purchases made through various channels (Web, Catalog, Store, etc.).

### Campaign Responses

- **Campaign Responses Clustered Column Chart:** Analyzes responses to different marketing campaigns.
- **Campaign Response Rates Gauge Chart:** Displays overall customer engagement with marketing campaigns.

### Additional Visualizations

- **Customer Segmentation by Age Group and Total Spending Stacked Bar Chart:** Segments customers by age groups and shows their total spending on different product categories.
- **Correlation between Income and Total Spending Scatter Chart:** Analyzes the relationship between customer income and their spending habits.
- **Customer Enrollment Over Time Line Chart:** Shows the trend of customer enrollment over time.

## Data Cleaning Steps

1. **Handle Missing Values:**
   - Replaced missing values in the Income column with the median value.

2. **Create New Columns:**
   - Calculated the Age column from the Year_Birth column.
   - Created an Age Group column to categorize customers into different age groups.

## Author
Sarah Rafiq Shaikh
