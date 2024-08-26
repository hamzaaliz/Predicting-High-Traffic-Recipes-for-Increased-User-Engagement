# Predicting High-Traffic Recipes for Increased User Engagement

## Project Overview

Tasty Bytes, a recipe discovery platform, aims to enhance user engagement and increase subscription rates by showcasing popular recipes on the website’s homepage. This project focuses on developing a predictive model to identify which recipes are likely to generate high traffic, thereby optimizing the homepage content to attract more visitors.

## Objectives

The primary objectives of this project are:

1. **Predict Recipe Popularity:** Develop a model that accurately predicts which recipes will drive high traffic to the website.
2. **Achieve High Prediction Accuracy:** Ensure the model correctly predicts high-traffic recipes with at least 80% accuracy.
3. **Optimize Homepage Content:** Use model predictions to feature recipes that maximize user engagement and subscription rates.
4. **Evaluate Model Performance:** Assess the model using metrics such as Recall and F1 Score.
5. **Provide Business Recommendations:** Offer actionable insights based on model findings to improve content strategy.

## Dataset Description

The dataset provided by Tasty Bytes includes the following features:

- **recipe:** Unique numeric identifier for each recipe.
- **calories:** Total calories per serving in the recipe.
- **carbohydrate:** Amount of carbohydrates (in grams) per serving.
- **sugar:** Amount of sugar (in grams) per serving.
- **protein:** Amount of protein (in grams) per serving.
- **category:** Type of recipe, categorized into one of ten possible groupings (e.g., 'Lunch/Snacks', 'Desserts', 'Vegetable').
- **servings:** Number of servings that the recipe yields.
- **high_traffic:** Indicates whether the recipe led to high traffic on the website ("High") or not.

## Key Findings

- **Traffic Analysis:** The analysis revealed that certain food categories like 'Potato', 'Vegetable', and 'Pork' are more likely to drive high traffic.
- **Model Performance:** The Logistic Regression model, despite being a baseline, outperformed the fine-tuned Random Forest model in terms of F1 Score, making it the model of choice for deployment.
- **Business Recommendations:** It’s recommended to deploy the Logistic Regression model, regularly retrain it with new data, and monitor performance using Recall and F1 Score metrics.
