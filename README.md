# EA-Game-Fifa20-Players-Ground-Positions
EA Sports is a division of Electronic Arts that develops and publishes sports video games. Formerly a marketing gimmick of Electronic Arts, in which they tried to imitate real-life sports
networks by calling themselves the "EA Sports Network"
#1
Introduction
FIFA is a series of association football video games developed and released annually by Electronic Arts under the EA Sports
label. As of 2011, the FIFA franchise has been localized into 18 languages and available in 51 countries. Listed in Guinness World Records as the best-selling sports video game franchise
in the world, the FIFA series has sold over 325 million copies as of 2021.
FIFA is best selling game franchise followed by SIMS and Need for Speed.Stamina,Dribbling,Power Shot Starting from FIFA 20, EA Sports has given the option to
gamers to create their own players. Pick any player – the race and gender you pick don’t matter here. In the
customization section of FIFA 20, you’re able to fully design your own player. You can choose what clothes your player wears, but the tabs at the top also allow you to customize
their name, sex, race, and appearance.
#1
Introduction
Apart from choosing skin,you can also change player attributes like stamina, dribbling, goalkeeping reflexes, ballcontrol. These attributes will change player behavior on the soccer
field. Also, the player's best position will also change. We will be using machine learning to predict the best position for this newly created player. We will train a
model on current players' attributes and their current playing positions. Ball Control Goalkeeping Handling In linear regression, we try to fit a linear line with our training data
points. After training, we will get output in range (-∞, ∞), but we wanted the output to be in the range [0,1], where 0 means class 1, and 1 means class 2. To change our output
range we pass it through a special function called logistic regression Logistic Regression is a classification machine learning algorithm that can only classify data
points into two classes, that is it's a binary classification algorithm. It consists of two parts, we apply linear regression followed by a logistic function.
#2
Logistic Regression 
This is known as One v/s Rest, using we can use any binary classifier in multiclass classification problem.
logistic regression is a binary classification algorithm but our problem is a multiclass classification problem, where we have to classify players into four categories
attacker, midfielder, defender, and goalkeeper. So we should use a different classification algorithm.
#3
One v/s Rest
Instead of studying a complete new algorithm, we will use 4 logistic
regression models. First model will check wether the player is an
attacker or not, similarly other models will check other positions.
