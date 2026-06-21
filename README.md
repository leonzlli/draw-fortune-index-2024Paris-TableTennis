# Draw Fortune Index — 2024 Paris Olympics Table Tennis

A Draw Fortune Index measuring bracket luck vs. seeding in the Paris 2024 Olympic table tennis tournament.

## Overview

This project analyzes whether a player's draw (the bracket they're placed in) gives them
an easier or harder path to the medal rounds than their seeding alone would suggest. It
combines historical match results, player ranking data, and tournament draw structures
to build a "fortune index" for each competitor.

## Repository Structure
├── data/           # Raw match results from WTT tournaments and the 2024 Olympics

├── feature/         # Engineered feature tables (win rate, world ranking points, career achievement)

├── notebook/         # Data cleaning and analysis notebooks

├── Game_Theory_Project_Math_2BL.pdf   # Project write-up / reference document

└── .gitignore

## Data Sources

Match data is pulled from multiple 2024 WTT events (Saudi Smash, Singapore Smash, WTT
Champions Chongqing & Incheon, WTT Star Contender Bangkok/Doha/Goa/Ljubljana, World Cup
Macau) plus the official Paris 2024 Olympic draw.

## Features

- **Feature1** — Table win rate
- **Feature2** — World ranking points
- **Feature3** — Career achievement score

## Getting Started

1. Clone the repo
2. Open the notebook in `notebook/` to see the data cleaning pipeline
3. Raw data lives in `data/`, engineered features in `feature/`

## Status

Work in progress — analysis and write-up ongoing.
I will find better algorithms to quantify the fortune brought by the match draws, and adding more features, such as ages and dominant hands.
