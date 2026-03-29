# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

#Add code here

numbers = [1, 2, 3, 4, 5]

print(sum(numbers))
## Output
<img width="177" height="113" alt="image" src="https://github.com/user-attachments/assets/3df1b9a2-ba57-437b-8150-d67b7fef3a9b" />


## Result
Thus the program was successfully executed and obtained the result.


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


# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
#Add Code Here

def remove(s):

    n = int(input())
    
    a = ""
    
    for i in range(len(s)):
    
        if i != n:
        
            a += s[i]
    
    return a

string = input()

print(remove(string))

## Output
<img width="268" height="190" alt="image" src="https://github.com/user-attachments/assets/092dd613-c6b1-4731-84de-58c3909a15f2" />


## Result
Thus the program was successfully executed and obtained the result.



# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

#Add code here

s = "google"

rev = s[::-1]

if s == rev:

    print("Palindrome")

else:

    print("Not Palindrome")

## Output
<img width="256" height="113" alt="image" src="https://github.com/user-attachments/assets/b7cf2778-a06b-49d4-9c5e-65fb22106664" />


## Result
Thus the program was successfully executed and obtained the result.



# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
#Add code here

x = ('a', 'n', 5, 8, 'z')

print('n' in x)

print(8 in x)

## Output
<img width="211" height="134" alt="image" src="https://github.com/user-attachments/assets/9f845109-7b7e-439c-96ce-80f6edbbe5bc" />


## Result
Thus the program was successfully executed and obtained the result.
