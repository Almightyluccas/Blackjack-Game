# Python Blackjack Game

This Python program simulates a blackjack game. The code consists of several classes which model the elements of the game: `Card`, `Deck`, `Hand`, and `Game`.

## Classes

### `Card`

The `Card` class represents a single card with a suit and rank.

### `Deck`

The `Deck` class represents a deck of cards. It creates a standard 52-card deck, can shuffle the deck, and deal cards from it.

### `Hand`

The `Hand` class represents a player's hand of cards. It can add cards to the hand, calculate the value of the hand, check for blackjack (a hand value of 21), and display the hand.

### `Game`

The `Game` class controls the game flow. It handles player input, checks for winning conditions, and outputs the game results.

## Gameplay

Once the game is initiated, you'll be asked how many games you want to play. After entering a valid number, the game will begin.

You'll be dealt two cards and so will the dealer. The dealer's first card will be hidden. You can then choose to 'Hit' (draw another card) or 'Stand' (stick with the cards you have). The goal is to get as close to 21 as possible without going over.

Once you're finished drawing cards, the dealer will draw cards until they reach a hand value of 17 or more. At this point, the hand values are compared, and the game winner is determined.

The game will repeat for the number of times you specified at the start.

## Running the Game

To run the game, ensure that you have Python installed, navigate to the directory containing the game file, and execute the following command in your terminal:

```bash
python blackjack.py
#Please replace `blackjack.py` with the actual name of your Python script if you change it
```
### Enjoy Playing!
