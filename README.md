Titanic Survival Analysis

Overview
Analyzed passenger data from the Titanic disaster to identify which factors 
most influenced survival, then built a logistic regression model to predict 
survival based on those factors.

Dataset
891 passenger records including class, sex, age, fare, and family info.
Source: Titanic dataset (Kaggle / public dataset)

Key Findings
1. Sex was the strongest predictor — women survived at 74.2% vs 18.9% 
   for men, reflecting the "women and children first" evacuation priority.
2. Passenger class mattered a lot — survival dropped from 63% (1st class) 
   to 47% (2nd) to 24% (3rd class), likely tied to cabin location and 
   lifeboat access.
3. Children had the best odds among age groups — 58% survival rate, 
   dropping steadily to 23% for seniors.
4. Small families fared best — solo travelers had only 30% survival, 
   which climbed to 72% for families of 3, then dropped sharply for 
   families of 4+.

Model
Built a Logistic Regression model using Pclass, Sex, Age, Fare, and 
FamilySize as features.

Result: 80.4% accuracy on held-out test data.

Tools
Python, pandas, matplotlib, scikit-learn, Google Colab

Files
- `titanic_analysis.ipynb` — full analysis and model code
