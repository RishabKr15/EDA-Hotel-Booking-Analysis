# EDA-Hotel-Booking-Analysis
![eda](https://github.com/user-attachments/assets/79632a58-7b55-4f4a-b99b-d4bcc6452186)
## Hotel Booking Data Analysis

This project revolves around analyzing booking data for a city hotel and a resort hotel to gain insights into various factors affecting bookings. The dataset contains information such as booking dates, length of stay, number of guests, and availability of parking spaces, among other details. Here's a comprehensive description of the project:

## Business Objective:

Analyze booking data for City Hotel and Resort Hotel to gain insights into factors influencing bookings.
Dataset Overview:

Contains 119,390 rows and 32 columns.
Includes information on hotel type (City Hotel or Resort Hotel), cancellation status, lead time, arrival date, length of stay, and more.
All personally identifying information has been removed from the data.
Data Manipulation Workflow:

## Data Collection:

Used methods like head(), tail(), info(), describe(), and columns() to explore the dataset.
Identified columns like hotel, is_canceled, lead_time, arrival_date, and stays_in_weekend_nights.

## Data Cleaning and Manipulation:

Checked for and removed duplicate data items (31994 duplicates found).
Checked for and handled null values, dropping the 'company' column with a large number of nulls and filling minimal null values using .fillna().

## Exploratory Data Analysis (EDA):

Utilized various charts and graphs for data visualization to gain insights and achieve the business objective.
Explored factors such as booking trends over time, cancellation rates, length of stay, and special requests.

## Key Visualizations:

Time series analysis of booking trends over different months and years.
Cancellation rates analysis for City Hotel and Resort Hotel.
Distribution of length of stay for both hotel types.
Analysis of special requests and their correlation with other factors.
This comprehensive analysis of hotel booking data provides valuable insights for optimizing booking strategies and improving customer satisfaction.
