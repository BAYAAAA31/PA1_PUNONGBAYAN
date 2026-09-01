# ECE 2112: Advanced Computer Programming and Algorithms

### Experiment 1: Introduction to Python Programming

**Student Name:** Punongbayan, AJ Andriz J. **Section:** 2ECE-A **Date Submitted:** September 1, 2026

## I. Objectives

1. use basic Python functions, operators, and string operations.
2. manipulate strings using indexing, slicing, and built-in string methods.
3. apply sequence unpacking to manipulate the elements of a list.
4. construct simple Python functions that return a specified result.

## II. Instructions

Write a Python program in a Jupyter Notebook to solve each of the following problems.
* Use the exact function names specified in each problem.
* Place each problem in a separate, clearly labeled section of the notebook.
* Each function must return the required result unless printed output is explicitly requested.
* Do not use external Python libraries.
* Use only basic Python operations, string methods, slicing, and sequence unpacking. Loops and classes are not required.
* Test each function using the examples provided. Additional valid inputs may be used when grading the notebook.

## III. Programming Problems

**A. WORD ROTATION PROBLEM**

Create a function named rotate_word() that accepts a non-empty string. Move the first character of the string to the end while keeping all remaining characters in their original order. Preserve the capitalization of every character.

**Function format:** rotate_word(text)

**Examples:**
* rotate_word("python") -> "ythonp"
* rotate_word("logic") -> "ogicl"
* rotate_word("Code") -> "odeC"
* rotate_word("A") -> "A"

**Requirement:** Use string indexing or slicing to construct the returned string.

**B. USERNAME BUILDER PROBLEM**

Create a function named make_username() that accepts two strings: first name and last name. The function must:
1. convert all letters to lowercase.
2. remove all spaces from the first name.
3. remove all spaces from the last name.
4. join the processed first and last names using one period (.).

**Function format:** make_username(first_name, last_name)

**Examples:**
* make_username("Ada", "Lovelace") -> "ada.lovelace"
* make_username("Alan", "Turing") -> "alan.turing"
* make_username("Ana Maria", "De Leon") -> "anamaria.deleon"

**Requirement:** Use basic string methods and string concatenation. Return the completed username.

**C. BOOKEND SWAP PROBLEM**

Create a function named swap_bookends() that accepts a list containing at least two elements. Unpack the list into three variables:
* first - the first element.
* middle - a list containing everything between the first and last elements.
* last - the last element.

Using these variables, return a new list in which the first and last elements have exchanged positions.[cite: 1] The elements in `middle` must remain in their original order. Do not modify the input list.

**Function format:** swap_bookends(items)

**Examples:**[cite: 1]
* swap_bookends([1, 2, 3, 4, 5, 6]) -> [6, 2, 3, 4, 5, 1]
* swap_bookends(["red", "green", "blue"]) -> ["blue", "green", "red"]
* swap_bookends([8, 3]) -> [3, 8]

**Requirement:** Use extended sequence unpacking in the following form: first, *middle, last = items

## IV. Submission Requirements

Submit one Jupyter Notebook file (.ipynb) containing:
1. your name and section.
2. clearly labeled solutions for Problems A, B, and C.
3. the three required Python functions.
4. executed test cells showing the expected output for the provided examples.

The notebook must execute from beginning to end without errors.




