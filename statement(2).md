# Project Statement — Space Quiz Adventure

## 1. Problem Statement

Students who are new to programming need practical projects that help them use different programming concepts together. A basic command-line quiz has limited interaction and does not demonstrate features such as graphical interfaces, event handling, timers, file storage, and modular programming in one application. **Space Quiz Adventure** addresses this by providing a simple educational desktop game built around space and astronomy questions.

## 2. Proposed Solution

**Space Quiz Adventure** is a desktop quiz application developed in Python using Tkinter. The player first enters their name and then progresses through three levels containing multiple-choice questions about space. The player starts with three lives, and each question has a 15-second time limit. Correct answers increase the score, while incorrect answers or unanswered questions after the timer expires reduce one life. Once the game is completed, the final score is stored in a local text file.

## 3. Scope

The project includes:

- Desktop-based graphical quiz interaction
- Three levels of astronomy-related questions
- Timer and life tracking
- Score calculation
- Saving scores in a local text file
- Basic testing and validation
- Modular implementation using Python

The current version is designed to work locally and does not provide online multiplayer, database servers, user accounts, cloud storage, or other network-based services.

## 4. Target Users

The application is mainly intended for:

- Students who are learning Python
- Beginners exploring GUI programming
- Students with an interest in space and astronomy
- Users looking for a short and educational quiz game

## 5. High-Level Features

1. Player name entry
2. Graphical quiz screen
3. Three difficulty levels
4. Four multiple-choice answers for each question
5. Three player lives
6. 15-second countdown for each question
7. Scoring based on the current level
8. Saving scores through a text file
9. Play Again and Exit options
10. Basic project validation tests

## 6. Functional Requirements

- The application should take the player's name and check that it is valid.
- The application should display one question along with four possible answers at a time.
- The quiz should contain three different levels.
- The game should maintain a total of three lives for the player.
- Each question should have a 15-second countdown.
- The score should be calculated according to the level being played.
- The game should move to the appropriate question or level based on the player's progress.
- The final score should be stored in `scores.txt`.
- After the game ends, the player should be able to start again or close the application.

## 7. Non-Functional Requirements

- **Usability:** The interface, controls, and game information should be simple and easy to follow.
- **Performance:** The application should respond smoothly to user actions.
- **Reliability:** Lives, levels, scores, and timer updates should work consistently throughout the game.
- **Maintainability:** The code should be organized into separate modules with clear responsibilities.
- **Resource efficiency:** The application should run locally using Python's standard libraries.
- **Error handling:** Invalid or empty player names should be prevented, and missing score files should be handled safely.

## 8. Main Modules

| Module | Responsibility |
|---|---|
| `main.py` | Launches the application |
| `game.py` | Manages the GUI, game flow, timer, lives, levels, and scoring |
| `questions.py` | Contains the questions for all three levels |
| `score.py` | Handles saving and reading player scores |
| `utils.py` | Provides reusable helper functions and ASCII artwork |
| `test_project.py` | Performs basic project validation tests |

## 9. Workflow

```text
Start Application
       ↓
Enter Player Name
       ↓
Check Player Name
       ↓
Level 1 → Show Question → Answer / Timeout
       ↓
Update Score or Lose Life
       ↓
Level 2
       ↓
Level 3
       ↓
Game Completed / Game Over
       ↓
Save Score
       ↓
Play Again or Exit
```

## 10. Expected Learning Outcomes

By developing this project, students can gain practical experience with Python functions, classes, lists, dictionaries, conditional statements, loops, modules, file handling, Tkinter GUI development, event-driven programming, timer events, input validation, and basic software testing.
