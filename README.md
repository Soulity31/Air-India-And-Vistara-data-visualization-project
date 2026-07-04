# ✈️ Business Class Flight Price Analysis

## Objective
Analyse Indian domestic business class flight prices from EaseMyTrip to understand what drives pricing differences across airlines, stops, and cities.
This is a learning project
---

## Dataset
[Flight Price Prediction](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction) by Shubham Bathwal on Kaggle — `business.csv` only, scraped Feb–Mar 2022.

Key columns: `airline`, `source_city`, `destination_city`, `stops`, `time_taken`, `days_left`, `price`

---

## Conclusions
- **Vistara prices higher than Air India** across all stops, source cities, and destination cities
- **Non-stop flights cost more** than one-stop — business class passengers pay for convenience
- **Booking earlier is cheaper** — price drops as days_left increases
- **Longer flights cost more** — duration and price are positively correlated

---

**Stack:** pandas · numpy · matplotlib · seaborn  
**Author:** [Soulity31](https://github.com/Soulity31)
