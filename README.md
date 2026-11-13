<p align="center">
  <img src="Text Slot Machine.png" alt="Slot Machine Banner" width="80%">
</p>

## 📖 What does it do?

This project is a fully functional, terminal-based **Text Slot Machine** game written entirely in Python. It allows users to simulate a classic slot machine experience directly from their command line.

Players can deposit a starting balance, choose how many lines they want to bet on (up to 3), and select their bet amount per line. The game generates a randomized 3x3 grid of symbols, calculates any winning rows based on weighted symbol values, and updates the player's balance dynamically until they choose to cash out.


## 🎯 Why I built this

I created this project as a fun, practical way to refine my core Python skills. While the premise is simple, building it required implementing several important programming concepts like Lists, Hashmaps and Nested Iterations:


## 🚀 Features

**Dynamic Betting System:** Choose between 1 and 3 lines to bet on, scaling risk and reward.

**Weighted Symbols:** Symbols have different rarities and payout multipliers, simulating real game mechanics.

**Robust Error Handling:** The program won't crash if you type a letter instead of a number—it politely asks you to try again.

**Continuous Play:** A clean while loop architecture that lets players spin repeatedly or cash out at any time.


## 🛠️ Technical Highlights

Here is a quick look at how the slot machine grid is generated and evaluated:

The get_slot_machine_spin function utilizes Python's random.choice alongside a dynamically managed list of available symbols to simulate spinning reels without replacing symbols in the same column.

The check_winnings algorithm efficiently iterates through a 2D array to verify matches across chosen lines, making it easy to scale the grid size in the future.


## 📥 How to Run Locally

If you want to try my Text Slot Machine out, then feel free to copy my code and run it on any source-code editor.
