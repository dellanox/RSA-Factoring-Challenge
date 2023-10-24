PROJECT - RSA Factoring Challenge
---------------------------------

0. Factorize all the things!
----------------------------
Factorize as many numbers as possible into a product of two smaller numbers.


# RSA Factoring Challenge

The RSA Factoring Challenge is a computational task that involves factorizing a series of numbers into their prime components. In the context of RSA (Rivest-Shamir-Adleman) cryptography, the challenge is to find the prime numbers p and q when provided with their product, 'n'. This README provides an overview of the challenge and guidelines for tackling it.

## Objective

The primary objective of this challenge is to factorize given natural numbers into a product of two smaller numbers. While you can find factorization methods for general numbers, this challenge has specific requirements:

1. **Task 0: Factorize All the Things!**
    - Factorize natural numbers into two smaller numbers.
    - Numbers are provided in a file, with one number per line.
    - All numbers are valid natural numbers greater than 1.
    - No empty lines or extraneous spaces are present in the file.
    - The output format should be: "n = p * q," where p and q do not have to be prime numbers.
    - The order in which you work on the numbers is flexible.
    - Your program should run independently without external dependencies.
    - The program must complete factorization within a strict time limit of 5 seconds.

2. **Task 1: RSA Factoring Challenge**
    - An extension of Task 0 with more stringent conditions.
    - The prime factors p and q must always be prime numbers.
    - Each file contains only one number to factorize.
    - Your challenge is to find the prime factors of this number within the same 5-second time limit.
    
This challenge is a classic problem in cryptography, reflecting the significance of efficient prime factorization in the RSA encryption algorithm.

## Implementation

To accomplish this challenge, you can utilize various algorithms for factorizing numbers into their prime components. A simple example in Python is provided in the 'factors.py' script.

- The 'is_prime' function checks for primality.
- 'factorize_and_print' factorizes the numbers into p and q.
- The script reads numbers from a file and prints the factorization for each number.

This code serves as a basic example, and for factorizing large RSA numbers, you may need more advanced algorithms like Pollard's rho algorithm or the quadratic sieve. You might consider using optimized libraries or code to meet the 5-second time limit.

## Usage

To use the provided Python script, follow these steps:

1. Ensure you have Python installed on your system.

2. Run the script using the command:

