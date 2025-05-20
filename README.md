# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
    numbers = [1, 2, 3, 4, 5]
    total = sum(numbers)
    print("Sum of all elements:", total)
    

## Output
![Screenshot 2025-05-19 204311](https://github.com/user-attachments/assets/fed0ad29-a774-4cfc-81a2-77e20e77274f)

## Result
Thus, the program is verified successfully.

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
      import re
      items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
      l1 = []
      for i in items:
          if not re.search(r"e", i):
              l1.append(i)
      print("Words without 'e':", l1)

## Output
![Screenshot 2025-05-19 204447](https://github.com/user-attachments/assets/1518d03e-404d-4c75-a248-6c784c9d2124)

## Result
Thus, the program is verified successfully.

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
    def remove(input_string):
        # Read the index to remove from the user
        n = int(input("Enter the index of the character to remove: "))
        
        a = ""  # Initialize new string
        
        # Iterate over the string by index
        for i in range(len(input_string)):
            if i != n:
                a += input_string[i]  # Append character if index != n
        
        return a
    user_string = input("Enter a string: ")
    
    result = remove(user_string)
    print("String after removal:", result)

## Output
![Screenshot 2025-05-19 204725](https://github.com/user-attachments/assets/6b952c37-fddd-4871-a0ad-15168587516e)

## Result
Thus, the program is verified successfully.

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
      s = "google"
      reversed_s = s[::-1]
      
      if s == reversed_s:
          print(f'"{s}" is a palindrome.')
      else:
          print(f'"{s}" is not a palindrome.')


## Output
![Screenshot 2025-05-19 204906](https://github.com/user-attachments/assets/1bb73684-e6df-40cd-b683-06aebba39b31)

## Result
Thus, the program is verified successfully.

# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
    x = ('a', 'b', 'n', 5, 8, 10)
    
    has_n = 'n' in x
    has_8 = 8 in x
    print("'n' exists in tuple:", has_n)
    print("8 exists in tuple:", has_8)

## Output
![Screenshot 2025-05-19 205036](https://github.com/user-attachments/assets/93cd54ef-accc-4e15-ae7f-7537e4c76d7a)

## Result
Thus, the program is verified successfully.
