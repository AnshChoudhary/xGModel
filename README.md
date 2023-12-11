# Football Expected Goals (xG) Prediction

This repository contains code to predict the Expected Goals (xG) from shots in football using various machine learning models like Linear Regression, XGBoost, and Random Forest.

## Overview

Expected Goals (xG) is a statistical metric used in football (soccer) that quantifies the probability of a shot resulting in a goal based on various features and historical data. This repository provides a predictive model to estimate xG for shots taken during a football match.

## Dataset

The dataset used for this project includes information about shots taken during football matches. It contains features such as:
- Shot location
- Shot angle
- Distance from goal
- Type of play leading to the shot (e.g., open play, set-piece)
- Other relevant match and player-specific information

The dataset can be downloaded from this website: https://www.kaggle.com/datasets/joopauloduartelima/football-event-data/

## Models Implemented

### 1. Linear Regression
- Simple linear regression model trained to predict xG based on shot features.

### 2. XGBoost
- Gradient Boosting algorithm using the XGBoost library to predict xG. It offers improved performance over traditional boosting methods.

### 3. Random Forest
- Ensemble learning method using Random Forest to predict xG by aggregating multiple decision trees.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/AnshChoudhary/xGModel.git
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the notebooks or scripts associated with each model to train the models and predict xG from shots. 
   
