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


#### Step 2:  Explore Basic String Operations

- Assigned string values to variables
- Printed string variables to display output
- Verified case changes in output


#### Step 3: Implement String Case Conversion Methods

- upper() method to convert all letters to uppercase
- lower() method to convert all letters to lowercase
- Returned new strings without modifying originals


#### Step 4: Learn String Validation Methods

- isalpha() to check if all characters are alphabetic
- isdigit() to check if all characters are digits
- islower() to verify if all letters are lowercase
- isupper() to verify if all letters are uppercase
- Returns boolean True/False values for validation

#### Step 5: Master String Splitting & Joining Operations

- Used split() to break strings into lists
- Specified delimiters for custom splitting
- Applied join() to combine list elements into strings
- Specified separator between joined elements


#### Step 6:  Practice String Modification and Detection

- Implemented replace() for substring substitution
- Used startswith() to check string beginnings
- Applied endswith() to verify string endings
- Returns boolean values for conditional logic
- Tested various string patterns


## 💻 Commands Executed
```
#### Basic String Operations
- name_ = "ParoCyber LLC"
- print(name_)  # ParoCyber LLC

#### String Case Conversion
- name_ = "ParoCyber LLC"
- name_ = name_.upper()
- print(name_)  # PAROCYBER LLC

- name_ = name_.lower()
- print(name_)  # parocyber llc

#### String Validation Methods
- name_ = "ParoCyber LLC"
- result = name_.isalpha()
- print(result)  # False (contains space and numbers)

- Name_ = "ParoCyber LLC"
- result = Name_.isdigit()
- print(result)  # False (not all digits)

- result = Name_.islower()
- print(result)  # False (contains uppercase letters)

- result = Name_.isupper()
- print(result)  # False (contains lowercase letters)

#### String Splitting Operations
- Flowers = "Last week couples got flowers"
- Flowers.split(" ")
- # Output: ['Last', 'week', 'couples', 'got', 'flowers']

#### String Joining Operations
- Flowers = "Last week couples got flowers"
- word = Flowers.split(" ")
- result = " ".join(word)
- print(result)  # Last week couples got flowers

- Flowers = "Last week couples got flowers"
- words = Flowers.split(" ")
- result = "_".join(words)
- print(result)  # Last_week_couples_got_flowers

#### String Replacement
- Flowers = "Last week couples got flowers"
- word = Flowers.replace("flowers", "chocolate")
- print(word)  # Last week couples got chocolate

####String Detection Methods
- Flower = "roses"
- Flower.startswith("s")
- # Output: False (roses does not start with "s")

- Flower = "roses"
- Flower.startswith("r")
- # Output: True (roses starts with "r")

- Flower = "Daisy"
- Flower.endswith("e")
- # Output: False (Daisy does not end with "e")

- Flower = "Daisy"
- Flower.endswith("y")
- # Output: True (Daisy ends with "y")
```

## 📸 Results & Screenshots
All lab outputs have been executed successfully in Jupyter Notebook.

#### Case Conversions
![Case Conversions](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%20%203/Case%20Conversions.png?raw=true)

#### Validation Methods
![Validation Methods](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%20%203/Validation%20Methods.png?raw=true)

#### Split and Join
![Split and Join](https://github.com/Essie21/DS-ML-Labs/blob/main/Week%202/Screenshots%20of%20Assignment%20%203/Split%20and%20Join.png?raw=true)

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

