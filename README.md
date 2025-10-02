# comp163-assignment-5
git add main.py
git commit -m "Challenge 1: Collatz sequence - while loop for unknown iterations"

git commit -m "Challenge 2: Prime checker - for loop for known range"
Git Commit: "Challenge 3: Multiplication grid - nested loops for 2D data"
# Assignment 5: Loop Challenges Documentation

## Loop Choices & Rationale

### Challenge 1: Collatz Conjecture
- **Loop Type Chosen:** `while` loop
- **Reason:** The Collatz sequence requires repeatedly applying a rule to a number until it becomes 1. The number of iterations isn't known beforehand, so a `while` loop is ideal for this kind of open-ended repetition.

### Challenge 2: Prime Number Checker
- **Loop Type Chosen:** `for` loop
- **Reason:** To check if a number is prime, you test divisibility by every integer in a known range (from 2 up to the number minus one). Since the range is predetermined, a `for` loop is best suited for this task.

### Challenge 3: Multiplication Table
- **Loop Types Chosen:** Nested `for` loops
- **Reason:** Generating a multiplication table requires iterating over two known ranges (rows and columns). Nested `for` loops efficiently handle this predictable, grid-like structure.

---

## Solution Explanations

### Collatz Conjecture
- Prompts the user for a starting number.
- Uses a `while` loop to generate the sequence, applying the Collatz rules:
  - If even, divide by 2.
  - If odd, multiply by 3 and add 1.
- Counts and displays the number of steps taken until reaching 1.

### Prime Number Checker
- Prompts the user for a number.
- Uses a `for` loop to test divisibility by all numbers from 2 up to (but not including) the input.
- Declares the number as prime if no divisor is found; otherwise, marks it as not prime.

### Multiplication Table
- Uses two nested `for` loops to print rows and columns from 1 to 10.
- Formats and displays the multiplication table as a grid.

---

## AI Assistance

- Parts of the code and documentation were written and reviewed with the help of GitHub Copilot and ChatGPT, which suggested loop structures, formatting, and explanations.

---

## Final Git Commands

To save this documentation, run:
```bash
git add README.md
git commit -m "Add loop design documentation"
```


