# Chapter 12: K-Nearest Neighbors — Lab Report

## Student Information
- **Name:** Nathaniel Tryon
- **Date:** 5/3/26
- **Course:** COSC 2436

## Algorithm Summary
- **How it works:** It classifies categorizing an item into a specific group. Regression involves predicting a continuous value, like estimating how many loaves of bread a bakery will sell on a given day based on various factors.
- **Time complexity:** Null
- **When to use it:** AI image recognition  

## Test Results
Bakery Data:
- weather  weekend_holiday  game_on  loaves
- 0         3                0        0      42
- 1         5                1        1      95
- 2         2                0        0      30
- 3         4                1        0      72
- 4         1                0        1      38
- 5         5                0        0      55
- 6         3                1        1      78
- 7         4                0        0      50
- 8         2                1        0      58
- 9         5                1        0      85
- 10        1                0        0      22
- 11        3                0        1      52
- 12        4                1        1      88
- 13        2                0        1      44
- 14        5                0        1      70
- 15        3                1        0      65
- 16        4                0        1      62
- 17        1                1        0      48
- 18        2                1        1      70
- 19        4                1        0      75

Features shape: (20, 3)
Target shape: (20,)

KNN model trained with k=4

Today's conditions: Weather=4, Weekend/Holiday=1, Game=0
Predicted loaves to bake: 70.5
