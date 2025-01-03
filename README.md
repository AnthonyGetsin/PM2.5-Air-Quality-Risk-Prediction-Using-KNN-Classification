# PM2.5-Air-Quality-Risk-Prediction-Using-KNN-Classification

This project implements a real-time air quality risk assessment system using a K-Nearest Neighbors (KNN) classifier. By integrating data from the OpenAQ API and historical PM2.5 datasets, the system predicts the Air Quality Index (AQI) category associated with PM2.5 pollution levels. The workflow begins by fetching real-time PM2.5 data from sensors and categorizing historical data using AQI breakpoints. These labeled datasets train a KNN model, which achieves high accuracy, demonstrated by a 98% test score on an independent San Francisco dataset. The system not only predicts real-time health risks but also provides a foundation for monitoring long-term air quality trends and identifying regions of concern.
