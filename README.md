# E-Commerce Data Analysis Project for Target

## Overview

This project involves analyzing e-commerce data from a Brazilian marketplace to gain insights into various aspects of customer behavior, sales trends, delivery efficiency, and payment methods. The analysis spans multiple years and covers:

- Order trends over time
- Delivery efficiency across different states
- Economic impact through order values and freight costs
- Payment method usage patterns

## Data Sources

The analysis utilizes the following datasets:

- **Customers**: Contains details such as customer ID, city, and state.
- **Orders**: Information on orders placed, including timestamps, purchase data, and delivery details.
- **Order Items**: Data related to specific items within each order.
- **Payments**: Contains payment details including payment type, value, and installments.
- **Geolocation**: Provides geographic information associated with customer locations.

## Key Analyses

### 1. Exploratory Data Analysis
   - **Data Structure & Characteristics**: 
     - Examined the data types and time ranges.
   - **Customer Distribution**: 
     - Analyzed the distribution of customers across cities and states.
   - **Order Trends**:
     - Identified trends in order volumes over time.

### 2. Order Trends
   - **Year-Over-Year Growth**: 
     - Investigated the growth in the number of orders placed from 2016 to 2017.
   - **Monthly Seasonality**: 
     - Analyzed patterns in order placements throughout the year.
   - **Time of Day Analysis**: 
     - Determined peak times during the day for order placements.

### 3. E-commerce Evolution
   - **Month-on-Month Order Volumes**:
     - Analyzed the volume of orders placed each month across different states.
   - **Customer Distribution**:
     - Studied how customers are distributed across states.

### 4. Economic Impact
   - **Order Cost Analysis**:
     - Calculated the percentage increase in order costs from 2017 to 2018.
   - **Order Prices and Freight Costs**:
     - Analyzed total and average order prices and freight costs by state.

### 5. Sales, Freight, and Delivery Time Analysis
   - **Delivery Time Evaluation**:
     - Evaluated the time taken to deliver orders and the difference between estimated and actual delivery times.
   - **Freight Value Analysis**:
     - Identified states with the highest and lowest average freight values.
   - **Delivery Efficiency**:
     - Determined states with the fastest delivery times relative to estimates.

### 6. Payments Analysis
   - **Payment Method Usage**:
     - Examined the month-on-month usage of different payment types.
   - **Installment-Based Orders**:
     - Analyzed the number of orders based on payment installment types.

## Insights

- **Order Trends**: Significant growth in order placements was observed from 2016 to 2017, with notable peaks in July 2017.
- **Time of Orders**: Most orders were placed in the afternoon, with the lowest during dawn.
- **State-Wise Analysis**: SP had the highest customer and order counts, while RR had the highest freight values.
- **Delivery Efficiency**: States like CE and RS exhibited faster delivery times compared to others.
- **Payment Trends**: Credit cards were the most commonly used payment method, particularly in October.

## Usage

To reproduce the analysis:

1. **Load Data**: Import the datasets as described in the key analyses.
2. **Run Queries**: Execute the provided SQL queries to generate insights.
3. **Analyze Results**: Review the insights derived from the data to inform business decisions or further research.

## Dependencies

- SQL-based querying for data analysis.
- Basic understanding of data structures and statistical analysis.
