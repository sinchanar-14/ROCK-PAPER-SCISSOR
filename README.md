# ROCK-PAPER-SCISSOR

*COMPANY NAME*:CODSOFT

*NAME*: SINCHANA R

*INTERN ID*:CS25RY56057

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 4 WEEKS

# Rock-Paper-Scissors Game

## Overview

The Rock-Paper-Scissors game is a classic hand game that has entertained players for generations. This implementation, created in Python, allows users to engage in a fun and interactive game against the computer. The game is simple yet engaging, making it suitable for players of all ages. The objective is straightforward: choose one of three options—rock, paper, or scissors—and compete against the computer's choice. The game incorporates basic programming concepts such as functions, loops, and conditionals, making it an excellent project for beginners looking to enhance their coding skills.

## Game Mechanics

### How to Play
The rules of Rock-Paper-Scissors are simple:
- Rock crushes scissors (rock wins).
- Scissors cuts paper (scissors win).
- Paper covers rock (paper wins).
- If both players choose the same option, the game results in a tie.

The game is played in rounds, and players can choose to continue playing until they decide to stop. The program keeps track of the score, displaying the number of wins for both the user and the computer after each round.

### User Interaction
The game begins with a welcoming message, inviting players to choose between rock, paper, or scissors. The user input is handled through the `get_user_choice()` function, which ensures that the input is valid. If the user enters an invalid choice, the program prompts them to try again until a valid option is selected.

### Computer Choice
The computer's choice is generated randomly using the `get_computer_choice()` function, which utilizes Python's `random.choice()` method to select one of the three options. This randomness adds an element of unpredictability to the game, making it more exciting for the player.

### Determining the Winner
The core logic of the game is encapsulated in the `determine_winner()` function. This function compares the user's choice with the computer's choice and determines the outcome based on the established rules. It returns a string indicating whether the result is a tie, a user win, or a computer win.

### Displaying Results
After each round, the results are displayed using the `display_result()` function. This function provides a clear summary of the choices made by both the user and the computer, along with the outcome of the round. The use of emojis (🎉 for user wins and 💻 for computer wins) adds a fun visual element to the output, enhancing the overall user experience.

### Scoring System
The game maintains a score for both the user and the computer, which is updated after each round based on the results. The current score is displayed after every round, allowing players to track their performance throughout the game. This scoring system encourages friendly competition and motivates players to improve their skills.

### Replay Option
At the end of each round, players are given the option to play again. The program prompts the user to input their choice, and if they decide not to continue, the final scores are displayed before the game ends. This feature allows for a seamless gaming experience, enabling players to engage in multiple rounds without restarting the program.

## Technical Details

The Rock-Paper-Scissors game is implemented using Python, showcasing fundamental programming concepts. The code is structured into several functions, each responsible for a specific aspect of the game. This modular approach enhances readability and maintainability, making it easier for developers to understand and modify the code.

### Code Structure
- **get_user_choice()**: Handles user input and ensures valid choices.
- **get_computer_choice()**: Randomly selects the computer's choice.
- **determine_winner()**: Compares choices and determines the winner.
- **display_result()**: Outputs the results of each round.
- **play_game()**: Manages the overall game flow, including scoring and replay options.

## Conclusion

The Rock-Paper-Scissors game is a delightful project that combines simplicity with engaging gameplay. It serves as an excellent introduction to programming concepts for beginners while providing an enjoyable experience for players. The implementation demonstrates how basic functions and control structures can be used to create an interactive application. Whether you're looking to practice your coding skills or simply enjoy a classic game, this Rock-Paper-Scissors implementation is a perfect choice. With its user-friendly interface and straightforward mechanics, it invites players to challenge themselves and have fun in the process.

*OUTPUT*:<img width="757" alt="Image" src="https://github.com/user-attachments/assets/df09d738-947e-4383-8867-ceda48c8c178" />
