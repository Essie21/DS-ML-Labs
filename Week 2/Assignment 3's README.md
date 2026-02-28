## Python Data Structures: Strings and Control Flow


## 🎯 Objectives

1. Master string operations and manipulation techniques in Python
2. Learn built-in string methods for case conversion and checking
3. Understand string validation methods (isdigit, isalpha, islower, isupper, etc.)
4. Implement string splitting and joining operations
5. Practice string replacement and substring detection


## 🛠️ Tools Used

- **Python 3**
- **Jupyter Notebook**
- **Anaconda Navigator**



## 📋 Step-by-Step Process

#### Step 1: Set Up Environmeent

- Opened Jupyter Notebook in my IDE
- Ensured Python 3.x is installed
- Created a new notebook file for Assignment 3


#### Step 2: Implement Arithmetic Operators (with x=20, y=4)

- Addition (+) operation  resulting in 24
- Subtraction (-) operation resulting in 16
- Multiplication (*) using asterisk notation resulting in 80
- Division (/) with forward slash resulting in 5.0
- Floor Division (//) to get whole numbers without decimals
- Modulo (%) operation to find remainders
- Exponential (**) using double asterisks for power calculations


#### Step 3: Apply Comparison Operators

- Greater than (>) comparison operations
- Less than (<) comparison operations
- Equal to (==) checking value equality
- Greater than or equal to (>=) compound comparisons
- Less than or equal to (<=) range checking
- Not Equal to (!=) inequality verification
- Observed Boolean outputs (True / False)


#### Step 4: Master Logical Operators

- AND operator (both conditions must be true)
- OR operator (at least one condition must be true)
- NOT operator (negates the condition set)


#### Step 5: Practice Assignment Operators

- Simple assignment (=) to assign values
- Addition assignment (+=) to add and assign
- Subtraction assignment (-=) to subtract and assign
- Multiplication assignment (*=) to multiply and assign
- Division assignment (/=) for division results
- Floor division assignment (//=) for whole number division
- Exponentiation assignment (**=) for power operations


#### Step 6: Explore Bitwise Operations

- AND (&) operator for binary AND operations
- OR (|) operator for binary OR operations
- Exclusive OR (^) for XOR calculations
- NOT (~) operator to negate binary digits
- Left Shift (<<) to shift bits left and multiply by 2^n
- Right Shift (>>) to shift bits right and divide by 2^n
- Converted between decimal and binary representations


#### Step 7: Apply Membership Operators

- IN operator to check if value exists in a sequence
- NOT IN operator to verify absence of values
- Works with strings, lists, tuples, sets, and dictionaries
- Returns boolean True/False values
- Useful for validation and membership testing


#### Step 8: Understand Identity Operators

- IS operator to check object identity in memory
- IS NOT operator to verify different memory locations
- Compares memory addresses, not values



## 💻 Commands Executed
```
#### Arithmetic Operators
- x = 20, y = 4
- print(x + y)  # 24
- print(x - y)  # 16
- print(x * y)  # 80
- print(x / y)  # 5.0
- print(x // y)  # 5
- print(x % y)  # 0 (remainder)
- x = 5, y = 3
- print(x ** y)  # 125

#### Comparison Operators
- x = 54, y = 77
- print(x > y)  # False
- print(x < y)  # True
- print(x == y)  # False
- print(x >= y)  # False
- print(x <= y)  # True
- print(x != y)  # True

#### Logical Operators
- x = 32, y = 21
- print(x > 30 and y < 25)  # True
- not (x < 32)  # True (negates false to true)

#### Assignment Operators
- x = 55  # Assign 55
- x += 78  # Adds 78, result 133
- x -= 23  # Subtracts 23
- x *= 3  # Multiplies by 3, result 30
- x /= 2  # Divides by 2, result 5.0
- x //= 3  # Floor divides, result 3
- x **= 3  # Exponentiates, result 8

#### Bitwise Operators
- x = 55 (Binary: 00110111)
- y = 70 (Binary: 01000110)

AND (&): x & y = 6 (Binary: 00000110)
OR (|): x | y = 119 (Binary: 01110111)
XOR (^): x ^ y = 113 (Binary: 01110001)
NOT (~): ~55 = -56 (Binary: 1 1 0 0 1 0 0 0)
LEFT SHIFT (<<): 55 << 2 = 220 (Add 2 zeros on right)
RIGHT SHIFT (>>): 55 >> 2 = 13 (Remove last 2 digits)

#### Membership Operators
- a = [1, 2, 3, 4, 5]
- print(2 in a)  # True (2 exists in list a)
- print(8 in a)  # False (8 not in list a)

#### Identity Operators
- a = [1, 2, 3, 4, 5]
- b = [1, 2, 3, 4, 5]
- print(a is b)  # False (different memory locations)
- print(a is not b)  # True (a and b occupy different memory)

```

## 📸 Results & Screenshots
All lab outputs have been executed successfully in Jupyter Notebook.

#### Case Conversions
![Case Conversions](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%20%203/Case%20Conversions.png?raw=true)

#### Validation Methods
![Validation Methods](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%20%203/Validation%20Methods.png?raw=true)

#### Split and Join
![Split and Join](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%20%203/Split%20and%20Join.pngraw=true)

#### String Replacement & Startswith
![String Replacement & Startswith](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%20%203/String%20Replacement%20and%20Startwith.png?raw=true)

##### Startswith & Endswith
![Startswith & Endswith](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%20%203/Startswith%20and%20Endswith.png?raw=true)



## 🧠 Lessons Learned

1. String Manipulation Mastery
- String operations are fundamental to text processing in Python.
- Methods like upper(), lower(), split(), and join() enable powerful text transformations.
- String validation methods (isdigit, isalpha, islower, isupper) provide boolean checks for conditional logic.
- Detection methods like startswith() and endswith() support pattern matching essential for data validation


  
2. Common Mistakes to Avoid

- Forgetting that isalpha() returns False if the string contains spaces
- Confusing split() delimiter behavior (it removes the delimiter)
- Using join() on non-iterable objects
- Assuming string methods modify the original string (they don't!)
- Overlooking case sensitivity in startswith() and endswith() checks

3. Best Practices

- Use descriptive variable names to distinguish original strings from processed versions
- Remember that strings are immutable—methods return new strings, never modify originals
- Chain string methods efficiently when performing multiple operations
- Use split() with appropriate delimiters based on your data structure
- Validate strings with isdigit(), isalpha() before processing assumptions

