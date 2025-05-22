# Python Loop Practice Problems

This document contains a set of 20 practice problems designed to help you master `for` and `while` loops in Python. Work through them to solidify your understanding of iterative constructs. Try to solve them yourself before looking for solutions!

## `for` Loop Problems

1.  **Print Numbers 1 to N:**
    Write a Python program that asks the user for an integer `N` and then prints all integers from 1 up to `N` (inclusive), each on a new line.

2.  **Sum of Even Numbers up to N:**
    Write a program that takes an integer `N` as input and calculates the sum of all even numbers from 1 to `N` (inclusive) using a `for` loop.
    *Example:* If `N` is 10, the even numbers are 2, 4, 6, 8, 10. The sum is `2+4+6+8+10 = 30`.

3.  **Print String Characters and Indices:**
    Write a program that takes a string as input from the user. Using a `for` loop and the `enumerate` function (or manual index tracking), print each character of the string along with its index.
    *Example:* If input is "py", output:
    ```
    0 p
    1 y
    ```

4.  **Count a Specific Character in a String:**
    Write a program that asks the user for a string and a specific character. Then, use a `for` loop to count and print how many times that specific character appears in the string (case-sensitive).

5.  **Multiplication Table (Custom Range):**
    Write a program that asks the user for a number, a starting multiplier, and an ending multiplier. Then, print the multiplication table for that number within the specified range.
    *Example:* Number=5, Start=3, End=6
    ```
    5 x 3 = 15
    5 x 4 = 20
    5 x 5 = 25
    5 x 6 = 30
    ```

6.  **Calculate Factorial:**
    Write a program that takes a non-negative integer `N` as input and calculates its factorial using a `for` loop. The factorial of `N` (denoted as `N!`) is the product of all positive integers less than or equal to `N`. (e.g., `5! = 5 * 4 * 3 * 2 * 1 = 120`). Remember `0! = 1`.

7.  **Create a List of Squares:**
    Given a list of numbers, e.g., `numbers = [1, 2, 3, 4, 5]`, write a program that uses a `for` loop to create a *new* list where each element is the square of the corresponding element in the original list. Print the new list.

8.  **Reverse a List (Manual Iteration):**
    Write a program that takes a list (e.g., `[10, 20, 30, 40, 50]`) and prints its elements in reverse order using a `for` loop. Do *not* use the built-in `list.reverse()` method or slicing `[::-1]`. (Hint: you might need to iterate using indices in reverse).

9.  **Find Max and Min in a List:**
    Write a program that iterates through a list of numbers (e.g., `[4, 1, 9, 7, 5, 2]`) using a `for` loop to find and print the maximum and minimum values in the list. Do not use the built-in `max()` or `min()` functions.

10. **Hollow Square Pattern:**
    Write a program that asks the user for an integer `N` (size of the square). Then, using nested `for` loops, print a hollow square pattern of asterisks (`*`) of size `N x N`.
    *Example:* If `N` is 5:
    ```
    *****
    * *
    * *
    * *
    *****
    ```

## `while` Loop Problems

11. **Countdown from N:**
    Write a Python program that asks the user for an integer `N` and then uses a `while` loop to print numbers from `N` down to 0 (inclusive), each on a new line.

12. **Sum of Digits of a Number:**
    Write a program that asks the user for an integer. Using a `while` loop, calculate and print the sum of its digits.
    *Example:* If input is `12345`, output is `1+2+3+4+5 = 15`.

13. **Reverse a Number:**
    Write a program that asks the user for an integer and then uses a `while` loop to print its digits in reverse order.
    *Example:* If input is `12345`, output is `54321`.

14. **Input Until "quit":**
    Write a program that continuously prompts the user to enter some text. The program should store each piece of input in a list. The loop should terminate when the user types "quit" (case-insensitive). After the loop, print all the inputs entered by the user (excluding "quit").

15. **Simple Password Validator:**
    Write a program that asks the user to enter a password. The program should keep asking for a password using a `while` loop until the user enters a password that is at least 8 characters long. Once a valid password is entered, print "Password accepted."

16. **Guess the Number Game:**
    Write a program where the computer "thinks" of a random number between 1 and 100 (you can use `random.randint(1, 100)`). The user has to guess the number. After each guess, the program should tell the user if their guess was "too high" or "too low". The game continues until the user guesses the correct number. Print a congratulatory message and the number of guesses taken.

17. **Fibonacci Sequence up to a Limit:**
    Write a program that generates and prints Fibonacci numbers using a `while` loop as long as the Fibonacci number is less than a certain limit (e.g., 100). The Fibonacci sequence starts with 0 and 1, and each subsequent number is the sum of the two preceding ones (0, 1, 1, 2, 3, 5, 8...).

18. **Power Calculation (No `**` or `pow()`):**
    Write a program that asks the user for two positive integers: a base and an exponent. Using a `while` loop, calculate `base` raised to the power of `exponent` (base<sup>exponent</sup>) without using the `**` operator or the `pow()` function. Print the result.

19. **Check if a Number is a Palindrome:**
    Write a program that asks the user for an integer and uses a `while` loop to check if the number is a palindrome. A palindrome number reads the same forwards and backward (e.g., 121, 353, 9009). Print whether the number is a palindrome or not. (Hint: you might need to reverse the number first).

20. **Simple Interest Calculator (Loop for Multiple Calculations):**
    Write a program that calculates simple interest (SI = P * R * T / 100).
    First, ask the user if they want to calculate simple interest (e.g., "yes" or "no").
    If "yes", prompt for principal (P), rate (R in %), and time (T in years). Calculate and display the SI.
    Then, ask the user if they want to perform another calculation. The program should loop as long as the user answers "yes".
