# GoTrip Tokyo: Short-Term Rental Market Entry Strategy
## Project Overview
This project was the capstone for the Generation Hong Kong Junior Data Analyst Bootcamp. Our team was tasked with assisting GoTrip, an Online Travel Agent (OTA), in its strategic entry into the short-term rental market in Tokyo, Japan. 

The project emphasizes data-driven recommendations for:
- Location Selection: Identifying high-potential neighborhoods for listings.
- Pricing Strategies: Dynamic pricing models to maximize revenue.
- Host Dependency: Strategies to build loyalty among rental hosts, encouraging exclusive or preferential listings on GoTrip.

Our work leverages the Inside Airbnb dataset for Tokyo (captured on June 27, 2025), providing a comprehensive snapshot of the local market.

The analysis was conducted using a 12-week agile framework by a team of four data analysts. My primary responsibilities encompassed Project Management, Presentation & Data Visualization, and a deep-dive analysis into the impact of amenities on occupancy to formulate a strategic growth plan.

Hypothesis: By analyzing competitor data (Airbnb), we can identify underserved locations, optimal pricing tiers, and key amenity offerings that maximize occupancy, providing GoTrip with a data-driven blueprint for a successful market entry.


## Business Objectives
- Market Trend Analysis: Evaluate occupancy rates, demand patterns, and competitive landscape.
- Pricing Optimization: Develop data-backed pricing guidelines based on amenities, location, and seasonality.
- Opportunity Identification: Pinpoint underserved segments (e.g., amenity-driven demand) for targeted growth.
- Strategic Planning: Propose actionable plans to enhance host engagement and platform adoption.

## Dataset
**Source:**  Inside Airbnb (Tokyo, Kantō, Japan)
**Date:** June 27, 2025
**Files:**
-listings.csv: Detailed listings data with prices, locations, amenities, etc.
-calendar.csv: Historical availability and pricing data (if used for occupancy calculation).
-reviews.csv: Customer review data (if used for sentiment analysis).

## Methodology
Data Processing and Analysis (Python)
We used Python (Pandas, NumPy, Matplotlib, Seaborn) for exploratory data analysis (EDA) and modeling:
Data Cleaning: Handled missing values, outliers, and standardized formats using if-elif logic and custom functions (def).
Feature Engineering: Merged datasets (pd.merge), grouped by location/amenities (groupby), and calculated metrics like occupancy rate.
Visualization: Generated charts for trends (e.g., price vs. amenities scatter plots, heatmaps for neighborhood demand).
