# <u>Motivation:</u>
In this short exploratory analysis of Rainbow Six: Siege data, my goal is to identify counters to the claim that Siege is a perfectly balanced game.  These include: a huge spread on pick rate of certain characters, Win rates for characters greater than 55%, and Win Rates for roles in general greater than 55%.  If these sorts of statistics are present, it may be an indicator of game imbalance, and should be promptly corrected to the best of the game developers' abilities.

Sometimes in competitive video games, certain playable characters, map environments, or abilities can be either too strong, or too weak compared to others.  Characters might have abilities that have almost zero counters, or maps may completely favor one team to another depending on their role, e.g.: Attacking/Defending.  If these imbalances are not made aware and changed in a prompt time frame, the game can become hard or simply un-fun to play; as you may lose due to a game mechanic that you cannot play against.

The same can be said for sports or other competitive environments, where some rules may be deemed archaic or outdated, and hinder the player's or give them an advantage.  An example of this is in the UFC, where a fighter cannot kick an opponent who is on the ground, so that opponent can leg lock you with almost no counter to be had from the other fighter.  These fules should be reviewed and updated periodically, just as developers modify and edit their in game mechanics; aka the game's 'rules'.

# <u>Initial Questions and Answers: ABSTRACT:</u>
1. What to do if player character imbalanced?
+ Weaken/Strengthen character's equipment or abilities.  A nerf/buff could also come in the form of weakening/strengthening another player who is a counter to said player. Or by changing/modifying the ability itself.  In Siege's case, this meant taking away an ACOG scope from certain characters, not allowing them to get headshots on opponents as easily.

2. What to do if map imbalanced?
+ Rework map environment, change certain areas, remove or add obstacles, take away windows, and change objective locations

3. How do video game imbalances relate to real world sports/competitive environments?
+ Sometimes, rules in sports/competitive events can become outdated or hindering. Just like how video games change and rework rules/maps/characters, sports and other competititions should also consider reviewing over rules in a more frequent manner.



# <u>Libraries Used:</u>

Pandas: Used to aggregate, modify dataframes
Numpy: Aiding Pandas in its data manipulation
MatplotLib: Visualizations
Scipy.Stats: For statistical testing of hypothesis tests
Seaborn: Visualizations
Sklearn: For Scaling properties in the preprocessing library
Warnings: to filter out any warnings/exceptions

# <u>Files In Repository:</u>
S5_objectives: Rainbow Six Siege Objectives dataset 
S5_operators: Rainbow Six Siege Operators dataset
mapWinRate.png: Graph illustrating Win Rates on certain maps for certain operators
operatorPickRate.png: Illustrates pick rate for certain operators at different skill rankings
operatorWinRate.png: Illustrates win rate for certain operators at different skill rankings
