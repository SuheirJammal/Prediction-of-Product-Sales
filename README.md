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
<img width="580" height="455" alt="Outlet_Location_Type" src="https://github.com/user-attachments/assets/a2a68be2-27df-4a81-8e12-6fd269e47a72" />

#### **Interpretation**
   - Tier 3: **highest number of outlets** ~3400 outlets
   - Tier 2: ~2800 outlets
   - Tier 1: **fewest number** of outlets ~2400 outlets
#### **Insights**
   - The highest number of outlets are in Tier 3 locations, which are likely highly populated areas
   - Fewer outlets are found in Tier 1 locations, possibly because they represent smaller towns.
   - The highest number of outlets doesn't always reflect higher sales performance.
     

     
### Outlet Location Type vs Outlet Sales
<img width="580" height="455" alt="Outlet_Location_Type_vs_Sales" src="https://github.com/user-attachments/assets/4751bb6a-12bc-4882-ac44-46a84871283f" />

#### **Interpretation**
  - Tier 2 avg sales: ~2,400 m
  - Tier 3 avg sales: ~2,250 m
  - Tier 1 avg sales: ~1,900 m
#### **Insights**
   - Although tier 3 location has the highest number of outlets, but tier 2 location appear to have the largest amount of average sales.



### Outlet Location and Establishment Year Type vs Outlet Sales
<img width="580" height="455" alt="Outlet_Establishment_Year_Location_Type_vs_Sales" src="https://github.com/user-attachments/assets/9a7a6d34-3365-48b7-be8d-b7407005c987" />

#### **Interpretation**
  - Tier 3: shows inconsistant sales performance across the years.
  - Tier 2: show moderate and stable sales across years 2002–2009.
  - Tier 1: have lower average sales compared to Tier 2 and Tier 3.
#### **Insights**
   - Older outlets (especially those established in 1985 and 1987) perform strongly, possibly due to brand reputation or established customer bases.
   - Tier 2 outlets outperform other tiers in terms of sales volume and sales stability.
   - Tier 1 outlets may be in less populated or lower-income areas, leading to lower overall sales.
### Question 1: which outlet location performs best in sales?
  ✔️ **Tier 2 outlets** clearly perform the best in sales
     - shows stable avg of sales across years, unlike tier 3, which achieve high sales but unstable results.
     

   

