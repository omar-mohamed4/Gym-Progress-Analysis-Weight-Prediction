# Gym Progress Tracker

This project tracks weight, calories, protein intake, workouts, and steps over 200 days, with the ability to predict future weight.

---

## Project Description
The project analyzes workout and nutrition data to help users monitor their progress and improve their training and diet.  
It uses rolling averages and machine learning algorithms (**Linear Regression** and **Random Forest**) to predict weight trends.

---

## Features
- Daily weight tracking
- Calculation of rolling averages for calories, protein, steps, and workouts
- Predict future weight using ML models
- Visualizations of weight and activities over time

---

## Requirements
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## How to Use
1. Download the project files from GitHub.
2. Open the main code file (e.g., `main.ipynb` or `gym_progress.py`).
3. Run the code after installing the required libraries.
4. Follow instructions to add your data or view the visualizations.

---

## Sample Data
| Day | Weight_kg | Calories_Intake | Protein_Intake_g | Steps_Walked | Workout_Duration_min |
|-----|------------|----------------|-----------------|--------------|--------------------|
| 1   | 70         | 2200           | 120             | 8000         | 45                 |
| 2   | 69.8       | 2100           | 130             | 8500         | 50                 |

---

## Visualizations (Placeholders for Images)
- User weight over time
- Calories, protein, and steps (3-day rolling average)
- Predicted weight (7-day rolling average)
