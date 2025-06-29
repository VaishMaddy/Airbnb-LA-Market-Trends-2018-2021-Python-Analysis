# AIRBNB LA MARKET ANALYSIS (2018–2021)

This project analyzes the evolution of Airbnb listings in Los Angeles between 2018 and 2021, focusing on the impact of COVID-19 on pricing, occupancy, and listing characteristics.

---

## OVERVIEW

Using detailed scraped Airbnb data from [Inside Airbnb](http://insideairbnb.com/get-the-data.html), this notebook investigates:

- Changes in supply and pricing across neighborhoods
- Shifts in listing quality indicators (cleanliness, host responsiveness)
- COVID-era demand trends for different room types and cancellation policies
- Which listing features most strongly correlated with occupancy — before vs after the pandemic

---

## CONTENTS

1. **Data Overview & Preprocessing**  
   1.1 Load & Transform Summary Dataset  
   1.2 Load & Clean Detailed Dataset  

2. **Exploratory Analysis**  
   2.1 Monthly Active Listings Over Time  
   2.2 Room Type Distribution Changes  
   2.3 Average Price Trends (2018–2021)  
   2.4 Neighborhood-Level Price Changes  
   &nbsp;&nbsp;&nbsp;&nbsp;2.4.1 All Neighborhoods (Full Sorted Comparison)  
   &nbsp;&nbsp;&nbsp;&nbsp;2.4.2 Top 20 Neighborhoods by Price Change  
   &nbsp;&nbsp;&nbsp;&nbsp;2.4.3 Priority Neighborhoods: Pandemic-Era Pricing Shifts  
   2.5 Cancellation Policy Distribution During COVID  
   2.6 Average Cleanliness Score Over Time  
   2.7 What Makes a Listing Successful?  
   &nbsp;&nbsp;&nbsp;&nbsp;2.7.1 Correlation Analysis Methodology  
   &nbsp;&nbsp;&nbsp;&nbsp;2.7.2 Correlation Analysis: Pre vs Post COVID

---

## METHODOLOGY

- Cleaned and merged listing-level data (e.g., price, reviews, host behavior)
- Segmented listings into **Pre-COVID** (Jan 2018–Feb 2020) and **Post-COVID** (Mar 2020–Jan 2021)
- Estimated **occupancy rates** using reviews as a proxy
- Computed feature correlations to surface drivers of listing success over time
- Built visualizations (line charts, bar charts, heatmaps) to highlight trends

---

## KEY INSIGHTS

- **Active Listings Fell, Prices Held**: The number of active listings dropped in 2020, but average prices **remained stable** — suggesting demand concentrated among fewer, higher-quality options
- **Room Type Preferences Shifted**: Entire home bookings dominated post-COVID, reflecting travelers' preference for privacy and social distancing
- **Flexible Policies Gained Share**: Flexible cancellation options saw the **largest increase** in adoption, becoming a competitive necessity
- **Urban Core Recovery**: Downtown LA, Venice, and Los Feliz experienced the **strongest price rebounds** after COVID  
- **Trust Signals Drive Demand**: Superhost status, review scores, and fast communication were **top predictors of occupancy**  
- **Price Sensitivity Dropped**: Guests prioritized **clean, dependable listings** over bargain pricing during uncertainty  
- **Suburban Shift**: Fringe and remote-friendly areas outperformed urban centers as travelers sought more space and flexibility

---

## DATA SOURCE

- [Inside Airbnb](http://insideairbnb.com/get-the-data.html):  
  Los Angeles detailed listing and calendar data from 2018 to 2021
