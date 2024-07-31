# 🔐 Password Generator
This repository contains a Python script for generating strong and random passwords. The project is designed to provide two levels of password generation complexity: Easy and Hard.

## Project Overview
The program prompts the user to specify the number of letters, symbols, and numbers for the password. Based on these inputs, it generates a password according to the selected level of complexity.

## Instructions
The program will ask:

__How many letters would you like in your password?__

__How many symbols would you like?__

__How many numbers would you like?__

The goal is to take these inputs and generate a random password using Python lists and loops.

## Easy Version (Step 1)
In the easy version, the password is generated in a sequence. For example, if the user wants:

4 letters
<br>
2 symbols
<br>
3 numbers

The password might look like this: wgdx$*935

Here, all letters are grouped together, followed by symbols, and then numbers.

## Hard Version (Step 2)
In the hard version, the generated password does not follow a specific pattern. For example, the password might look like this: x$d23g*h9

The characters (letters, symbols, and numbers) are shuffled to ensure that each generated password is unique and random every time.

## Run the program
**View easy version code** - [password_generator_easy.py](password_generator_easy.py)
<br>
__View hard version code__ - [password_generator_hard.py](password_generator_hard.py)