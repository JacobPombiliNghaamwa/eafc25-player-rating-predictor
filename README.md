# EAFC 25 Player Rating Predictor ⚽
I built this project to predict a player's overall rating in EAFC 25 
using their in-game stats. It's part of my data science portfolio.

## What I did
- Explored a dataset of 180,000+ players with 109 attributes
- Used a correlation heatmap to find which stats matter most
- Built a Linear Regression model to predict overall ratings
- Discovered that log transforming player market value (value_eur) 
  jumped my R² from 0.76 to 0.94 — biggest lesson from this project

## Results
- R² Score: 0.9447
- RMSE: 1.63 rating points

## Features used to predict overall
- Passing, Dribbling, Physic, Shooting, Age, Market Value (log)

## Tech
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, NumPy

## How to run
pip install pandas scikit-learn matplotlib seaborn numpy

Then open and run fifa_rating_predictor.ipynb

## Dataset
EAFC 25 player dataset — available on Kaggle
