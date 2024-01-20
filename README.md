# Next POI Recommendation with Graph Neural Networks 🌐

## Overview 👀

Welcome to my Graph Neural Networks (GNN) project! Here, I'm building a GNN model that uses historical check-ins and friendship networks to predict and recommend the next POIs that a user might find appealing. This approach is designed to enhance the personalization of location-based services 📍🔍.

## Getting Started 🚀

To get a feel for the model and how it works, check out the `gnn-poi-recommendation.ipynb` in this repository.

## Dataset 📊

This project utilizes the publicly available Foursquare NYC dataset, which is a treasure trove of user check-ins across New York City 🗽. As this dataset is not owned by me, it's important to comply with its usage rules and credit the original creators accordingly.

## Metrics 📏

The model's performance is evaluated using two key metrics:

- **Accuracy@K** 🎯: This reflects the hit-rate of our recommendations within the top K suggestions.
- **Mean Reciprocal Rank (MRR)** ↔️: This metric provides insight into the average ranking position of the true next POI.
