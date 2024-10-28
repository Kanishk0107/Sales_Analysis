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
![image](https://github.com/user-attachments/assets/bf4ee76b-4b9b-4cd4-9593-7dc4bd802fcb)


## Data Preparation
We clean and preprocess the data to ensure accuracy, including:
- **Missing Values**: Removed or imputed missing data
- **Duplicates**: Removed duplicate records
- **Inconsistency Resolution**: Standardized categorical fields (e.g., state, zone)
- **Data Type Conversion**: Converted relevant fields to numerical types
- **Outlier Handling**: Managed outliers using techniques like winsorization
- **Feature Engineering**: Created new or derived features for better analysis
![image](https://github.com/user-attachments/assets/d6b7da6d-c780-4dff-ac59-18d0211e5575)

## Exploratory Data Analysis (EDA)
Our EDA investigates:
- **Gender**: Customer distribution by gender and purchasing trends
![image](https://github.com/user-attachments/assets/cdc61455-c463-4cde-be3c-1d98c1c456cb)

- **Age**: Age distribution and influence on spending patterns
  ![image](https://github.com/user-attachments/assets/92fa076e-c135-4217-9d66-b4bde2c925f6)

- **State**: Regional variations in sales
  ![image](https://github.com/user-attachments/assets/4ea243e9-840c-4f2d-8bf8-f3c65ecc10d4)

- **Marital Status**: Relationship between marital status and purchasing behavior
  ![image](https://github.com/user-attachments/assets/08384be1-25d7-4d5d-a485-d88dedef7b9f)

- **Occupation**: Differences in purchasing behavior across occupations
  ![image](https://github.com/user-attachments/assets/078c6ada-1106-41b2-a0e8-73ca0bdab612)

- **Product Category**: Popular and underperforming product categories
  ![image](https://github.com/user-attachments/assets/353920cb-2511-4c8e-ad53-a325351c12b9)

- **Product ID**: Insights at the individual product level
  ![image](https://github.com/user-attachments/assets/9a5ec5ae-f419-4178-8415-152af16f55f6)


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
