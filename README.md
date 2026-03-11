# Airbnb Pricing Drivers Analysis

## Overview
This project analyzes Airbnb listings across five major U.S. cities — Boston, Los Angeles, Washington DC, San Francisco, and Seattle — to identify the key factors that drive higher nightly prices and occupancy.

The goal is to understand how listing features, host characteristics, and location influence pricing patterns across short-term rental markets.

---

## Research Questions
- Which listing features consistently drive higher Airbnb prices?
- Does **superhost status** increase listing prices?
- Which **room types** generate the highest revenue?
- How much does **location** influence pricing?

---

## Dataset
Airbnb listing datasets from five cities.

Key variables include:
- `room_type`
- `accommodates`
- `bathrooms`
- `neighbourhood_group`
- `host_is_superhost`
- `review_scores_rating`
- `number_of_reviews`

---

## Data Cleaning
To ensure reliable analysis:
- Removed listings with excessive missing values
- Filtered inactive listings and unrealistic price outliers
- Applied minimum price thresholds to remove implausibly low listings

After cleaning, **>95% of listings were retained**.

---

## Key Insights
- **Listing size drives price:** larger properties command higher nightly rates.
- **Entire homes generate the highest revenue potential.**
- **Host reputation affects occupancy rather than price.**
- **Location significantly influences pricing across cities.**

---

## Recommendation
Hosts seeking to maximize revenue should prioritize:
- Entire home listings
- Larger guest capacity
- High-demand neighborhoods

---

## Tools
- Python
- Pandas
- NumPy
- Exploratory Data Analysis (EDA)
- Data Visualization
