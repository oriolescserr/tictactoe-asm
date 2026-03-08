<p align="left">
   <a href="https://www.eps.udl.cat/ca/" target="_blank">
     <img src="https://os-gei-udl-2526-105012.github.io/course/figures/corporative/institute.png" width="150"/>
   </a>
</p>

# Practice 2 - Tic-Tac-Toe Game (Von Neumann Simulator)

**Subject:** Computer Architecture 2
**Degree:** 1st year of Computer Engineering (University of Lleida - Igualada Campus)
**Academic year:** 2024/25 — 2nd semester
**Student:** Oriol Escolà Serra
**Grade obtained:** 10/10
**Weight in subject:** 15%

## Objective

Develop a program in assembly language for the KIT Von Neumann Simulator, implementing the classic Tic-Tac-Toe game with keyboard and screen interaction, optimised to the highest level and meeting all mandatory and optional requirements.

## Installation and Execution

1. Download the simulator from the repository: https://github.com/jvilaplana/SimuladorVonNeumann.
2. Extract the ZIP file into a working folder.
3. Open and edit the `.ens` files with a text editor.
4. Compile the program:
```bash
   Ensambla.exe filename.ens
```
5. Run the simulator:
```bash
   VonNeuman.exe
```

## Game Features

- Automatic screen and keyboard buffer clearing at startup.
- Drawing of a 3x3 board with clear coordinates.
- Coordinate input from each player.
- Coordinate validation and occupied cell checking.
- Display of the corresponding symbol: X for player 1 and O for player 2.
- Checking for 3 in a row in all directions.
- End-of-game detection and full board detection.
- Personalised winner message.

### Extras Implemented

- Player name input at the start of the game.
- Option to play another round once the first one has ended, resetting all data.
- Highly commented code structured in modular procedures for easy reading and maintenance.
- Performance and code efficiency optimisation.

## Author

Oriol Escolà Serra
Computer Engineering Student
University of Lleida – Igualada Campus

## License

This project was developed for educational purposes.
Copying this code for academic submissions without prior authorisation is not permitted.
