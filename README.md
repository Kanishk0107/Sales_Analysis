# Sales Data Analysis

This project analyzes a sales dataset containing customer information, product details, and transaction records to derive actionable insights for strategic decision-making. Using Python's data analysis libraries (NumPy, Pandas, Matplotlib, and Seaborn), we explore patterns and relationships to enhance customer understanding and improve business outcomes.

## Dataset Overview

The dataset includes:
- **User ID**: Unique customer identifier
- **Cust Name**: Customer's name
- **Product ID**: Unique product identifier
- **Gender**: Customer's gender
- **Age Group & Age**: Age and age group category
- **Marital Status**: Customer's marital status
- **State**: Customer's state of residence
- **Zone**: Customer’s geographical zone
- **Occupation**: Customer's occupation
- **Product Category**: Category of purchased product
- **Orders**: Number of orders placed by the customer
- **Amount**: Total value of customer orders

### Objective
The analysis aims to:
- Segment customers
- Evaluate product performance
- Analyze demographic trends
- Identify factors influencing purchasing behavior

## Libraries Used
- **NumPy**: Efficient array manipulation
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical graphics

## Data Preparation
We clean and preprocess the data to ensure accuracy, including:
- **Missing Values**: Removed or imputed missing data
- **Duplicates**: Removed duplicate records
- **Inconsistency Resolution**: Standardized categorical fields (e.g., state, zone)
- **Data Type Conversion**: Converted relevant fields to numerical types
- **Outlier Handling**: Managed outliers using techniques like winsorization
- **Feature Engineering**: Created new or derived features for better analysis

## Exploratory Data Analysis (EDA)
Our EDA investigates:
- **Gender**: Customer distribution by gender and purchasing trends
- **Age**: Age distribution and influence on spending patterns
- **State**: Regional variations in sales
- **Marital Status**: Relationship between marital status and purchasing behavior
- **Occupation**: Differences in purchasing behavior across occupations
- **Product Category**: Popular and underperforming product categories
- **Product ID**: Insights at the individual product level

## Key Insights
- **Target Customer**: Married women aged 26-35
- **Location**: Concentrated in Uttar Pradesh, Maharashtra, and Karnataka
- **Occupation**: Higher purchasing tendency among IT, healthcare, and aviation professionals
- **Preferred Categories**: Food, clothing, and electronics

### Conclusion
Our analysis highlights a key customer segment, their preferences, and potential areas for targeted marketing and product optimization. Businesses can leverage these insights to improve customer targeting, enhance inventory management, and optimize marketing strategies.

## Setup & Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sales-data-analysis.git
