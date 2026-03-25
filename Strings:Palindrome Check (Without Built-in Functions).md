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
