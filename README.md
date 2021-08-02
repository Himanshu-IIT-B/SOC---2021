# SOC-2021
SOC 2021 RL trader Code Repo

#Progress till Now :

Reinforcement Learning 
1. Learnt MDP's 
2. Implemented Q-Learning via Grid - World Problem and Tic-Toc Toe codes

Quant Trading

1. Sucessfully completed Intro to financial python suggested By mentor.
2. Traded in Live Markets to get insights.
3. Coded a Pine Script indicator for personal use on trading View (simple).
4. Got familiar with BlueShift Platform. 

Back-tested and Forward traded Intraday @9.20 Short Straddle(Bank Nifty) with exit at 3.25pm, concluded with 3 green weeks and 1 with minor loss in a month (at India-VIX in the range 13-19)

Coding Part

1. USed A2C based Agent to Backtest on AAPL 1 year using RSI 13SMA and OBV oscillator.
2. Working with different Combination of Indicators for optimal performance.
4. Working on DDPG based agent for increasing it's adaptivity towards data.

Brief Description

This project is all about coding an algo trading bot that makes decisions and trades itself. Unlike the conventional algo trading bots that just follow a set of instructions that is pre-coded this bot is way different. The Bot first learns in an environment of indicators/data by trading randomly and getting reward subsequently for the actions taken, the bot remembers the past experiences as a function of reward that helps in future decision making. So every time the bot trades randomly it’s basically using the past experiences and trying to get better and better, that usually depends on the type of agent used. Once sufficient learning was done it was used to backtest on the training set. Depending on the results obtained some parameters were changed to get optimal performance by trial and errors, sometimes changing the indicator combination itself. At the end Important parameters were noted and conclusions were made.
