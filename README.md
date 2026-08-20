# Two Sum Using Hashing

## 📌 Description

This Python program finds two numbers in a list whose sum is equal to a given target value.

It uses a Python dictionary as a hash table to efficiently find the required pair.

## 🐍 Language

Python

## 🧠 DSA Concept

- Hashing
- Dictionary
- Array/List
- Searching

## 💻 Example

### Input

Numbers:
[2, 7, 11, 15]

Target:
9

### Output

Pair found: 2 + 7 = 9

## ⚙️ How It Works

1. Store each number in a dictionary.
2. Calculate the required value using:
   `target - current_number`
3. Check whether the required value already exists.
4. If it exists, the pair is found.
5. Otherwise, store the current number and continue.

## 📂 File

`two_sum.py`

## 🎯 Purpose

This program demonstrates how hashing can be used to solve the Two Sum problem efficiently.

## 👩‍💻 Author

Nagasri
