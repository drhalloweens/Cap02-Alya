AVAILABLE ALL YEAR, BOOKED ALMOST NEVER
Inside Bangkok's Zombie Airbnb Listings
Why Availability Fails to Turn into Bookings

Capstone Project - Data Analytics & Data Science
By Madina Febriani
Purwadhika Digital Technology School

**PROJECT OVERVIEW**
This project investigates a critical marketplace paradox in Bangkok’s Airbnb ecosystem:
Why do many Airbnb listings remain underperforming despite being available almost all year?

Using data-driven analysis, this study compares high-performing listings against low-performing
("Zombie") listings to identify the factors that drive demand, visibility, and guest engagement.

**BUSINESS PROBLEM**
A significant number of Airbnb listings in Bangkok show the following pattern:
- Available 300 - 365 days per year
- Receive very few or zero reviews
- Fail to convert supply into bookings

These listings appear active but contribute little to actual marketplace demand.
They are referred to as "Zombie Listings".

**CORE BUSINESS QUESTION**
What prevents some Airbnb listings from capturing market demand,
while others consistently succeed?

**TARGET AUDIENCE**
- Airbnb business and marketplace teams
- Product, strategy, and data analysts
- New and existing Airbnb hosts
- Stakeholders evaluating listing optimization strategies

**DATASET**
Source: Public Airbnb listings data for Bangkok
Observations: ~15,800 listings

**Key variables:**
- price
- room_type
- availability_365
- minimum_nights
- number_of_reviews
- reviews_per_month
- last_review
- neighbourhood
- listing_name

**DATA CLEANING SUMMARY**
- Removed invalid price entries
- Standardized categorical values
- Converted date columns to datetime
- Handled missing values strategically
- Retained business-meaningful outliers

**ANALYSIS STRUCTURE**
1. Exploratory Data Analysis (EDA)
2. Define Listing Performance
3. Characteristics of Popular vs Low-performing Listings
4. Inferential Statistics & Modeling (Poisson Regression)
5. Keyword Analysis in Listing Names
6. Insights & Business Recommendations

**KEY INSIGHTS**
- Entire home/apartment listings consistently outperform other room types
- High availability does not guarantee bookings or reviews
- High price and long minimum stay reduce popularity
- Many listings are visible but inactive in demand terms
- Keyword optimization improves listing engagement


**TOOLS & TECHNOLOGIES**
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels
- Jupyter Notebook

**PROJECT STRUCTURE**
├── data/
│   └── airbnb_bangkok_cleaned.csv
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_market_overview.ipynb
│   ├── 03_define_performance.ipynb
│   ├── 04_factor_analysis.ipynb
│   ├── 05_statistical_modeling.ipynb
│   └── 06_insights_recommendations.ipynb
├── assets/
│   └── figures/
├── presentation/
│   └── Available_All_Year_Booked_Almost_Never.pdf
└── README.md

## Link Deliverables
- Presentation: [Link Presentation] https://www.canva.com/design/DAHAjseb9ec/9bwmVfcxKvC5FoYNOyqy9A/edit?utm_content=DAHAjseb9ec&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton 
- Dashboard Tableau: [Link Tableau] https://public.tableau.com/views/AirBnBListingsBangkok_17703946942330/Sheet1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

**FINAL NOTE**
This project is framed as a marketplace analysis aligned with Airbnb business logic.
It focuses on explaining why some listings fail and how performance can be improved
through data-driven decisions.
