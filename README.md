# Blackjack Game in C++

## Overview
Welcome to the **Blackjack Game** implemented in C++. This is a text-based version of the popular casino card game where players aim to beat the dealer by having a hand value closer to 21 without going over. 

### Game Features
- Play against a dealer controlled by the computer.
- Support for multiple players (up to 6).
- Ability to place bets, hit, stand, or double down.
- Real-time score tracking for each player.
- Proper handling of player busts and wins.
   
1. **Run the Game**:
   - After compiling, run the game with the command:
     ```bash
     ./blackjack
     ```

2. **Game Instructions**:
   - Upon starting the game, you will be prompted to enter the number of players (1-6). 
   - You will also be asked to input your name and the names of other players.
   - Each player will place a bet, and then the game will deal two cards to each player and the dealer.
   - Players take turns to either hit (take another card), stand (end their turn), or double down (double their bet and take one more card).
   - The dealer will reveal their hand and play according to standard Blackjack rules (hitting until they reach 17 or higher).

3. **Winning and Losing**:
   - Players win if their hand value is greater than the dealer's without going over 21.
   - If a player busts (hand value exceeds 21), they lose their bet.
   - If the dealer busts, all remaining players win.

## Card Values
- Number cards (2-10) are worth their face value.
- Jacks, Queens, and Kings are worth 10 points.
- Aces can be worth 1 or 11 points, depending on which value benefits the player most.

## Code Structure
- **Classes**:
  - `Card`: Represents a playing card with a suit and value.
  - `Deck`: Manages the deck of cards, including shuffling and dealing.
  - `Player`: Represents a player in the game, either a human player or the dealer.
  
- **Functions**:
  - `showPlayersHands`: Displays each player's hand and their total score, hiding the dealer's total until all cards are revealed.
  - `playBlackjackRound`: Conducts one round of the game, managing betting, card dealing, and player actions.
  - `isGameOver`: Checks if the game should end based on players' balances.
