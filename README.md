# python_assessment
Assessment Q1 
A popular RJ hosts a competition in his evening radio show. One lucky caller gets a load of goodies if he/she can guess the word 
whose alphabets have been jumbled. For example the presenters gives you a series of alphabets "epmalxe" and the participant has to figure out the word it
spells, which is "Example". Your friend Mr. S. Khan has qualified for the show and is due to appear tomorrow
evening sadly he is no good with spellings yet the goodie bag will make him very happy. 
You can help Mr Khan by writing a solver, a small computer application that can look up all the various combinations and instantly tell you the right set of words.

Brief : 
Write a small command line application that takes the jumbled input string and prints out all correct english words with the same set of characters. The set of
words are listed in the attached file.(dictionary.txt)

Assessment Q2
You wish to buy video games from the famous online video game store Mist. Usually, all games are sold at the same price, p dollars. However, they are planning to
have the seasonal Halloween Sale next month in which you can buy games at a cheaper price. Specifically, the first game will cost p dollars, and every subsequent
game will cost d dollars less than the previous one. This continues until the cost becomes less than or equal to m dollars, after which every game will cost m dollars.
How many games can you buy during the Halloween Sale?

Example :
p = 20, d = 3, m = 6, s = 70
The following are the costs of the first 11, in order:
20, 17, 14, 11, 8, 6, 6, 6, 6, 6, 6

Start at p = 20 units cost, reduce that by d = 3 units each iteration until reaching a
minimum possible price, m = 6 . Starting with s = 70 units of currency in your Mist
wallet, you can buy 5 games:
20 + 17 + 14 + 11 + 8 = 70

Create a function howManyGames which will accept 4 arguments
howManyGames(p, d, m, s)

And will return the total number of games that can be bought alongwith prices of each game.(Can return an array of response)

Sample Input
howManyGames(20, 3, 6, 70)
Sample Output
[5, [20, 17, 14, 11, 8]]

Assessment Q3
John has been keeping logs of every time he charged his laptop, which includes the duration of the charge, voltage at power socket and the duration of TV watching that
followed. He wants to use this log to predict how long he will be able to watch TV after charging his laptop, so that he can plan his activities accordingly.

Challenge
You are given access to John’s laptop charging log by reading from the file “training_data.txt” 
(You will get this file as an attachment to email). The training data file will consist of 100 lines, each with 3 comma-separated numbers.
1. The first number denotes the amount of time the laptop was charged.
2. The second number denotes the voltage of the power socket used for charging the
laptop.
3. The third number denotes the amount of time the battery lasted.

The input for each of the test cases will consist of a list of 2 numbers.First will be the number of hours the laptop was charged and the second voltage.
For each input, output 1 number: the amount of time you predict his battery will last.

Sample Input
1.50 220
Sample Output
3.00
