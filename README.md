# stock_strategy_learner

Machine learning techniques are used to create stock trading strategies. For comparison, manual trading strategies based on human intuition are also used. The cash value of the same portfolio that underwent two different strategies are compared. 

## How machine learning is used to create trading strategies ?

There are three flavors of machine learning methods to create trading strategies:

- Regression or classification-based learner: Create a strategy using your Random Forest learner. 
- Reinforcement-based learner: Create a Q-learning-based strategy using your Q-Learner. 
- Optimization-based learner: Create a scan-based strategy using an optimizer. 

In the training phase, chosen learner uses previous data to learn a strategy. For instance, for a regression-based learner it will use this data to make predictions about future price changes. Previous data includes stock prices and 3+ indicators. 


## How manual trading strategies are created?

These strategies are basically traditional trading decisions made based on observing stock prices and various stock indicators. These strategies are simply rules such as IF INDICATOR_1 G.T. VALUE_1 THEN SHORT/LONG/CASH. 
