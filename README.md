# AI-Powered-Air-Quality-Prediction

# AI Air Quality Guardian

A Python-based AI project to predict daily air quality ("Safe" or "Alert") using historical data (2004-2005) and real-time OpenWeatherMap API integration, developed for a hackathon on March 12, 2025. The project aligns with SDGs 3 (Good Health), 11 (Sustainable Cities), and 13 (Climate Action) by empowering urban residents with actionable air quality insights.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [License](#license)

## Project Overview
The AI Air Quality Guardian predicts daily air quality based on NOx levels, temperature, and humidity, classifying conditions as "Safe" (NOx < 200 µg/m³) or "Alert" (NOx ≥ 200 µg/m³). It uses:
- **Historical Data:** 7,396 hourly records (2004-2005) aggregated to daily averages.
- **Real-Time Data:** OpenWeatherMap API for current NOx, CO, temperature, and humidity in Addis Ababa.
- **Model:** Logistic Regression with enhanced preprocessing (scaling, outlier handling) and regularization to reduce overfitting.
- **Visualizations:** Daily NOx trends and historical vs. real-time comparisons.

## Features
- Predicts air quality using historical and real-time data.
- Visualizes NOx trends (2004-2005) and compares historical averages with real-time levels.
- Implements preprocessing to reduce overfitting (feature scaling, outlier handling, stratified cross-validation).
- Aligns with SDGs by addressing urban air quality challenges.

## Installation
1. **Clone the Repository:**
   ```bash
   git clone ..........
