# Real Estate Sales Analysis Guide

## Data

### Evolution of real estate sales (number and prices) over a period of 15 years

**Main page:** [https://statbel.fgov.be/en/themes/housing/real-estate#figures](https://statbel.fgov.be/en/themes/housing/real-estate#figures)

Use the Excel file: **Sales of real estate (N) per quarter per municipality 2010-2025**

> **Hint:** The original data structure might need some transformation for convenient exploration/querying and handling of missing data.

## Data Exploration

Make a visualization to help explore the evolution of the number (N) of transactions and price (€). Can you make sense of what you see? Feel free to use whatever tools or information you have available for this last question.

**Bonus question:** Can you also visualize the data on a map? 
- Spatial units available here: [https://statbel.fgov.be/fr/open-data/secteurs-statistiques-2024](https://statbel.fgov.be/fr/open-data/secteurs-statistiques-2024)

**Bonus question:** Can you make the visualizations interactive for the user?

## Price Corrector

Build a "price corrector" that takes as input a listing price at time `t0`, the municipality code (`refnis`) and the type of property, and predicts the price at another time `t1`. Only use the time range available in the dataset in this part. 

> **Hint:** No modeling needed in this step

**Bonus question:** Can you forecast the price for future quarter(s) not provided in the dataset?