# Python Blackjack Game

This is a simple command-line Blackjack game implemented in Python.

## Game Rules

- The deck is unlimited in size.
- There are no jokers.
- The Jack/Queen/King all count as 10.
- The Ace can count as 11 or 1.
- The cards in the list have equal probability of being drawn.
- Cards are not removed from the deck as they are drawn.
- The computer is the dealer.

## How to Play

1. Run the script in your Python environment.
2. You will be dealt two cards to start the game.
3. On each turn, you can choose to draw another card or pass.
4. The game ends when you choose to pass or your total score exceeds 21.
5. After you finish drawing cards, the computer draws cards until its score is 17 or more.
6. The player with the highest score wins, unless a player's score exceeds 21, in which case that player loses.

## Future Improvements

- **Add betting system**: Introduce a betting system where the player starts with a certain amount of money and places a bet at the beginning of each round. The player then wins or loses money based on the outcome of the game.
- **Splitting pairs**: Allow the player to split their hand if they are dealt a pair. This would essentially allow the player to play two hands in one round.
- **Doubling down**: Give the player the option to double their initial bet in exchange for committing to stand after receiving exactly one more card.
- **Insurance**: If the dealer's upcard is an Ace, offer the player the option of taking "insurance" before the dealer checks the hole card.
- **Multiple players**: Extend the game to allow multiple players to play against the dealer at the same time.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
