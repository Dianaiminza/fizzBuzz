# FizzBuzz in C#

This is a simple implementation of the **FizzBuzz** problem in C#, demonstrating basic control flow and modulus operations. The program prints the numbers from 1 to 100 with the following rules:

- For numbers divisible by **3**, print `"Fizz"` instead of the number.
- For numbers divisible by **5**, print `"Buzz"` instead of the number.
- For numbers divisible by **both 3 and 5**, print `"FizzBuzz"` instead of the number.
- For all other numbers, print the number itself.

## How to Run

To run the **FizzBuzz** program, follow these steps:

1. **Clone the repository** to your local machine:

   ```bash
   git clone https://github.com/Dianaiminza/fizzbuzz.git

2. **Build and run the program:**

   ```bash
    dotnet build
    dotnet run

## Code Explanation
The program works as follows:

- A for loop runs from 1 to 100.
- For each number:
   - If divisible by both 3 and 5, it prints "FizzBuzz".
   - If divisible only by 3, it prints "Fizz".
   - If divisible only by 5, it prints "Buzz".
   - If neither, it prints the number itself.

