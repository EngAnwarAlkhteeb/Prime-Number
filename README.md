# Prime Checker 🌟

A Python script to determine if a given number is prime or not.

## 🚀 Usage

1. Run the Python script in a console or terminal.
2. Enter a number when prompted.
3. The program will reveal whether the number is prime or not.

## 💡 How it Works

The script uses a basic algorithm to check for divisibility, iterating up to the entered number. If the number is not divisible by any number in this range, it's considered prime.

## 🌐 Example

```python
def prime_checker(number):
    is_prime = True
    for i in range(2, number):
        if number % i == 0:
            is_prime = False
    if is_prime:
        print(f"{number} is a prime number.")
    else:
        print(f"{number} is not a prime number.")

# Test the function with different numbers
input_user = int(input("Enter a number: "))
prime_checker(number=input_user)
