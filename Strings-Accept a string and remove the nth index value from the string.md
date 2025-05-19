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
