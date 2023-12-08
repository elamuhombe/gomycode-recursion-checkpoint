# Palindrome Checker Algorithm

This algorithm checks whether a given word is a palindrome using two counters.

## Table of Contents
- [Introduction](#introduction)
- [Algorithm Overview](#algorithm-overview)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This algorithm is designed to determine if a given word is a palindrome. It employs two counters to compare characters from both ends of the word towards the center.

## Algorithm Overview

The algorithm works as follows:
1. Initialize variables, including two counters (`i` and `j`) and the length of the word.
2. Read the input word.
3. If the length of the word is less than or equal to 1, the word is considered a palindrome, and the algorithm returns `TRUE`.
4. Use two counters (`i` and `j`) to compare characters at symmetric positions in the word, moving towards the center.
5. If the loop completes successfully (i.e., `i` becomes greater than `j`), the word is a palindrome, and the algorithm returns `TRUE`; otherwise, it returns `FALSE`.

## Usage

You can use this algorithm to check if a given word is a palindrome. Simply pass the word as input, and the algorithm will return `TRUE` if it's a palindrome and `FALSE` otherwise.

```pascal
result := check_palindrome_with_two_counters(word)

## License
The project is licensed under my name "Elaine Muhombe"
