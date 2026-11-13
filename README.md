<p align="center">
  <img src="Text Slot Machine.png" alt="Slot Machine Banner" width="100%">
</p>


## 📖 What does it do?

This project is a fully functional, terminal-based Slot Machine game written entirely in Python. It allows users to simulate a classic slot machine experience directly from their command line.

Players can deposit a starting balance, choose how many lines they want to bet on (up to 3), and select their bet amount per line. The game generates a randomized 3x3 grid of symbols, calculates any winning rows based on weighted symbol values, and updates the player's balance dynamically until they choose to cash out.

## 🎯 Why I built this

I created this project as a fun, practical way to refine my core Python skills. While the premise is simple, building it required implementing several important programming concepts that are highly relevant in professional software development:

Input Validation: Ensuring users only enter valid data types and amounts (e.g., preventing negative bets or string inputs where integers are expected).

Algorithm Logic: Dynamically generating a grid and accurately checking across matrix rows for matching symbols.

State Management: Keeping track of the user's balance accurately across multiple loops and varying bet sizes.

## 🚀 Features

Dynamic Betting System: Choose between 1 and 3 lines to bet on, scaling risk and reward.

Weighted Symbols: Symbols have different rarities and payout multipliers, simulating real game mechanics.

Robust Error Handling: The program won't crash if you type a letter instead of a number—it politely asks you to try again.

Continuous Play: A clean while loop architecture that lets players spin repeatedly or cash out at any time.

## 💻 See it in Action

Note: Here is a look at the code and the game being played inside the VSCode terminal!

## 🛠️ Technical Highlights

Here is a quick look at how the slot machine grid is generated and evaluated:

The get_slot_machine_spin function utilizes Python's random.choice alongside a dynamically managed list of available symbols to simulate spinning reels without replacing symbols in the same column.

The check_winnings algorithm efficiently iterates through a 2D array (list of lists) to verify matches across chosen lines, making it easy to scale the grid size in the future.

## 📥 How to Run Locally

If you'd like to try spinning the reels yourself, you can run this project in just a few seconds!

Clone the repository:

git clone https://github.com/YourUsername/Your-Repo-Name.git


Navigate to the directory:

cd Your-Repo-Name


Run the Python file:

python main.py
