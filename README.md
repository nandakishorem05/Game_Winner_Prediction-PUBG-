# Game_Winner_Prediction-PUBG-
Game winner prediction


📌 Project Overview

Player performance in battle royale games like PUBG depends on many factors such as:

Combat ability

Survival strategies

Movement across the map

Resource management

This project analyzes these factors and builds a machine learning model to predict win probability (winPlacePerc).

🎯 Problem Statement
Task 1

Perform complete data analysis on the PUBG dataset.

Task 2

Build a predictive machine learning model to estimate win probability of a player/team in a match.

📊 Dataset Description

The dataset contains gameplay statistics for PUBG matches.

Target Variable

winPlacePerc

Value between 0 and 1

Represents the final placement percentage

1 → Winner

0 → Last place

This value acts as a proxy for win probability.

📥 Important Features
Player Identification

Id

groupId

matchId

Combat Statistics

kills

damageDealt

assists

headshotKills

killStreaks

longestKill

roadKills

teamKills

DBNOs

Survival & Healing

boosts

heals

revives

Movement

walkDistance

rideDistance

swimDistance

vehicleDestroys

Match Information

matchDuration

matchType

maxPlace

killPlace

Ranking Metrics

rankPoints

killPoints

winPoints

Equipment

weaponsAcquired

🧪 Project Workflow

The project follows a typical Data Science pipeline:

1️⃣ Data Loading

Import dataset using Pandas.

2️⃣ Data Exploration

Shape of dataset

Data types

Statistical summary

Unique values

3️⃣ Data Cleaning

Handling missing values

Removing anomalies

Checking null values

4️⃣ Exploratory Data Analysis (EDA)

Using Seaborn and Matplotlib to visualize:

Feature relationships

Correlation patterns

Impact of gameplay factors on winning

5️⃣ Feature Analysis

Identify important factors affecting win probability.

6️⃣ Model Building

Train a machine learning regression model to predict:

winPlacePerc

🛠️ Technologies Used

Python

Pandas

NumPy

Seaborn

Matplotlib

Jupyter Notebook

📂 Project Structure
PUBG-Winner-Prediction
│
├── FinalGameWinnerPrediction.ipynb
├── pubg.csv
├── README.md
▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/yourusername/pubg-winner-prediction.git
2️⃣ Install Required Libraries
pip install pandas numpy matplotlib seaborn
3️⃣ Run the Notebook

Open the notebook in Jupyter Notebook / Google Colab

FinalGameWinnerPrediction.ipynb
📈 Key Insights

Some factors that strongly influence winning:

High damage dealt

More kills

Longer walk distance

Efficient healing and boosts

Better placement strategy

These features significantly affect win probability.

🚀 Future Improvements

Add advanced ML models

Hyperparameter tuning

Feature engineering

Deep learning models

Build a real-time prediction web app


👨‍💻 Author

Nandakishore M
Data Science Student

GitHub: https://github.com/nandakishorem05
