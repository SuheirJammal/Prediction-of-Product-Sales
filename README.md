# Prediction-of-Product-Sales
- This project will be a sales prediction for food items sold at various stores. The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.

## Data Source
- Sales prediction [Data Link](https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view)

## Data Dictionary
<img width="796" height="630" alt="Data-Dictionary-Product-Sales" src="https://github.com/user-attachments/assets/b739f43a-107f-4125-9b39-a6e680fc6f4f" />

## Technologies Used
- **Google Colab** – for code execution and experimentation in a cloud-based environment  
- **Python (Pandas Library)** – for data cleaning, manipulation, and analysis  
- **Seaborn & Matplotlib** – for data visualization and insight generation

## Dataset Size
- Number of columns: 12
- Number of rows: 607

## Data Cleaning
- Converted data types of incompatible columns
- Renamed ambiguoius columns' names
- Dropped high cardinality columns or columns with unique identifiers
- handled inconsistant columns' values
- Identified missing values
- dropped duplicated rows

## Exploratory Data Analysis
- Conducted visualizations for all numerical and categorical features and explored feature relationships using different graph types.
- In this analysis, I focused on answering specific questions?
- Which outlet Location type perform the best in Sales?
- Does opening new outlets increase the sales?
  
### Outlet Location Type
<img width="590" height="390" alt="location_type" src="https://github.com/user-attachments/assets/3c5cfc1a-2f7a-4e79-8d6d-a4e54bc8e817" />

  - Tier 3: 3800 outlets
  - Tier 2: 2700 outlets
  - Tier 1: 2400 outlets
  - Insights: Tier 3 dominates our dataset with 3800 outlet counts, which might indicate that tier3 is the best performing location type
  
### <img width="580" height="438" alt="location_type_vs_sales" src="https://github.com/user-attachments/assets/77777986-dd70-488a-86ad-3ddd22508911" />

- Tier 2 avg sales: 2400 thousands
- Tier 3 avg sales: 2250 thousands
- Tier 1 avg sales: 1900 thousands
- Insights: although tier 3 is dominant of our dataset, but this graph shows that location tier 2 achieves the highest average sales

