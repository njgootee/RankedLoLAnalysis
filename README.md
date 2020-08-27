# RankedLoLAnalysis
An analysis and classification algorithm for high rank League of Legends games

## Run
Unzip LoLanalysis.zip, and open notebook in desired environment (Python 3.8.1), with dataset saved in same directory.  Read cells, analysis, graphics or alternatively run cells to reproduce.

## Description

"League of Legends (LoL) is a multiplayer online battle arena video game developed and published by Riot Games for Microsoft Windows and macOS" (https://en.wikipedia.org/wiki/League_of_Legends). Within LoL, "Ranked Matchmaking is available to players upon reaching account level 30. It uses a similar system as Normal Matchmaking; however, pre-made teams must be of comparable ELO strength, so expert players and weak players are not allowed to team together in Ranked. After playing 8 or more Ranked games, accounts are given a public 'rank' that roughly correlates with their ELO ranking" (https://en.wikipedia.org/wiki/League_of_Legends).

The dataset (available at https://www.kaggle.com/bobbyscience/league-of-legends-diamond-ranked-games-10-min) "contains the first 10min. stats of approx. 10k ranked games (SOLO QUEUE) from a high ELO (DIAMOND I to MASTER)." These players are within the top 0.25% (https://www.leagueofgraphs.com/rankings/rank-distribution) of ranked players and can be considered experts of the game. 

Analysis focuses on the correlation of features with the target variable 'blueWins' which signifies which team won the game. Furtthermore, there is analysis of inter-correlation between other features. Classification algorithms were trained, tuned, and compared for the task of classifying 'blueWins'. Additional commentary Offers the significance of findings and possible extensions.

## Extensions
With more data, extensions of this analysis and algorithms could be developed. One possible extension is a live team win algorithm. This could inform players on how their performance and actions (both positive and negative) influence the outcome of the game. This could also help inform players on surrender votes by knowing the likely outcome of the game and if their efforts would be better spent in a fresh game or if they should continue to push for a win with decent odds. 

For this, access to Riots API would be necessary. As Riot does not desire developers to create analysis or algorithms that attempt to 'solve' the game, this may be difficult. However, several statistics sites that use the API exist, which 'solve' the game by showing players the most succesful champions, builds, runes etc.
