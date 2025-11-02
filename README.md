# Weather Forecast Reliability Analysis for Travel Planning

### *Turning Weather Data into Smarter Travel Decisions*

---

## Executive Summary
In a world where weather heavily influences travel behavior, **we want to transform raw meteorological data into actionable insights**.  
Our goal is to **help users choose their ideal weekend destination based on weather reliability**, while illustrating how **data automation and analytics** can guide smarter real-world decisions.


---

## Business Problem
Weekend travelers often make plans based on uncertain weather forecasts.  
This uncertainty impacts:
- **User satisfaction** (bad reviews, cancelled trips)  
- **Tourism business performance** (fluctuating demand and occupancy rates)  
- **Operational forecasting** (hotels, transportation, events)  

From a business perspective, **forecast reliability** also influences **pricing strategies**.  
If hotel owners can trust a 5-day forecast predicting rain, they can **lower room rates in advance** to attract more bookings.  
Conversely, in regions where forecasts are **less reliable**, they can **wait longer before adjusting prices**, optimizing revenue once the weather trend becomes clearer.

The challenge was to build a **data-driven tool** capable of:
- Measuring the **reliability of weather forecasts**
- Recommending **optimal destinations**
- Providing **clear visual insights** for both **travelers** and **tourism professionals**
- Supporting **dynamic pricing decisions** based on forecast confidence

---

## Solution Overview
The project consists of **two complementary systems**:

| Module | Description | Value |
|--------|--------------|--------|
| **France Adventure Planner** | A **Streamlit web app** recommending weekend destinations based on forecasted weather and hotel availability | Helps users plan better trips |
| **ClimAdvisor** | A **Power BI & Python analysis** evaluating the **accuracy of 5-day forecasts** across 250+ French cities | Helps organizations assess forecast reliability & trends |

🔁 The data pipeline runs **automatically every day** via GitHub Actions, collecting **1,250 forecasts per day** through APIs and integrating real-time updates — no manual intervention required.

---

## Business Impact
- **250+ destinations** analyzed daily (mountain, coast, city)  
- **1,250+ forecasts/day** processed and updated automatically  
- **100% automation** (CI/CD pipeline with GitHub Actions)  
- **Weather reliability index** created to assess forecast accuracy and confidence  
- **Interactive dashboards & app** for personalized recommendations and strategic insights  

These insights can support:
- Tourism boards and transport companies (anticipating demand)  
- Media or travel apps (improving UX with data-backed recommendations)  
- Users (simplifying travel decisions)

---

## Key Insights
- Forecasts beyond 72h show **up to 10% drop in accuracy** in some cities.  
- **Western coastal regions** show higher forecast variability due to maritime influences.  
- Mountain areas remain **most sensitive to microclimatic changes**, reducing long-term forecast reliability.  
- A clear **data gap** exists between user perception (“it always rains here”) and statistical reality.

---

## Tools & Technologies
**Python** (Pandas, Plotly, Scrapy) • **Streamlit** • **Power BI / DAX** • **GitHub Actions (CI/CD)** • **Scraping** • **OpenWeatherMap API** • **Nominatim API** • **Make.com**

---

## What’s Next
- Add an **AI-driven recommendation model** for “where to go next weekend”.  
- Correlate weather data with **tourism KPIs** (hotel occupancy, train bookings).  
- Extend analysis to **European destinations** using the same data model.  
- Integrate **forecast reliability alerts** directly in the app.

---

## Summary
This project demonstrates how **data can bridge the gap between prediction and decision**.  
By combining automation, analytics, and interactive design, it showcases my ability to:
- Translate **data workflows into business value**
- Deliver **end-to-end solutions** (from data collection to insights)
- Build tools that are **both analytical and user-focused**

> 🎯 *Because good data doesn’t just describe the weather — it helps you decide where to go.*
