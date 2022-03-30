# UFC Fight Data Analysis
## JoelleMarie Yonzon

## Objective
Analysis serves to explore fighter types and winners in the UFC and answer two overarching questions:
1. What kind of fighters are there in the UFC?
2. Can we predict winners in UFC fights?

## Data
The uploaded files are composed based on Ultimate Fighting Championchip (UFC) fight data scraped from sherdog.com.
Data spans fights between March 1994 and March 2021.

## Summary of findings
1. Fighter types
K-means clustering sorts fighters into four groups:
Group 0: Blue corner, biggest losers, grappler, attempts lots of submissions
Group 1: Blue corner, losers, striker, attempts lots of ineffective strikes
Group 2: Red corner, best winners, balance of striker and ground fighter
Group 3: Red corner, winners, balance of striker and ground fighter, hard hitter

Principal component analysis sorts fighters most effectively into five groups:
Group 0: Red corner, hard hitter, best striker, occasional grappler
Group 1: Blue corner, some hard hits, infrequent striker, frequent grappler
Group 2: Blue corner, soft hitter, frequent striker, frequent grappler
Group 3: Neither corner, soft hitter, infrequent striker, frequent grappler
Group 4: Red corner, hard hitter, infrequent striker, not grappler

2. Predicting winners
The trival findings show that winners can be predicted, but not with high reliability. The best model incorporates the opponent's statistics to predict wins at a rate of 63.3% reliability.
