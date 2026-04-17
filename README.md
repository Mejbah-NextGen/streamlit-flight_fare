# ✈️ Airline Price Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on an airline ticket pricing dataset.
The goal is to understand patterns, trends, and relationships in the data before applying preprocessing and machine learning models.

## 📊 Dataset Description

The dataset contains **300,153 records** with the following features:

| Column Name      | Description                                |
| ---------------- | ------------------------------------------ |
| airline          | Name of the airline company                |
| flight           | Flight code                                |
| source_city      | Departure city                             |
| departure_time   | Time of departure                          |
| stops            | Number of stops (non-stop, one-stop, etc.) |
| arrival_time     | Arrival time                               |
| destination_city | Destination city                           |
| class            | Travel class (Economy/Business)            |
| duration         | Flight duration (in hours)                 |
| days_left        | Days remaining before departure            |
| price            | Ticket price                               |

## 🎯 Objectives

- Perform **data exploration and visualization**
- Identify:
  - Price distribution
  - Relationship between features and price
  - Trends based on time, class, and airline
- Detect:
  - Outliers
  - Patterns in duration and pricing
- Prepare insights for:
  - Feature engineering
  - Model building

## 📈 Visualizations Performed

- 📊 Airline Distribution (Bar Chart)
- 🎫 Class Distribution (Economy vs Business)
- ✈️ Airline vs Price (Boxplot / Bar Chart)
- 💼 Class vs Price (Price comparison by travel class)
- 🛑 Stops (Transit) vs Price (Impact of stops on pricing)
- 🌅 Departure Time vs Price (Time-based price variation)
- 🌇 Arrival Time vs Price (Arrival time impact on price)
- 🌆 Source City vs Price (Departure city pricing trends)
- 🏙️ Destination City vs Price (Destination-based price variation)
- ⏱️ Duration vs Price (Flight duration vs ticket cost)
- 📅 Days Left vs Price (Trend of price vs remaining days)

## 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📌 Key Insights

- Ticket prices increase as **days_left decreases**
- **Business class** is significantly more expensive than economy
- Flights with **more stops** tend to be cheaper
- Certain airlines consistently have higher pricing
