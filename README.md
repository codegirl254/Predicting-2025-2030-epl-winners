# EPL Winner Prediction Using Logistic Regression

## Overview

This project uses logistic regression to predict the winner of the English Premier League (EPL) based on historical performance data. The model is trained using past seasons' statistics and is used to make predictions or analyze historical outcomes.

## Table of Contents

1. [Project Description](#project-description)
2. [Data](#data)
3. [Model](#model)
4. [Usage](#usage)
5. [Results](#results)
6. [Dependencies](#dependencies)
7. [Contributing](#contributing)
8. [License](#license)

## Project Description

The objective of this project is to predict the EPL winner based on various performance metrics of teams. We use logistic regression for binary classification to determine whether a team will win the league.

## Data

The dataset used in this project includes the following columns:

- `Season_End_Year`: The end year of the season.
- `Team`: The name of the team.
- `Rk`: The team's rank in the league.
- `MP`: Matches Played.
- `W`: Wins.
- `D`: Draws.
- `L`: Losses.
- `GF`: Goals For.
- `GA`: Goals Against.
- `GD`: Goal Difference.
- `Pts`: Points.

The `Team` and `Season_End_Year` columns are encoded for model training.

## Model

### Logistic Regression

Logistic regression is used for binary classification. It predicts the probability that a team will win the league based on features such as wins, points, and goals. The following features are used in the model:

- Matches Played (`MP`)
- Wins (`W`)
- Draws (`D`)
- Losses (`L`)
- Goals For (`GF`)
- Goals Against (`GA`)
- Goal Difference (`GD`)
- Points (`Pts`)
- Encoded categorical data (`Team_encoded`, `Season_encoded`)

### Training and Evaluation

The model is trained using historical data and evaluated based on accuracy and other classification metrics.

## Usage

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/epl-winner-prediction.git
   cd epl-winner-prediction
