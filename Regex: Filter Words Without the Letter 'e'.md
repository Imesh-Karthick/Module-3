# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
#Add code here

import re

l1 = []

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

for i in items:

    if not re.search(r"e", i):
    
        l1.append(i)

print(l1)
## Output
<img width="228" height="105" alt="image" src="https://github.com/user-attachments/assets/eed3e15b-eb76-42d0-b964-f2e24c7d2f12" />


## Result
Thus the program was successfully executed and obtained the result.
