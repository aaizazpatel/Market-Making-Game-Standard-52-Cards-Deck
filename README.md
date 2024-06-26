# Market-Making Game README

## Overview:
This Python script implements a market-making game using a standard 52-card deck. The game simulates market dynamics where players can choose to buy or sell based on bid and ask prices quoted by a market maker. The objective is to demonstrate understanding of market-making concepts through Python implementation.

## Game Rules:
1. The game utilizes a standard 52-card deck.
2. Cards from Ace to 10 have values of 1 to 10 respectively. Picture cards (J, Q, K) have values of 11, 12, and 13 respectively.
3. If the suit of the card is Spades or Clubs, the card's value is multiplied by 2.
4. If the suit of the card is Hearts or Diamonds, the card's value remains unchanged.
5. Each round consists of three cards, with only the first card shown initially.
6. The market-maker quotes bid and ask prices.
7. Players can choose to buy or sell from the market-maker after the price is quoted.
8. Quantity traded is 1 unit.
9. After the trade, the remaining two cards are revealed, and the fair value is calculated based on their values and suits.
10. Profit or loss is calculated for the trader based on the traded price and the fair value of the three cards.

## Code Breakdown:
- The script initializes card suits and ranks, creates a deck, and selects three random cards.
- The values and suits of the selected cards are determined, and the fair total value of the cards is calculated.
- The market maker quotes bid and ask prices with a spread.
- Players can input whether they want to buy or sell.
- After the trade, the remaining cards are revealed, and the fair value is displayed.
- Profit or loss is calculated based on the trade and fair value.

## Instructions:
1. Clone the repository to your local machine.
2. Ensure you have Python installed.
3. Run the Python script provided (market_making_game.py).
4. Follow the prompts in the terminal to see the first card and the market maker's quote.
5. Enter "B" to buy or "S" to sell.
6. View the remaining cards and the fair total value.
7. The script will display the profit or loss based on the trade.

## Notes:
- Players can experiment with different strategies to maximize profit or minimize loss based on market dynamics.
- The game provides a hands-on approach to understand market-making concepts in a simplified setting.

## Disclaimer:
This game is for educational purposes only and does not simulate real financial markets. It serves as a tool to grasp basic market-making principles through interactive gameplay.
