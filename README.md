# Original Project Description

A common question within the mixed martial arts world is who is the greatest fighter of all time? I wanted to offer a solution to solve that. I first devised a web scraper that scrapes ufcstats.com. This would leave me with every result in UFC history, starting with the first ever fight between Gordon Gordeau and Taylor Wily, and currently ending with the most recent of Sean O'Malley and Merab Dvalishvili. I then took the data to create an elo engine ranking system in python. The code follows how normal chess elo engines work, following the common elo formula.

This repository contains all code for the project, as well as the csv files from webscraping, and then the final list of the elo's starting with the highest. 

To find your favorite fighter go to the all_fighters_elo.csv file and you can search!

Youtube Video Link:
https://www.youtube.com/watch?v=PLwhzlyjEgU

# Purposes of This Fork

The current purpose of this branch is to find an optimal k-value, providing insight on the volatility of UFC fighters' skill and for more accurate rankings.

## Changes Made
`predictions.json`
Dictionary of the predicted fight odds (rounded to the nearest 5 percent) and the actual fight outcomes.
For example, line 7 shows that a fighter was predicted to win 25% of the time, they would win 22% of the time.