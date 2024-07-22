# 🏏 IPL Player SWOT Analysis Model

## Introduction

I support RCB in IPL. It's a well-known fact that they haven't won any IPL title by the time of writing this. They often falter under pressure, especially in knockout matches.

## Project Idea

I believe that creating a model that generates a SWOT analysis for teams given as input can help prepare better for matches. This project will be a great start to my machine learning journey. 🎓

## Project Steps

1. **Data Collection** 📊
2. **Preprocessing and Preparing Data** 🛠️
3. **Selecting the Right Machine Learning Model** 🤖
4. **Training the Machine Learning Model** 🏋️‍♂️
5. **Evaluating Model Performance** 📈
6. **Tuning and Optimizing the Model** 🔧
7. **Deploying the Model and Making Predictions** 🚀

## Data Collection

### Types of Data

1. **Event Data** - The familiar stats displayed during matches. 📅
2. **Subjective Data** - Commentary that captures details like field placement, strong and weak zones of players, and mental attitude. 🎙️
3. **Tracking Data** (private): Ball tracking data, which includes details like the path and false-shot rate, is not publicly available. So let's skip this. 🔍

### Sources

- **Event Data**: ESPN Cricinfo's [IPL Team Match Results](https://www.espncricinfo.com/records/trophy/team-match-results/indian-premier-league-117) is a good starting point. 🏏
- **Commentary Data**: ESPN provides commentary data, which needs to be accessed using web scraping techniques. 🌐

This is my first time implementing web scrapping, and not all websites allow you to do it. Luckily espn allows to do so. I found that they even have a python library for it. 
Now I don't have to invent the wheel again.


