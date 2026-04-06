# 💸 Bill Splitter

A Python command-line tool that calculates how much each person owes
after splitting a restaurant bill among friends, including tip.

## Features

- Splits the bill among any number of friends
- Calculates tip as a percentage of the subtotal
- Displays a clean, itemised bill summary
- Accepts any number of bill items

## How to Run

```bash
python bill_splitter.py
```

## Sample Output

```
===================================
        BILL SUMMARY
===================================
  Subtotal     : $198.83
  Tip          : $49.71
  Total        : $248.54
-----------------------------------
  Each person  : $62.13
===================================
```

## How It Works

1. Pass in the number of friends, tip percentage, and individual item costs
2. The program calculates the subtotal, tip, and total
3. Divides the total equally and displays a formatted breakdown

## What I Learned

- Python functions with `*args` for variable number of inputs
- f-strings for formatted currency output
- Separating logic from display using multiple functions
- The `if __name__ == "__main__"` pattern

## Author

Harshwardhan Kumar Paswan
