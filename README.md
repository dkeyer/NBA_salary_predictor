# david-capstone

## Table of Contents
1. [Data Choices, Extraction, Cleaning, and Analysis](#Data_Choices)
2. [Modeling](#Modeling)
3. [Problem Statement](#Problem_Statement)
4. [Executive Summary](#Executive_Summary)
5. [Use Case Scenario](#Use_Case_Scenario)

### 1 - Data Choices, Extraction, Cleaning, and Analysis <a name="Data_Choices"></a>
The first thing I needed to do was choose the data I would work with for this project. I knew that I wanted to use NBA player statistics in order to predict player salary, but I needed to specifically decide the time frame on which I’d focus for my predictions. I settled on using five years previous stats of a player to predict his yearly salary. For example, to predict a player’s salary in 2020, I used stats from 2016, 2017, 2018, 2019, 2020. I made this decision so as to: minimize/exclude the data that would take predictive power away from my model, and for practicality in the sense that, in the future, we can use multiple years of data from the past to predict current/future salary.

### 2 - Modeling <a name="Modeling"></a>
(In progress)

### 3 - Problem Statement <a name="Problem_Statement"></a>
This project poses an interesting problem in which we must manipulate our models appropriately so as to have maximum predictive power. Is it possible to predict if an NBA player’s salary is above or below the mean salary based on his statistics from past years.

### 4 - Executive Summary <a name="Executive_Summary"></a>
The purpose of our models is to be able to take in the statistics of any given NBA player that has been in the league for five straight seasons, and, based on his statistics over that timespan, correctly classify his salary as above or below the league average for that season. In manipulating the models through feature selection, feature engineering, and hyperparameter optimization, our model can be useful in classifying which players are paid above/below the average salary, and predicting whether a player will be above or below it in the future.

### 5 - Use Case Scenario <a name="Use_Case_Scenario"></a>
These models can be used to know more in the future about, given a player’s statistics, whether he should be making above or below the league salary, and how accurately we can make these predictions.

These models can be useful for (among other things) NBA organizations when making decisions about their team salary cap and potential players they want so sign. If considering signing a player who is currently being paid below the average league salary, but who the model predicts should be making above the league average, they may want to consider that the player could be in line for a pay-raise given his stats. So, that is something that they would need to be cognizant of when planning financially and allocating salaries for players.
