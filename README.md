# Word Guessing Game

This is a Python program for a word guessing game where the player tries to guess a secret word by guessing letters or the entire word. The game will continue until the player correctly guesses the word or runs out of lives.

## Prerequisites

- Python 3.x installed on your system.

## How to Play

1. Clone the repository or download the source code.
2. Open a terminal or command prompt in the directory where the source code is saved.
3. Run the command `python word_guessing_game.py`.
4. The game will start by displaying a clue with question marks representing the unknown letters of the secret word and the number of lives remaining.
5. Enter a letter or the entire word to guess the secret word.
6. If you correctly guess the entire word, the game ends and you win.
7. If you guess a correct letter, the clue will be updated with the guessed letter.
8. If you guess an incorrect letter, the number of lives will decrease, and you will be prompted to guess again.
9. If you run out of lives, the game ends, and you lose.

## Program Flow

1. The program imports the random module to randomly choose a word from a list of words.
2. It defines the number of lives (initially set to 3) that the player has.
3. It creates a list of words to choose from.
4. It uses the random.choice() function to choose a secret word from the list.
5. It creates a list of question marks, representing the unknown letters of the secret word.
6. It sets a heart symbol for use in displaying the remaining lives.
7. It sets a boolean variable to indicate whether the player has guessed the word correctly.
8. It defines a function called update_clue() that takes a guessed letter, the secret word, and the clue list, and updates the clue list with the guessed letter if it matches a letter in the secret word.
9. It uses a while loop to allow the player to continue guessing until they have used up all their lives or correctly guessed the secret word.
10. It displays the current clue and the number of lives remaining in each iteration of the loop.
11. It prompts the player to guess a letter or the entire word.
12. If the player correctly guesses the entire word, the guessed_word_correctly variable is set to True, and the game ends.
13. If the player guesses a correct letter, the update_clue() function is called to update the clue list with the guessed letter.
14. If the player guesses an incorrect letter, a message is printed, and they lose a life.
15. If the player runs out of lives, the game ends, and a message is printed showing the secret word.
16. If the player correctly guesses the secret word, a message is printed showing the secret word and informing them that they have won.

## License

This program is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This program was written and assisted by ChatGPT, a large language model trained by OpenAI based on the GPT-3.5 architecture.

