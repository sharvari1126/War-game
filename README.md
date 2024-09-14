# War Card Game

## Description
This is a simple Python implementation of the card game **War**, where two virtual players battle automatically. Each player is dealt a deck, and the program simulates the game, showing the result after each round. If the two players draw the same card, a "war" is declared, adding an extra level of excitement. The game continues until all rounds are played, and the program announces the final winner.

## How the Game Works
1. A standard deck of 52 cards is shuffled and divided evenly between two players.
2. In each round, both players play the top card from their decks.
3. The player with the higher card wins the round and takes both cards.
4. If both cards have the same value, a **war** is declared:
    - In a war, each player draws seven more cards. The highest card drawn wins the war, and the winner takes all the cards.
    - The player with the higher face-up card wins all the cards in play.
5. The game ends when one player is out of cards.
6. After one player does not have enough cards to play, the game declares a winner.

## Features
- Automatic card shuffling, distribution, and gameplay.
- Tracks and displays the number of rounds.
- Declares a **war** when cards of equal value are played.
- Clear output showing the final result.

## Technologies Used
- Python 3.x

## Example output
**Round 1**  
**Round 2**  
**Round 3**  
**Round 4**  
**Round 5**  
**...**  
**Round 265**  
Player one out of cards. Game over!!  
PLAYER TWO WINS!!  
