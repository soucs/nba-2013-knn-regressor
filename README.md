# nba-2013-knn-regressor
Using the K-nearest neighbors algorithm to predict how many points NBA players scored in the 2013-2014 season


Explanation of the columns:
* `player` - Name of the player
* `pos` - Position of the player (Center(C), Point Forward(PF), Shooting Guard(SG), etc.)
* `age` - Age of the player
* `bref_team_id` - Player team
* `g`, `gs` - No.of Games, No.of Games Started by the player
* `mp` - Minutes Played
* `fg`, `fga`, `fg.` - Field Goals, Field Goal Attempts, Field Goal Percetage(FG%=FG/FGA)
* `x3p`, `x3pa`, `x3p.` - 3-Point Field Goals, 3-Point Field Goal Attempts, 3-Point Field Goal Percentage(3P%=3P/3PA)
* `x2p`, `x2pa`, `x2p.` - 2-Point Field Goals, 2-Point Field Goal Attempts, 2-Point Field Goal Percentage(2P%=2P/2PA)
* `efg.` - Effective Field Goal Percentage; eFG% = (FG + 0.5 * 3P) / FGA
* `ft`, `fta`, `ft.` - Free Throws, Free Throw Attempts, Free Throw Percentage(FT%=FT/FTA)
* `orb`, `drb`, `trb` - Offensive Rebounds, Defensive Rebounds, Total Rebounds(TRB=ORB+DRB)
* `ast`, `stl`, `blk` - Assists, Steals, Blocks
* `tov`, `pf` - Turnovers, Personal Fouls
* `pts` - Points
* `season`, `season_end` - Season(2013-14), Season end year(2013)


Kaggle Link to Dataset: https://www.kaggle.com/razamh/unsupervised-ml
