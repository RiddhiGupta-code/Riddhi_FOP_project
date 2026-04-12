# Riddhi_FOP_project
A simple interactive Rock Paper Scissors Lizard Spock game built in C using raylib. It features a graphical interface, keyboard-based input, and score tracking for two players. This project demonstrates basic game loops, rendering, and user interaction in a fun and engaging way.
## Features
- GUI using raylib
- Keyboard controls
- Score system

## How to Run
- Compile using gcc with raylib
- Run the executable

## Tech Used
- C Language
- Raylib
## Test Cases

| Test Case | Player 1 Input | Player 2 Input | Expected Output |
|----------|---------------|---------------|----------------|
| TC1 | Rock | Scissors | Player 1 Wins |
| TC2 | Paper | Rock | Player 1 Wins |
| TC3 | Scissors | Paper | Player 1 Wins |
| TC4 | Lizard | Spock | Player 1 Wins |
| TC5 | Spock | Scissors | Player 1 Wins |
| TC6 | Rock | Rock | Draw |
| TC7 | Paper | Scissors | Player 2 Wins |
| TC8 | Invalid Key | Any | Error / No Change |

| Test Case | Scenario | Expected Output |
|----------|---------|----------------|
| TC9 | Rapid key press (multiple keys quickly) | Only one input is registered |
| TC10 | No key pressed | Game waits for input, no crash |
| TC11 | Window close button clicked | Game exits safely |
| TC12 | Long gameplay (multiple rounds) | Scores update correctly without reset |
| TC13 | Invalid key press (e.g., X, Z) | No action taken |
| TC14 | Same key pressed by both players | Draw is declared |
| TC15 | Game running for long time | No lag or crash |
| TC16 | Screen visibility / text clarity | Text is readable on white background |
| TC17 | Window resizing (if allowed) | UI remains stable (or fixed size maintained) |
| TC18 | Keyboard not responding momentarily | Game continues without crashing |
