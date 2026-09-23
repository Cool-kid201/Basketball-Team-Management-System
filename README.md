 Basketball Team Management System

A Python-based basketball team management system for managing players, recording games, and analyzing team and player statistics.

This project was built to practice Object-Oriented Programming, argument parsing, decorators, design patterns, generators, , and Python's special methods in a practical application.

 Features
1. Add, view, edit, and remove players
2. Search players by name or position
3. Record games and player statistics
4. View team statistics
5. Track team wins and losses
6. Calculate team win percentage
7. Find scoring, assist, rebound, steal, and block leaders
8. Display top 3 scorers
9. Display top 3 assist leaders
10. View individual player statistics
11. Calculate player averages:
 Points per game (PPG), 
b. Assists per game (APG),
-Rebounds per game (RPG),
-Steals per game (SPG) and
-Blocks per game (BPG)
Concepts Applied:

Object-Oriented Programming
Decorators,
Properties,
Generators,
Type Hints,
Special Methods,
Factory Design Pattern and
Proxy Design Pattern


The project uses several classes to model the application:

Player — represents an individual player
Team — manages team information and records
Statistics — handles statistical analysis
PlayerFactory — creates player objects
PlayerProxy — controls access to player details
Decorators


Special Methods

The project demonstrates several Python special methods:

__str__,
__repr__,
__eq__,
__lt__,
__len__,
__iter__,


These allow objects to behave naturally with Python operations such as:



 Main Menu

The application provides the following options:

1. Add Player
2. View Players
3. Edit Player
4. Remove Player
5. Search Players
6. Record Game
7. Statistics
8. Exit


The Statistics menu provides:

1. Team Overview
2. Scoring Leader
3. Assist Leader
4. Rebound Leader
5. Steals Leader
6. Blocks Leader
7. Top 3 Scorers
8. Top 3 Assist Leaders
9. Player Averages
10. Player Statistics
11. Team Record
12. Back


 Example

A player can have statistics such as:

Player: John
Games: 10
Points: 185
Assists: 52
Rebounds: 73
Steals: 18
Blocks: 9


The system can then calculate:

PPG: 18.50
APG: 5.20
RPG: 7.30
SPG: 1.80
BPG: 0.90


Possible improvements for future versions:
 Add team roster limits,
 add multiple teams and
 add a graphical user interface

