# Project Title: **Voter Turnout Prediction and Party Affiliation Analysis in Rural and Urban America**

## Authors
- Jince Shi  
- Eddie Kuang  
- Riley Hawley  
- Eric Tashji  

## Project Overview

This project aims to address the problem of increasing voter turnout for both Republican and Democratic voters in areas where they are traditionally underrepresented. Specifically, Republicans seek to increase turnout in urban areas by 5%, while Democrats aim to do the same in rural areas. To achieve this, we used multiple machine learning algorithms to analyze and predict voting behavior in these regions.

## Problem Statement

Republican voters are more likely to reside in rural areas, while Democratic voters are more concentrated in urban regions. Both parties are interested in strategies to increase their voter turnout by 5% in areas where their support is traditionally weaker.

## Algorithms Used
The project leverages four key machine learning algorithms:
1. **Gaussian Mixture Model (GMM)**
2. **Logistic Regression**
3. **Linear Regression**
4. **Decision Tree**

These algorithms were chosen to predict voter turnout, analyze trends, and identify the significant factors affecting voting behavior in both rural and urban areas.

## Dataset Description
The dataset used for this project contains information on voters from both rural and urban areas, including:
- Age
- Gender
- Marital Status
- Number of Children
- Occupation
- Salary
- Standard of Living
- Party Membership
- Voter Turnout Rates
- Most Important Issue (from polling)
- Engagement with ground campaigns
- Voting history for both Democratic and Republican candidates in the last 8 years

## Preprocessing Steps
1. Handled missing values, particularly for features like the number of children.
2. Capped outliers in the salary column to prevent skewing the analysis.
3. Categorical data (e.g., gender, party membership) was encoded numerically.
4. Normalized continuous features (e.g., age, salary) to ensure consistent scaling.

## Key Findings
- **Urban Areas**: Voter turnout and party affiliation in urban areas are heavily influenced by occupation and party membership, with Democrats performing better among high-salary earners.
- **Rural Areas**: Rural areas see a stronger Republican presence, although high-earning voters in rural areas are more evenly split between both parties, making them potential swing voters.

## Files in This Repository
1. **Jince_Shi_Project_Code.ipynb**: Contains the code implementations for the analysis.
2. **Riley_Hawley_Project_Code.ipynb**: Another code implementation for the project, covering machine learning model training and evaluation.
3. **Eddie_Kuang_Project_Code.ipynb**: This file contains the code for the Gaussian Mixture Model and Decision Tree analysis.
4. **Eric_Tashji_Project_Code.ipynb**: Includes the implementation details of linear and logistic regression models.

## How to Run
1. Install the necessary dependencies by running the following command:
   ```bash
   pip install -r requirements.txt
