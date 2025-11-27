# Dota 2 Winner Prediction - Kaggle Competition

This repository contains my solution notebook for a Kaggle competition on **predicting the winner of a Dota 2 match** using only the first minutes of in-game data. The goal is to build a binary classifier that estimates which team (Radiant or Dire) will win based on an early snapshot of game state.

---

## Competition

- **Kaggle:** [Dota 2: Win Probability Prediction](https://www.kaggle.com/competitions/mlcourse-dota2-win-prediction)
- **Task:** Predict the match winner using features from the first ~5 minutes of the game (gold, XP, kills, hero picks, etc.).
- **Target:** Binary label indicating whether the Radiant team wins the match.

---

## Repository Structure

```text
Dota-2-Kaggle-Competition/
├── Dota2.ipynb      # Main end-to-end notebook: EDA, feature engineering, modeling, and submission
└── README.md        # Project documentation (this file)
