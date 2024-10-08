# Electric Vehicle Market Segmentation

### By Sakshi Singh - FeyNN Lab

## Problem Statement

With the global shift towards sustainable transportation, the electric vehicle (EV) market is experiencing rapid growth. However, the adoption of EVs remains uneven across different customer segments due to varying levels of awareness, financial capability, infrastructure availability, and environmental concerns. Manufacturers and marketers face the challenge of understanding the diverse needs and preferences of potential EV buyers. Without a clear market segmentation strategy, EV companies risk missing opportunities to effectively target and engage potential customers, hindering their ability to accelerate EV adoption and meet environmental and business goals.

The problem lies in identifying and segmenting the EV market based on key factors such as demographics, psychographics, income levels, geographic location, and consumer behaviors. This segmentation is essential to develop tailored marketing strategies, optimize product offerings, and ensure the right infrastructure is available to support different segments, ultimately driving broader EV adoption.

## A. Algorithm for Predicting Future Price Change with Respect to Time Dimension

### Target Segment: Price vs. Date Relation

- **Data Collection Source**: Kaggle dataset - `CAR DETAILS FROM CAR DEKHO.csv`

### Data Exploration

Feature extraction is a crucial step in data preparation, as it involves identifying and creating relevant variables (features) from raw data that will enhance the performance of the model or analysis. For EV market segmentation, extracting meaningful features can help accurately categorize customer segments and predict potential EV buyers. 

**Important features include**:
- Salary
- Price of car
- Fuel type
- Seller type
- Year or date

### Data Insights

Gathering basic information from the data provided to understand patterns and correlations.

### Algorithm Used: Random Forest

A Random Forest algorithm is implemented to predict the price changes based on the time dimension, leveraging the key features extracted from the dataset.

### Data Visualization

Data visualizations are created to represent the relationships between variables such as price, date, and other relevant features.

## B. Determining Salary, Gender, and Sales Correlation

- **Data Collection Source**: Kaggle dataset - Car sales data

### Data Exploration

Extracting and examining data features to understand the correlations between different variables.

**Feature Extraction**:
- ID
- Date
- Customer Name
- Gender
- Annual Income
- Company
- Dealer
- Model
- Engine
- Colour
- Transmission

### Data Visualization

Visualizing the relationships between features such as salary, gender, and sales to identify patterns and correlations.

### Insights

Applying a linear regression model to determine the optimum price range for a desired income group based on the data analysis.

## Conclusion

The analysis provides insights into the optimum price range for each income group, helping to develop effective marketing and product strategies for EV manufacturers. By targeting specific customer segments with tailored approaches, companies can better meet the demands of the market and drive EV adoption.

## GitHub Repository

Access the full project [here](https://github.com/Saakshi-Singh/ElectricVehicleMarketSegmentation).
