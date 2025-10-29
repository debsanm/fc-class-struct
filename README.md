# fc-class-struct

1. Design a class called Date that has integer data members to store month, day, and year. The class should have a three-parameter default constructor that allows the date to be set at the time a new Date object is created. If the user creates a Date object without passing any arguments, or if any of the values passed are invalid, the default values of 1, 1, 2001 (i.e., January 1, 2001) should be used. The class should have member functions to print the date in the following formats:

3/15/20
March 15, 2020
15 March 2020


2. Write a program that uses a structure named CorpData to store the following information on a company division: division name (e.g., East, West, North, or South), qtr1 sales, qtr2 sales, qtr3 sales, and qtr4 sales

Include a constructor that allows the division name and four quarterly sales amounts to be specified at the time a CorpData variable is created.

The program should create four CorpData variables, each representing one of the following corporate divisions: East, West, North, and South. These variables should be passed one at a time, as constant references, to a function that computes the division’s annual sales total and quarterly average, and displays these along with the division name.

3. Youth soccer teams earn 3 points for each win, 1 point for each tie, and 0 points for each loss. Create a teamScore class that has variables to hold the teamName, and to count the number of wins, ties, and losses. The constructor should accept the team name and initialize the three counters to 0. The class should have member functions updateWins, updateTies, and updateLosses that each add 1 to the appropriate counter. It should also have a displayRecord function that produces a nicely formatted display containing the team name, number of wins, ties, and losses so far, and the computed points. Demonstrate the class by creating a menu-driven program that creates a teamScore object and then includes a loop to display a menu and call the appropriate class function depending on the user-entered menu choice.

