## Python Data Structures: Lists, Tuples & Dictionaries



## Table of Contents
- [Overview](#Overview)
- [Key Business Questions](#key-business-questions)
- [Data Source and Structure](#data-source-and-structure)
- [Tools](#tools)
- [Skills Demonstrated](#skills)
- [Dashboard](#dashboard)




## 🎯 Objectives: 

1. Create and manipulate Python Lists using various methods
2. Understand immutable data structures through Tuples
3. Work with key-value pairs using Dictionaries
4. Implement common operations efficiently



## 🛠️ Tools Used

- **Python 3**
- **Jupyter Notebook**
- **Anaconda Navigator**



## Step-by-Step Process

### Step 1: Set Up Environmeent

- Opened Jupyter Notebook in my IDE
- Ensured Python 3.x is installed
- Created a new notebook file


### Step 2: Implement List Operations

- Created a list of items
- Practiced append, extend, insert, remove, pop operations
- Tested indexing and counting
- Implemented sorting and reversing


### Step 3: Explore Tuple Properties

- Created a tuple of countries
- Attempted modifications (observe immutability)
- Practiced count and index operations


### Step 4: Master Dictionary Operations

- Created dictionaries using all three methods
- Implemented nested dictionaries with multiple values
- Practiced accessing values using get()
- Extracted keys and values separately


## 💻 Commands Executed

#### Lists
- letters = ["a", "b", "c", "d", "e"]
- letters.append("f")
- letters.extend(["g", "h"])
- letters.insert(0, 1)
- letters.remove("b")
- pop_element = letters.pop()
- index = letters.index("g")
- count = letters.count("d")
- letters.sort()
- letters.reverse()

#### Tuples
- countries = ("Ghana", "India", "China", "Togo", "Benin")
- count = countries.count("Benin")

#### Dictionaries - Method 1
- myDictionary = {"Name": "Eric", "Age": 21, "Hobby": "Painting"}

#### Dictionaries - Method 2
- myDictionary = dict([("Name", "Eric"), ("Age", 21), ("Hobby", "Painting")])

#### Dictionaries - Method 3
- myDictionary = dict(Name="Eric", Age=21, Hobby="Painting")

#### Dictionaries with multiple values
- myDictionary = {
    "Name": ("Eric", "Cynthia", "Mary"),
    "Age": (21, 34, 45),
    "Hobby": ("Painting", "Singing", "Dancing")
}

#### Accessing dictionary data
- age = myDictionary.get("Age")
- items = myDictionary.items()
- keys = myDictionary.keys()
- values = myDictionary.values()


## 📸 Results & Screenshots
All lab outputs have been executed successfully in Jupyter Notebook.

#### List Creation and Operations
![

