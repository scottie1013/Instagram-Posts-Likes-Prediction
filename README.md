# Instagram Posts Likes Prediction

## Project Overview
This project aims to predict the number of likes an Instagram post will receive based on various features. We use machine learning models, specifically XGBoost regression and classification, to make these predictions.

## Features
- Predictive modeling of Instagram post engagement
- Image analysis to determine visual features that impact likes
- Data preprocessing and feature engineering
- Model evaluation and performance metrics

## Installation
To set up this project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/scottie1013/Instagram-Posts-Likes-Prediction.git
   ```
2. Navigate to the project directory:
   ```
   cd Instagram-Posts-Likes-Prediction
   ```
3. Create a virtual environment:
   ```
   python -m venv .venv
   ```
4. Activate the virtual environment:
   - On Windows: `.venv\Scripts\activate`
   - On macOS and Linux: `source .venv/bin/activate`
5. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Models
We use two main models in this project:
1. XGBoost Regression: For predicting the exact number of likes
2. XGBoost Classification: For categorizing posts into low, medium, and high engagement

## Results

XGBRegressor: R-squared score of 0.7655, 
The Root Mean Squared Error (RMSE) is 89,333.97, 

XGBoost Classifier:  overall accuracy of 74%, indicating it correctly classified 74% of all instances. 


## Future Work
- Create more complex features by combining existing ones, such as likes-to-follower ratio or engagement rate.
- Extract text features from post captions or comments using natural language processing techniques.
- Incorporate external data sources like trending topics, holidays, or major events that might influence engagement.
- Analyze the impact of Instagram algorithm changes on post visibility and engagement.
- If possible, collect more data to increase the dataset size and diversity.
- Use data augmentation techniques for images to artificially expand the dataset.

