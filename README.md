# Hotel Booking Cancellation & Revenue Analysis

## Overview
Analysis of 119,388 hotel booking records to identify 
cancellation patterns and revenue risk, culminating in 
a predictive model and interactive Tableau dashboard.

## Key Findings
- Overall cancellation rate: 37% (City Hotel: 41.7%, 
  Resort Hotel: 27.8%)
- Bookings made 365+ days in advance cancel at 67.7% 
  vs 11% for same-week bookings
- Non-refundable deposits paradoxically show 99.4% 
  cancellation rate
- August represents peak revenue at risk despite being 
  highest-grossing month
- Direct bookings cancel at only 15.3% vs 61.1% for groups

## Predictive Model
- **Algorithm:** Random Forest Classifier
- **Accuracy:** 85.5%
- **Top predictors:** Lead time (22.7%), ADR (17.9%), 
  Deposit type (15.3%)

## Tools Used
- Python (pandas, matplotlib, seaborn, scikit-learn)
- Tableau Public
- Google Colab

## Data Source
[Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

## Dashboard
[View Interactive Tableau Dashboard](WIP) 

## Methodology Note
Revenue at risk is estimated as ADR multiplied by planned 
stay duration for cancelled bookings. Actual revenue loss 
may be lower due to rebooking and deposit retention policies.
