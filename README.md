# Hotel Occupancy Prediction

## Project Overview

This project predicts the daily occupancy rate of a hotel using historical hotel reservation data.

The project transforms reservation data into daily occupancy data, performs data analysis and feature engineering, and applies Machine Learning regression models to predict hotel occupancy.

## Dataset

The dataset contains 9,974 hotel reservation records and 32 columns.

The data includes information such as:

- Check-in Date
- Check-out Date
- Room Number
- Room Type
- Adults
- Children
- Total Nights
- Total Amount
- Payment Status
- Reservation Source
- Booking Date

## Target

The target variable is:

**Occupancy Rate (%)**

It is calculated using:

```text
Occupancy Rate = (Occupied Rooms / Total Rooms) × 100
