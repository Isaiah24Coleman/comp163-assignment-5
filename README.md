# comp163-assignment-5
git add main.py
git commit -m "Challenge 1: Collatz sequence - while loop for unknown iterations"
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
print(1)  # End with 1
print("Steps:", steps)
git commit -m "Challenge 2: Prime checker - for loop for known range"
# === Challenge 2: Prime Number Checker ===
print("=== Challenge 2: Prime Number Checker ===")
n = int(input("Enter a number: "))

print(f"Testing divisors from 2 to {n-1}...")
is_prime = True
for i in range(2, n):
    if n % i == 0:
        is_prime = False
        print(f"{n} is not prime")
        print(f" (divisible by {i})")
        break

if is_prime:
    print(f"{n} is prime!")
Git Commit: "Challenge 3: Multiplication grid - nested loops for 2D data"
# === Challenge 3: Multiplication Table ===
print("=== Challenge 3: Multiplication Table ===")
print("Multiplication Table:")

print("     ", end="")
for i in range(1, 11):
    print(f"{i:4}", end="")
print()


for i in range(1, 11):
    print(f"{i:2}", end="  ")
    for j in range(1, 11):
        print(f"{i*j:4}", end="")
    print()
git push

