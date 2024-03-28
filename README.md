# Battleship-AI

## Description
this readme is currently in progress, I appreciate your patience, in the meantime try it out or come back soon :)

## My Contribution

### Probabilistic Agent

in progress

### How it Works

in progress

### Why it performs better than provided opponents

in progress

## Try it Out!

!!**_This game runs on java 8 (version 1.8)_**!!

clone the Battleship-AI directory

Ensure you are in the directory before running the following

## Mac, Linux
javac -cp "./lib/*:." @battleship.srcs

java -cp "./lib/*:." edu.bu.battleship.Main --p1Agent src.pas.battleship.agents.ProbabilisticAgent

## Windows
javac -cp "./lib/*;." @battleship.srcs

java -cp "./lib/*;." edu.bu.battleship.Main --p1Agent src.pas.battleship.agents.ProbabilisticAgent

This will default to player 1 being the AI I developed, at the lowest difficulty; facing an opponent that chooses randomly on a 10x10 map

## Customizers

### template (please use the executer appropriate for your operating system)
`_**executer**_` edu.bu.battleship.Main `_**player**_` src.pas.battleship.agents.`_**enemy_difficulty**_` `_**player**_` edu.bu.battleship.agents.`_**enemy_difficulty**_` `_**map_size**_`

### player
player 1
- --p1Agent
- The bot designated player 1 will be attacking the right board

player 2
- --p2Agent
- The bot designated player 2 will be attacking the left board

### Enemy Difficulty
Easy
- EasyAgent
- The easiest non-random opponent

Medium
- MediumAgent
- A slightly harder opponent 

Hard
- HardAgent
- The hardest available opponent

My AI
- ProbabilisticAgent
- The bot we were tasked to design, pit two of them together for a heated battle

### Map Size
Small
- -d EASY
- This map is a 10x10 with 1 aircraft carrier (5 squares), 1 battleship (4 squares), 1 destroyer (3 squares), 1 submarine (3 squares), and 1 patrol boat (2 squares).

Medium
- -d MEDIUM
- This map is a 20x20 with 1 aircraft carrier (5 squares), 1 battleship (4 squares), 2 destroyers (3 squares each), 2 submarines (3 squares each), and 3 patrol boats (2 squares each).

Large
- -d HARD
-  This map is a 30x30 with 2 aircraft carriers (5 squares each), 3 battleships (4 squares each), 4 destroyers (3 squares each), 4 submarines (3 squares each), and 5 patrol boats (2 squares each).

