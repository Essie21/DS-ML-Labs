## Python Data Structures: Operators


## 🎯 Objectives

1. Understand and implement various types of operators in Python
2. Master arithmetic operations and their applications
3. Learn comparison operators for boolean evaluations
4. Implement logical operators for complex condition handling
5. Explore bitwise operations at the binary level
6. Use Membership Operators to check value existence in sequences
7. Apply Identity Operators to compare object memory locations



## 🛠️ Tools Used

- **Python 3**
- **Jupyter Notebook**
- **Anaconda Navigator**



## 📋 Step-by-Step Process

#### Step 1: Set Up Environmeent

- Opened Jupyter Notebook in my IDE
- Ensured Python 3.x is installed
- Created a new notebook file for Assignment 2


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

#### Arithmetic Operators
![Arithmetic Operators](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Arithmetic%20Operators.png?raw=true)

#### Comparison Operators
![Comparison Operators](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Comparison%20Operators.png?raw=true)

#### Logical Operators
![Logical Operators](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Logical%20Operators.png?raw=true)

#### Assignment Operator
![Assignment Operator (1)](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Assignment%20Operator%20(1).png?raw=true)

![Assignment Operator (2)](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Assignment%20Operator%20(2).png?raw=true)

![Assignment Operator (3)](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Assignment%20Operator%20(3).png?raw=true)

#### Bitwise Operators
![Bitwise Operators (1)](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Bitwise%20Operators%20(1).png?raw=true)

![Bitwise Operators (2)](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Bitwise%20Operators%20(2).png?raw=true)

![Bitwise Operators (3)](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Bitwise%20Operators%20(3).png?raw=true)

![Bitwise Operators (4)](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Bitwise%20Operators%20(4).png?raw=true)

#### Membership Operators
![Membership Operators](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Membership%20Operators.png?raw=true)

#### Identity Operators
![Membership Operators](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%202/Identity%20Operators.png?raw=true)



## 🧠 Lessons Learned

1. Operator Types and Applications
- Arithmetic operators perform mathematical calculations and are fundamental for numerical computations.
- Comparison operators return boolean values, enabling conditional logic.
- Logical operators combine multiple conditions.
- Bitwise operators work directly with binary representations for advanced operations.
- Membership operators validate presence in collections, while identity operators verify object references in memory

  
2. Common Mistakes to Avoid

- Confusing assignment (=) with comparison (==)
- Using and/or instead of bitwise &/| operators
- Misunderstanding floor division vs regular division
- Attempting unsupported operations on incompatible data types
- Forgetting that bitwise operations work on binary representations
- Confusing == (equality) with is (identity) operators
- Assuming two lists with same values are the same object in memory

3. Best Practices

- Use appropriate operator types for specific tasks
- Understand operator precedence to avoid unexpected results
- Use parentheses for clarity in complex expressions
- Test operators with simple values before complex operations
- Use == for value comparison and is for object identity checks
- Leverage membership operators for cleaner, more readable code when     validating data presence
