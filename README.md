# Mobile Data Exploratory Data Analysis

This repository contains Python code for performing exploratory data analysis (EDA) on a dataset of mobile phone information. The EDA covers data cleaning, visualization, and correlation analysis.

## Libraries Used

The following Python libraries were used in the analysis:

- pandas
- numpy
- matplotlib
- seaborn
- plotly.express

## Dataset

The dataset used in this analysis is available from the following URL:
[Mobile Phone Dataset](https://raw.githubusercontent.com/ASatya-J107/Data_Science_Project_1_Exploratory_Data_Analysis/main/Mobile_phone_price.csv)

## Data Cleaning

- Renamed columns 'Storage ' and 'RAM ' to 'Storage (GB)' and 'RAM (GB)' respectively.
- Removed duplicate rows from the dataset.
- Formatted the 'Price ($)' column to remove currency symbols and commas.

## Data Visualization

1. **Distribution of Mobile Brands:**
   - A bar chart depicting the distribution of mobile brands in the dataset.

2. **Price Distribution Across Brands:**
   - A boxplot showing the distribution of mobile phone prices across different brands.

3. **Distribution of Storage (GB):**
   - A histogram displaying the distribution of storage capacities in gigabytes.

4. **Distribution of RAM (GB):**
   - A bar chart illustrating the distribution of RAM capacities in gigabytes.

5. **Relationship Between RAM (GB) and Storage (GB):**
   - A scatter plot showcasing the relationship between RAM and storage capacities.

6. **Relationship Between RAM (GB) and Price ($):**
   - A scatter plot demonstrating the relationship between RAM capacity and mobile phone prices.

7. **Relationship Between Storage (GB) and Price ($):**
   - A scatter plot depicting the relationship between storage capacity and mobile phone prices.

8. **Battery Capacity (mAh) vs. Price ($):**
   - A scatter plot showing the relationship between battery capacity and mobile phone prices.

9. **Screen Size (inches) vs. Price ($):**
   - A scatter plot illustrating the relationship between screen size and mobile phone prices.

10. **Main Camera MP vs. Price ($):**
    - A scatter plot displaying the relationship between the main camera resolution and mobile phone prices.

11. **Number of Cameras vs. Price ($):**
    - A violin plot presenting the relationship between the number of cameras and mobile phone prices.
