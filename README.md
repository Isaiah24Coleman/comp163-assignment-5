# comp163-assignment-5
#Git Commit: "Challenge 1: Collatz sequence - while loop for unknown iterations"
# === Challenge 1: Collatz Conjecture ===
print("=== Challenge 1: Collatz Conjecture ===")
num = int(input("Enter starting number: "))
print("Sequence:")

steps = 0
while num != 1:
    print(num, end=" ")
    if num % 2 == 0:
        num //= 2
    else:
        num = 3 * num + 1
    steps += 1
print(1)  # Final 1 in the sequence
print("\nSteps:", steps)
