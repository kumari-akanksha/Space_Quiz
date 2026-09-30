# 🚀 Space Quiz 

## Project Overview

**Space Quiz Adventure** is a small, interactive desktop quiz game built with Python and Tkinter. The game uses a space theme to make learning and practicing programming concepts a little more fun.

Players move through three levels—Easy, Medium, and Hard—and answer multiple-choice questions within a 15-second time limit. Each player starts with three lives, so every answer matters.

This project brings together several important Python concepts, such as functions, lists, dictionaries, modules, conditional statements, file handling, GUI development, event-driven programming, and timers.

## Problem Statement

Many beginner Python projects are limited to the command line, which can make them feel less interactive. This project aims to solve that by creating a simple graphical quiz application where learners can practice Python programming concepts while also experiencing how a complete desktop application works.

## Objectives

- Build a working desktop application using Python.
- Organize the project into separate modules for easier understanding and maintenance.
- Create a simple and user-friendly graphical interface.
- Add input validation and basic error handling.
- Combine questions, levels, lives, scoring, timers, and file storage into one complete game.
- Use basic automated tests to check important parts of the project.

## Main Game Features

- 🚀 Space-themed interface built with Tkinter
- ❤️ Three lives for each player
- ⭐ Three difficulty levels: Easy, Medium, and Hard
- ⏱️ 15 seconds to answer each question
- 🏆 Different scores for different levels
- 🎨 Four answer choices for every question
- 💾 Scores are saved in `scores.txt`
- 🔄 Option to play again after finishing
- ❌ Option to exit the game
- 🧪 Basic tests to check the project

## Game Levels

### Level 1 – Easy

This level contains simple questions related to space and astronomy.

### Level 2 – Medium

This level introduces more detailed and slightly more challenging astronomy questions.

### Level 3 – Hard

This level contains the most challenging space-related questions in the game.

## Scoring System

Players earn points for every correct answer:

- **Level 1:** 10 points
- **Level 2:** 20 points
- **Level 3:** 30 points

If a player chooses the wrong answer or the timer runs out, one life is lost.

## Technologies and Concepts Used

- Python 3
- Tkinter
- Functions
- Lists
- Dictionaries
- Modules
- File handling
- Event-driven programming

## How to Run the Project

1. Make sure Python 3 is installed on your computer.
2. Open the project folder in VS Code, IDLE, or another Python editor.
3. Open a terminal in the project directory.
4. Run the following command:

```bash
python main.py
```

5. Enter your player name and click **START GAME**.

Tkinter is normally included with Python on Windows and macOS. On some Linux systems, Tkinter may need to be installed separately.

## Project File Structure

- `main.py` – starts the application
- `game.py` – handles the main game logic and graphical interface
- `questions.py` – contains the question database
- `score.py` – handles score storage
- `utils.py` – contains helper functions
- `scores.txt` – stores saved scores
- `test_project.py` – contains the project tests
- `README.md` – contains the project documentation
- `statement.md` – contains the project summary
- `requirements.txt` – lists project requirements

## Installation

1. Install Python 3.10 or a newer version.
2. Download or clone the project repository.
3. Open a terminal inside the project folder.
4. Make sure Python and Tkinter are available on your system.

The project uses Python's standard library and does not require any external Python packages.

## Testing

The basic project tests can be run using:

```bash
python test_project.py
```

The tests check important parts of the game, including the three-level question structure, the number of questions and answer choices, and the validity of answer indexes.

## Manual GUI Testing

The following parts of the game should also be checked manually:

1. Entering an empty player name should show a warning.
2. Every question should display four answer choices.
3. A correct answer should increase the score.
4. An incorrect answer should reduce the player's lives by one.
5. Letting the timer run out should also reduce one life.
6. The timer should restart for every new question.
7. The game should move between levels correctly.
8. The player's score should be saved when the game ends.
9. **Play Again** should return the player to the starting screen.
10. **Exit** should close the application.

## VITyarthi Modules

### Functional Modules

1. Player and game initialization
2. Question and answer processing
3. Level and life management
4. Timer control
5. Score management and file storage
6. GUI presentation and navigation

### Non-Functional Requirements

- **Usability:** The controls should be simple and the game status should be easy to understand.
- **Performance:** The application should remain lightweight and responsive.
- **Reliability:** User input and changes to the game state should be handled safely.
- **Maintainability:** The code is divided into meaningful Python modules.
- **Resource efficiency:** The project uses the Python standard library and does not depend on external services.
- **Error handling:** The application checks for an empty player name and handles score-file reading safely.

## Design Artefacts

The project's design diagrams are available in the `diagrams/` directory. They cover the architecture, workflow, use case, sequence, class/component, and storage designs.

## Future Improvements

There are several features that could make the game even more engaging in the future:

- 🔊 Add sound effects
- ❓ Expand the question collection
- 🎯 Let players choose their difficulty level
- 🏆 Add a high-score table
- ⚡ Introduce power-ups
- 🚀 Add an animated spaceship
- 🎨 Add more images and visual effects
- 🎵 Include background music

---

Made as a beginner-friendly Python project to combine programming concepts with a simple, interactive game experience.
