# IPL Match Winner Predictor & Analysis (2008-2024)

## Problem Statement
Can we predict the winner of an IPL match using historical data?
What factors actually determine who wins - teams, venue, or toss?

## Key Findings
- Mumbai Indians are the most successful team with 144 wins
- Toss barely matters - toss winner wins only 50.6% of matches
- Venue is the #1 predictor of match outcome - more important than team strength
- Teams choosing to field win 53.6% vs 45.3% when batting
- AB de Villiers leads Player of the Match awards with 25

## Machine Learning Model
- Algorithm: Random Forest Classifier
- Features: Team, City, Toss Winner, Toss Decision, Team Win Rate
- Accuracy: 52.40%
- Key insight: City/venue is the strongest predictor (importance: 0.185)

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

## Dataset
IPL matches data 2008-2024 - 1095 matches, 260920 ball-by-ball deliveries

## How to Run
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook

## Author
Nandini | CS & Data Science
