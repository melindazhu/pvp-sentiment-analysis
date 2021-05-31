# pvp-sentiment-analysis
Application of existing sentiment analysis techniques to player communications in MMORPGs (massively multiplayer online role-playing games) through a supervised learning setting.<br/>
<br/>
CS229 Machine Learning (Spring 2021), Stanford University. <br/>
Contributors: Kevin Borst, Thomas Yang, Melinda Zhu.


## Overview
Since the first PvP (player vs. player) video games began to allow live communications during matches, toxic players have utilized in-game chats as platforms for unfiltered cyberbullying with little meaningful consequences. Existing filters used in games today only identify specific profanity at best, and players rarely suffer reprisal for racist, sexist, homophobic, or other insulting or derogatory remarks during live gameplay. Simultaneously, a unique lexicon of "gamer slang" has arisen, both in general and for specific games.  Gamer slang is relatively unknown and unused in regular conversation, and as a result, sentiment analysis algorithms (the identification of emotional connotations of text) adapted to normal English conversations are unable to comprehend and recognize toxic messages in games. Our project aims to extend existing sentiment analysis models to the "language of gaming" through a supervised learning setting. The inputs to our algorithms are in-game chat messages in vectorized forms. We then compare the performance of several classifiers such as Support Vector Machines, Naive Bayes, K-Nearest Neighbors, Random Forests, and neural networks to output one of three sentiments – neutral/positive (class 0), negative attitude (class 1), or derogatory (class 2) – for each message.  This text classification is foundational to any effort to regulate live toxic language.


## Contents
#### Baselines
[Binary SVM Baseline](https://github.com/melindazhu/pvp-sentiment-analysis/blob/main/SVM_Binary_Baseline.ipynb)
