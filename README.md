# Moneyball Re-Creation ⚾

Project is focused on recreation the way of general manager of Oakland Athletics Billy Beane and his assistant Paul DePodesta thought when they used data-drive approach to promote to playoff series. It's the textbook case of using such an approach in sports. I was inspired by the other people who did the similar thing, but I try to dig deeper to do it another way. I also used some simple ML models without solid tuning.

## Project structure 🗂️
Project consists of three folders

- `data` — contains all the datasets
- `notebooks` — contains two Google Colab notebooks: data wrangling and modeling in `.ipynb` format
- `visualization` — contains visualizations of different parts of data

## Information about data 📊

Project based on a Kaggle dataset — **[MLB Statistics 1962-2012](https://www.kaggle.com/datasets/wduckett/moneyball-mlb-stats-19622012)**
Key metrics of project are:
- `OBP` — **on-base percentage** reflects a batter's ability to reach base, no matter how they achieve this through a hit, a walk (base on balls), or being hit by a pitch
- `SLG` — **slugging percentage** represents the average number of total bases a player achieves per at-bat
- `BA` — **batting average** is a basic offensive statistic that measures a player's success at hitting the ball
- `OSLG` — **opponent slugging percentage** this stat applies the concept of slugging percentage to pitchers, showing how much damage opposing hitters do against them
- `OOBP` — **opponent on-base percentage** OBP applied to opponent

The key idea here is that usually scouts looked at BA when they choose new players but they didn't notice the impact of OBP and SLG. That's how Billy Beane and Paul DePodesta got the advantage

## Project goal 🎯
- recreate the way Billy Beane and Paul DePodesta asked questions to data
- using data and modeling predict the following things: how many games team should win to promote to playoff, how many runs allowed, how many runs team should score and compare it with real numbers

## Result
You can check the result in the `data/result.csv` file. For more information about 2002 season in MLB check out the **[Baseball Reference](https://www.baseball-reference.com/teams/OAK/2002.shtml)** page.
