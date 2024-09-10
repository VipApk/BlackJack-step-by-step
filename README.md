Blackjack Game in C++
This is a console-based Blackjack game implemented in C++. The game can be played with multiple players and a dealer. Each player bets using a starting balance, and the game continues until only one player has all the balance. Players are eliminated when their balance hits $0, and they can no longer participate in the game.

Features
Multiple Players: Supports multiple human players playing against the dealer.
Betting System: Each player starts with a balance of $1000 and places bets before each round.
Elimination: Players are eliminated when their balance reaches $0.
Game Continuation: The game continues until only one player has a positive balance.
Dealer AI: The dealer hits until their hand value reaches at least 17.
Player Control: Players can choose to hit or stand during their turn.
Hand Display: Hands are displayed in a column format for easy comparison between players.
Rules
Blackjack Values:
Number cards (2-10) are worth their face value.
Face cards (Jack, Queen, King) are worth 10.
Aces can be worth either 1 or 11, depending on which value keeps the hand under or equal to 21.
Betting:
Players place a bet before each round.
If a player wins, they earn twice their bet.
If they tie with the dealer, they receive their bet back.
If they lose, they forfeit their bet.
Elimination: If a player's balance reaches $0, they are eliminated from the game and can no longer place bets or receive cards.
Game Over: The game ends when only one player has a positive balance, and that player is declared the winner.
