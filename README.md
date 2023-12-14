
# Battleships

## Introduction
A python implementation of the classic board game. Includes both a singleplayer and multiplayer (vs AI) CLI mode as well as a GUI mode using flask (multiplayer vs AI only). Included are also a range of configuration files that allow you to customize your gameplay experience as well as a few functionality tests.


## Prerequisites
Python 3.11.4

Install flask with pip
```bash
  pip install flask
```
Install setuptools with pip
```bash
  pip install setuptools
```
## Installation
Not necessary to the grader of this project! You can install this project from github. In git bash use

```bash
  git clone https://github.com/imferolla/battleships.git
```

## Getting Started
To begin playing the CLI game, in your terminal change your directory to battleships/battleships and run components.py. For the GUI mode change your directory to the same folder, run main.py and then go to http://127.0.0.1:5000/placements. You will also find a placements.json, config.txt and battleships.txt file in that folder. These can be updated to modify your game. Config has some basic game variable options, battleships allows you to modify the amount of ships, their names, and their sizes, and placements allows you to create predetermined ship placements.
## Testing
The tests are designed to be ran in VSCode. During workshops issues arose with the tests simply refusing to run and sometimes showing import errors preventing them from running. At the time of writing this all the provided tests and all of the further tests that I've created passed. Please run them through VSCode's testing software with battleships/battleships folder open for the best results.
## Details
Author: Jake Klar

License: See included file

Github repository: https://github.com/imferolla/battleships
