# Olist Customer Insights Study

A deep-dive into customer behaviour, segmentation, and retention patterns using the [Olist](https://olist.com/) Brazilian e-commerce dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## About Olist
Olist is a Brazilian e-commerce platform that connects small businesses to major marketplaces. This dataset covers ~100k orders placed between 2016–2018 across multiple Brazilian states, including data on orders, payments, reviews, products, sellers, and customer geolocation.

## Tableau Dashboard 
An interactive Tableau dashboard that accompanies this analysis can be found [here](LINK).

## Summary of Findings
- Order volume grew steadily through 2017, peaking around November before stabilising
- Delivery delays are worst in Brazil's northern states, and late deliveries are the strongest predictor of a negative review
- Most customers are one-time buyers, with around 80% falling into the Lost or At Risk segments under K-Means clustering
- Segmentation is largely driven by Recency and Monetary value; Frequency is a weak signal in the Olist dataset

## Dataset Notes
- An order may have multiple items
- All store and partner names have been anonymised and replaced with Game of Thrones house names
- The dataset is a snapshot in time (2016–2018) and does not reflect Olist's current operations

## Limitations
- Low repeat purchase rates limit the effectiveness and robustness of frequency in the RFM analysis
- Cohort analysis is planned as a future addition
