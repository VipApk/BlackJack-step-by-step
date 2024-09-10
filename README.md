# Blackjack Game

## Overview
This is a console-based Blackjack game implemented in C++. The game can be played with multiple players and a dealer. Each player bets using a starting balance, and the game continues until only one player has all the balance. Players are eliminated when their balance hits $0, and they can no longer participate in the game.

## Features
- **Deck of Cards**: Standard 52-card deck with four suits (Hearts, Diamonds, Clubs, Spades) and thirteen ranks (Ace, 2-10, Jack, Queen, King).
- **Multiple Players**: Supports multiple human players playing against the dealer.
- **Betting System**: Each player starts with a balance of $1000 and places bets before each round.
- **Elimination**: Players are eliminated when their balance reaches $0.
- **Game Continuation**: The game continues until only one player has a positive balance.
- **Dealer AI**: The dealer hits until their hand value reaches at least 17.
- **Player Control**: Players can choose to hit or stand during their turn.
- **Hand Display**: Hands are displayed in a column format for easy comparison between players.

## Usage
1. **Start the Game**: The program will prompt you to press Enter to start.
2. **Input Player Names**: Enter names for each player when prompted.
3. **Gameplay**: Players will select their bet, be dealt two cards each, and the dealer will also receive two cards. Players can choose to hit or stand during their turn.
4. **Results**: After all players have completed their turns, the dealer will play according to the rules. The game will then display results and determine the winner based on hand values.

## Controls
- **Hit**: Enter 'h' when prompted to take another card.
- **Stand**: Enter 's' to keep your current hand and end your turn.

## Example
```
 Welcome to Blackjack!
Press Enter to start...

Enter the number of players: 2
Enter name for player 1: Alice
Enter name for player 2: Bob

=== New Round ===

Alice, you have $1000. Enter your bet: 100
Bob, you have $1000. Enter your bet: 200

Dealing cards...
Alice's hand:
Card 1: 7 of Hearts
Card 2: 9 of Clubs
Total value: 16

Bob's hand:
Card 1: King of Spades
Card 2: 8 of Diamonds
Total value: 18

Dealer's hand:
Hidden card
Card 2: 5 of Diamonds

Alice, do you want to hit (h) or stand (s)? h
Alice's hand:
Card 1: 7 of Hearts
Card 2: 9 of Clubs
Card 3: 4 of Spades
Total value: 20

Alice, do you want to hit (h) or stand (s)? s

Bob, do you want to hit (h) or stand (s)? s

Dealer's turn.
Dealer's hand:
Card 1: King of Clubs
Card 2: 5 of Diamonds
Total value: 15
Dealer hits.
Dealer's hand:
Card 1: King of Clubs
Card 2: 5 of Diamonds
Card 3: 7 of Hearts
Total value: 22
Dealer busted!

Alice's result: You win!
Alice's new balance: $1100
Bob's result: You win!
Bob's new balance: $1200
             
```
