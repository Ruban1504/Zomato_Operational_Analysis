# Zomato Operational Analysis using Python

## Overview

This project focuses on analyzing **Zomato's operational efficiency** using **Python**. The analysis aims to uncover patterns related to **delivery time, traffic conditions, weather impact, and order volume**. The dataset consists of **37,617 records**, offering insights into factors influencing delivery time and efficiency

![Chat Preview](https://imgur.com/Q7LCxq2.png)


---

## Problem Statement

The objective of this project is to extract key insights such as:

1. **Delivery Time Trends**  
   - Analyzing average delivery time under different conditions.
2. **Impact of Weather & Traffic**  
   - Examining how weather and traffic density affect delivery time.
3. **Order Volume Analysis**  
   - Studying order trends based on time, city, and other attributes.
4. **Performance of Delivery Personnel**  
   - Evaluating the impact of ratings, vehicle condition, and multiple deliveries.

---

## Dataset

The dataset contains **37,617 entries** covering various operational and logistical details.

### **Key Fields in the Dataset**

## Dataset Description

| Data Field                    | Description                          | Data Type       |
|----------------------------------|--------------------------------------|----------------|
| index                           | Unique row index                    | int64          |
| order_id                        | Unique identifier for each order    | object         |
| delivery_person_id              | Unique identifier for delivery person | object      |
| delivery_person_age             | Age of the delivery person          | int64          |
| delivery_person_ratings         | Ratings given to the delivery person | float64       |
| restaurant_latitude             | Latitude of the restaurant location | float64        |
| restaurant_longitude            | Longitude of the restaurant location | float64       |
| delivery_location_latitude      | Latitude of the delivery location  | float64        |
| delivery_location_longitude     | Longitude of the delivery location | float64       |
| order_date                      | Date when the order was placed      | datetime64[ns] |
| time_orderd                     | Time when the order was placed      | datetime64[ns] |
| time_order_picked               | Time when the order was picked up   | datetime64[ns] |
| weather_conditions              | Weather conditions during delivery  | category       |
| road_traffic_density            | Traffic conditions during delivery  | category       |
| vehicle_condition               | Condition of the delivery vehicle   | int64          |
| type_of_order                   | Type of food order (e.g., meal, snack) | category  |
| type_of_vehicle                 | Type of vehicle used for delivery   | category       |
| multiple_deliveries             | Number of deliveries in one trip    | int64          |
| festival                        | Whether the order was during a festival | category  |
| city                            | City where the order was placed     | category       |
| time_taken (min)                | Time taken for delivery in minutes  | int64          |
| time_orderd_hour                | Hour of the day when order was placed | int32       |
| time_order_picked_hour          | Hour of the day when order was picked | int32       |
| order_year                      | Year of the order                   | int32          |
| order_month                     | Month of the order                  | int32          |
| order_day_name                  | Name of the weekday when the order was placed | object  |
| order_day_num                   | Day of the month when the order was placed | int32 |
| pickup_duration                 | Duration between order and pickup   | float64       |




---

## Project Workflow

1. **Data Preprocessing**
   - Imported dataset and handled missing values.
   - Converted categorical values into numerical form for analysis.
   - Created new time-based features for deeper insights.

2. **Exploratory Data Analysis (EDA)**
   - Visualized delivery time distribution.
   - Examined the relationship between traffic, weather, and delivery time.
   - Analyzed peak order times and order distribution by city.

3. **Feature Engineering**
   - Added new features like `pickup_duration` and `order_day_name`.
   - Created bins for delivery time categories (Fast, Normal, Delayed).

4. **Findings & Insights**
   - Documented key observations to help Zomato improve operations.

---

## Expected Insights

- **Festival Impact**: Delivery time increases significantly during festivals.
- **Weather Conditions**: Foggy and cloudy conditions result in slightly longer delivery times.
- **Traffic Influence**: High traffic density leads to increased delivery time.
- **Order Timing**: Peak order hours impact delivery efficiency.
- **Multiple Deliveries**: More deliveries in a single trip affect overall delivery time.

This analysis helps Zomato enhance operational efficiency, optimize delivery time, and improve customer satisfaction. 🚀

---

## Installation
 Clone the repository:
   ```bash
   git clone https://github.com/Ruban1504/Zomato_Operational_Analysis.git
   ```


