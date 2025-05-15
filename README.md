# Card Game Poker Detector 🎴🃏

A console-based Python game that simulates a card draw and detects poker hands using various sorting algorithms.

## 🧠 Features

- Customizable hand size (3 to 15 cards)
- User chooses sorting algorithm per round:
  - Heap Sort
  - Binary Insertion Sort
  - Merge Sort
  - One custom sorting algorithm (e.g., Quick Sort)
- Poker hand detection:
  - One Pair, Two Pair, Three of a Kind, Straight, Flush, Full House,  
  Four of a Kind, Straight Flash, Royal Flush.
- Console interface, looped gameplay
- Bonus: (To be defined)

## 🛠️ Project Structure

```text
card-game/
├── main.py            # Entry point of the program
├── card.py            # Card class
├── deck.py            # Deck class
├── pokerHands.py      # Poker hand detection
├── gamePlay.py        # Main game logic
├── sorting/           # Sorting algorithms
│   ├── heapsort.py
│   ├── mergesort.py
│   ├── binary_insert.py
│   └── custom_sort.py
├── report.pdf         # Final report (for submission)
└── README.md          # This file
