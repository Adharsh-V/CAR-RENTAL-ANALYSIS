# CAR-RENTAL-ANALYSIS
End-to-end data analytics project covering MySQL data cleaning, SQL analysis, and interactive Power BI dashboard for a car rental business dataset.

##  Project Overview

This project demonstrates a complete analytics pipeline — from raw CSV ingestion and data cleaning in MySQL to advanced SQL analysis and a fully interactive Power BI dashboard.

**Dataset**: 5 relational tables (Customers, Vehicles, Rentals, Payments, Makes) containing c rental transactions across 50 vehicles.

##  Dataset

 *`customer.csv` - Customer profiles with membership tiers (Bronze/Gold/Silver)
 
 *`Vehicles.csv` - Fleet of 50 vehicles with make, model, daily rates 
 
*`Rentals.csv` - Rental transactions with start/end dates and status 
  
*`makes.csv` - Brand-level metadata including image URLs 

* `payments.csv` - Payment records by method (Credit Card, PayPal, Bank Transfer, Cash)

##  Tech Stack
- **MySQL** — Data ingestion, cleaning, deduplication, joins
- **Power BI** — Interactive dashboard with slicers and KPI cards
- **Excel** — Source data formatting

##  SQL Analysis Performed
1. Top revenue-generating customer identification
2. Revenue contribution by membership status (%)
3. Month-wise revenue generation and growth rate
4. Payment method revenue split
5. Customers above average spend
6. Monthly revenue trend with lag-based comparison

##  Dashboard Highlights
- **KPIs**: Total Revenue (2M), Total Trips (1,000), Avg Profit/Trip (1.65K)
- **Most Revenue Car**: Audi Q7
- **Top Payment Method**: Credit Card (112K)
- **Peak Month**: June
- Filters by Membership Status & Date Range

##  Key Insights
- Audi Q7 generates the highest number of trips (32 trips)
- Audi brand leads revenue at 58K across all brands
- Silver membership contributes the most revenue (98K)
- Nissan Sunny has the highest daily rate; Ford Fiesta the lowest
- Credit card is the dominant payment channel

##  File Structure

* steps.sql  # Cleaning and SQL
* Car_Rental.xlsx    # Source Excel data
* customer.csv
* Vehicles.csv
* Rentals.csv
* payments.csv
* makes.csv
*2.pbix             # Power BI dashboard file
