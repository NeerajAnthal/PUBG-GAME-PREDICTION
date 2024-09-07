# PUBG Game Prediction

![PUBG Airplane GIF](https://raw.githubusercontent.com/yourusername/yourrepository/branchname/path-to-your-gif/pubg-airplane.gif)


## Overview
This project aims to predict a player's performance in the popular game **PUBG** using various in-game statistics. The model helps determine crucial aspects such as a player's expected placement in the game based on features like kills, assists, damage dealt, and more.

## Features
- Predict player win percentages using various machine learning models.
- Analyze in-game statistics such as kills, assists, and damage dealt.
- Compare different model performances for accuracy and precision.

## Models Used
- **CatBoost Model**
  - RMSE: 0.08
  - R²: 0.93
- **Linear Regression**
  - RMSE: 0.14
  - R²: 0.81

## Dataset
The dataset includes features such as:
- `assists`
- `kills`
- `damageDealt`
- `matchType`
- `winPlacePerc`

## How to Run the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/PUBG-GAME-PREDICTION.git
    ```
2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook to train the model:
    ```bash
    jupyter notebook PUBG_Prediction.ipynb
    ```

## Installation
Make sure you have Python 3.x installed. Install dependencies using:
```bash
pip install -r requirements.txt
