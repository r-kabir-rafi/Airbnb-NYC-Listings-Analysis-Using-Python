# Airbnb-NYC-Listings-Analysis-Using-Python

#  NYC Airbnb Listings - Exploratory Data Analysis with Python 

## Project Summary

This project explores the Airbnb listings dataset for New York City to uncover patterns in prices, availability, room types, and host behavior. The goal is to provide data-driven insights for guests, hosts, and stakeholders in the short-term rental market.

https://github.com/r-kabir-rafi/Airbnb-NYC-Listings-Analysis-Using-Python/issues/1#issue-3165655663
---

## Objectives

- Analyze room types, pricing, and availability across NYC neighborhoods
- Identify price outliers and unusual listing behavior
- Understand host trends (e.g. multi-listing hosts)
- Visualize key trends using Python data libraries
- Provide recommendations for guests and hosts

---

## Dataset

- **Source:** Inside Airbnb NYC (2024 version)
- **Entries:** 20,765
- **Columns:** 22 (ID, price, location, room type, host name, reviews, etc.)

Key fields used:
- `price`, `neighbourhood_group`, `room_type`, `availability_365`, `number_of_reviews`, `reviews_per_month`, `latitude`, `longitude`

---

## Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Preprocessing

- Handled missing values in key columns
- Converted `last_review` to datetime
- Filtered extreme outliers (`price > $1000`)
- Cleaned and prepared data for visualization

---

## Key Explorations

- **Room Types:** Entire homes dominate, but private rooms are more budget-friendly  
- **Neighborhood Trends:** Manhattan has the highest average prices  
- **Availability:** Listings with more availability are often cheaper and better reviewed  
- **Host Behavior:** Identified professional hosts with multiple listings  
- **Outliers:** Found and removed listings with prices exceeding $10,000

---

## Visualizations

- Bar charts: Room types and neighborhood group distributions
- Histograms & Boxplots: Price distribution and outliers
- Heatmaps: Correlations among key numerical features
- Pairplots: Price, reviews, and availability relationships

---

## Insights & Recommendations

**For Guests:**
- Private rooms in Brooklyn offer good value
- Listings with high availability and strong review history are more reliable

**For Hosts:**
- Improve response rates and availability to boost bookings
- Stay competitive by monitoring price trends in your borough

---

### 1. Clone the repository
```bash
git clone https://github.com/najirh/Python-Project-P2-New-York-AirBnb-Listing-2024.git
cd Python-Project-P2-New-York-AirBnb-Listing-2024
