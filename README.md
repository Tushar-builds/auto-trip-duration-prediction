# Auto Trip Duration Prediction using Machine Learning

## Team
Hackenatics

## Hackathon
Netweb AI for Public Good Hackathon

## Overview
This project demonstrates a machine learning–based prototype for predicting
trip duration in smart transportation systems. The model estimates travel time
using distance and time-based features.

## Problem Statement
Accurate estimation of trip duration is critical for efficient transportation
planning. Existing systems often fail to consider multiple influencing factors.
This project applies a Gradient Boosting Regressor to predict trip duration
from historical trip data.

## Approach
- Load and clean historical trip data
- Perform feature engineering (distance and time features)
- Train a Gradient Boosting Regression model
- Predict trip duration for sample trips

## Dataset
NYC Taxi Trip Duration Dataset (Kaggle)  
https://www.kaggle.com/competitions/nyc-taxi-trip-duration/data

## Model Used
- Gradient Boosting Regressor (GBM)
- Features:
  - Haversine distance
  - Pickup hour
  - Day of week

## Prototype Scope
This repository contains a basic prototype showcasing the idea and technical
approach. It is not intended to be a production-ready system.

## Future Enhancements
- Integration of real-time traffic data
- Weather-aware predictions
- Route optimization
- Deployment as a web or mobile application

