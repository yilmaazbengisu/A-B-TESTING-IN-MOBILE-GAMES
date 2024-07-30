# Cookie Cats A/B Test Analysis

## Introduction

This repository contains an analysis of an A/B test conducted in the mobile game Cookie Cats. The main objective of this analysis is to determine the optimal placement of a game gate to enhance player retention and revenue. The test involves moving the gate from level 30 to level 40 and examining the impact on player behavior.

## Project Goal

In mobile games, especially those following the free-to-play business model, optimization is crucial due to the high competition in the industry. Gates in games are designed to drive revenue through in-app purchases and provide players with enforced breaks to enhance their overall enjoyment and prolong their engagement.

This project aims to determine the optimal gate placement in Cookie Cats by analyzing player retention data from an A/B test. The key focus is on understanding how moving the gate from level 30 to level 40 affects player retention on days 1 and 7.

## Dataset Description

The dataset includes A/B test results from 90,189 players who installed the game while the test was running. Each player was randomly assigned to one of two groups:
- `gate_30`: Control group with the gate at level 30.
- `gate_40`: Test group with the gate at level 40.

The variables in the dataset are:
- `userid`: A unique identifier for each player.
- `version`: The group assignment (`gate_30` or `gate_40`).
- `sum_gamerounds`: The number of game rounds played by the player during the first 14 days after install.
- `retention_1`: Indicates if the player returned to play 1 day after installing (1 if yes, 0 if no).
- `retention_7`: Indicates if the player returned to play 7 days after installing (1 if yes, 0 if no).

The dataset can be accessed [here on Kaggle](https://www.kaggle.com/datasets/mursideyarkin/mobile-games-ab-testing-cookie-cats?select=cookie_cats.csv).

## Analysis Steps

1. **Data Exploration and Cleaning**
   - Load the dataset and inspect its structure.
   - Handle missing values if any.
   - Summarize the key statistics of the dataset.

2. **Descriptive Analysis**
   - Compare the distributions of `sum_gamerounds`, `retention_1`, and `retention_7` between the two groups (`gate_30` and `gate_40`).
   - Visualize the data using histograms, box plots, and bar charts.

3. **Hypothesis Testing**
   - Perform hypothesis testing to determine if there are statistically significant differences in player retention and game rounds between the two groups.
   - Use appropriate statistical tests such as t-tests for continuous variables and chi-square tests for categorical variables.

4. **Effect Size Calculation**
   - Calculate the effect size to understand the magnitude of the difference between the groups.

5. **Conclusion and Recommendations**
   - Summarize the findings of the analysis.
   - Provide recommendations on gate placement based on the results.

## Findings

- **Retention Analysis**: Determine whether the gate placement at level 30 or level 40 results in higher retention rates on days 1 and 7.
- **Game Rounds Analysis**: Assess the impact of gate placement on the number of game rounds played by players.


## Conclusion

Based on the analysis, the optimal placement of the gate will be recommended to maximize player retention and revenue. The findings will help in making data-driven decisions to enhance the player experience and business outcomes for the game Cookie Cats.


## Acknowledgments

- The dataset is provided by Tactile Games.
- The analysis is inspired by the work done in the mobile gaming industry to optimize player engagement and monetization.

