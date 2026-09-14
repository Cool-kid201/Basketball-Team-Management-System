🏀 Basketball Team Management System

A Python-based basketball team management system for managing players, recording games, and analyzing team and player statistics.

This project was built to practice Object-Oriented Programming, argument parsing, decorators, design patterns, generators, , and Python's special methods in a practical application.

✨ Features
👤 Add, view, edit, and remove players
🔎 Search players by name or position
🏀 Record games and player statistics
📊 View team statistics
🏆 Track team wins and losses
📈 Calculate team win percentage
⭐ Find scoring, assist, rebound, steal, and block leaders
🥇 Display top 3 scorers
🎯 Display top 3 assist leaders
📋 View individual player statistics
📊 Calculate player averages:
Points per game (PPG)
Assists per game (APG)
Rebounds per game (RPG)
Steals per game (SPG)
Blocks per game (BPG)
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



🎮 Main Menu

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


📊 Example

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
 Add team roster limits
 Add multiple teams
 Add a graphical user interface

