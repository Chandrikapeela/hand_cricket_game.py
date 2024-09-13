
# Hand Cricket Game

## Overview

Hand Cricket is a text-based game where two players compete against each other in a simulated cricket match. Players can choose to bat or bowl, and the game follows the standard rules of cricket to determine the winner. This Python script allows users to input various parameters, play through multiple overs, and see the final scores.

## Features

- **Toss**: A coin toss determines which player will choose to bat or bowl first.
- **Player Choices**: Players can select to bat or bowl first based on the toss result.
- **Difficulty Levels**: Choose a difficulty level that affects gameplay.
- **Gameplay**: Each player takes turns batting and bowling over several overs.
- **Score Tracking**: The game tracks runs scored and wickets lost for each player.
- **Winner Determination**: At the end of the game, the player with the highest score is declared the winner.

## Installation

1. **Download or Clone the Repository**

   Download the source code as a ZIP file or clone the repository using Git:
   ```bash
   git clone https://github.com/chandrikapeela/hand-cricket.git
   ```

2. **Navigate to the Project Directory**

   Change to the project directory:
   ```bash
   cd hand-cricket
   ```

3. **Run the Script**

   Execute the script using Python:
   ```bash
   python hand_cricket.py
   ```

## Usage

1. **Start the Game**:
   - Run the script in your terminal or command prompt.

2. **Enter Game Parameters**:
   - Input the number of overs (1-10).
   - Participate in a coin toss to decide who chooses to bat or bowl first.
   - Choose to bat or bowl based on the toss result.

3. **Play the Game**:
   - Players will alternate between batting and bowling.
   - For each ball, choose a shot (1-6) if batting or a delivery (1-6) if bowling.
   - The game will display the score and wickets left after each ball and over.

4. **View Results**:
   - At the end of the game, the final scores and winner will be displayed.

## Example Interaction

Here is an example of how the game interaction might look:

```
Welcome Hand Cricket
You will be playing against another player
Enter the number of overs (1-10): 5
Toss time!
Choose heads (1) or tails (2): 1
It's Heads!
Player 1 won the toss!
Player 1, choose 1 to bat first, 2 to bowl first: 1
Player 2, choose 1 to bat first, 2 to bowl first: 2

Match Summary
=============
Overs: 5

Over 1, Player 1: 10 wickets left, Player 2: 10 wickets left
Player's turn - Batting
Over 1, Ball 1: Enter your shot (1-6): 4
Over 1, Ball 1: Player 2, choose 1 to bat, 2 to bowl: 2
You chose 4, Opponent chose 3
Player's score is 4

... (additional interaction)

Match Result
============
Player 1's score = 50
Player 2's score = 45
Player 1 won
Thank you for playing and have a good day :)
```

## Code Explanation

- **Function: `main()`**
  - Manages game flow, including user input and game setup.
  
- **Function: `toss()`**
  - Handles the coin toss to determine the first move.

- **Function: `play_game(overs, player1_choice, player2_choice, difficulty)`**
  - Manages the main gameplay including turns, runs, and wickets.

- **Function: `user_turn(player_score, player_wickets, player_choice, over)`**
  - Handles the player's turn for either batting or bowling.

- **Function: `display_scoreboard(player1_score, player2_score, over)`**
  - Displays the current score and wickets status.

- **Function: `who_won(player1_score, player2_score)`**
  - Determines and displays the match result.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, please contact peelachandrika@gmail.com

---
