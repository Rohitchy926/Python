# Python provides two important data structures: Dictionary (dict) and Set (set).

Both are used to store multiple values, but they work differently.
- Dictionary: Stores data in key-value pairs.
- Set: Stores unique elements (no duplicates)

## 1. What is a Dictionary?
A dictionary is a collection of data stored in key: value pairs.

It is created using curly brackets {}.

EX- employee = {
    "name": "Rohit",
    "age": 25,
    "role": "SRE",
    "company": "IT Company"
}

print(employee)

O/P- {'name': 'Rohit', 'age': 25, 'role': 'SRE', 'company': 'IT Company'}


<img width="1202" height="563" alt="image" src="https://github.com/user-attachments/assets/d8688a89-f014-42bb-aaa2-14ece864925e" />


***How to update dictionary***

here age is updated from 25 to 32.

<img width="1177" height="542" alt="image" src="https://github.com/user-attachments/assets/461d5955-c5eb-44a4-96bf-c9a0cd46edfa" />


**How to add new values (Key nd pair)in dictionary**

<img width="1201" height="563" alt="image" src="https://github.com/user-attachments/assets/a38debce-e8b5-4dc5-986f-f719daac2070" />


**How to remove any value**

By using pop

<img width="1206" height="575" alt="image" src="https://github.com/user-attachments/assets/4892b070-4c1d-4913-9ce8-2bfab49345d2" />


## Good Notes

### Dictionary
- A dictionary stores data in key-value pairs.
- Each key must be unique within the dictionary.
- Keys are used to access values quickly.
- Dictionaries are mutable, so you can update, add, or delete items.
- They are useful for storing information like student details, employee records, and configuration data.
- Example: `student = {"name": "Rohit", "age": 21}`

### Set
- A set stores only unique values.
- Duplicate values are automatically removed.
- Sets are unordered, so their elements do not have a fixed index.
- Sets are useful for membership tests and removing duplicates.
- Example: `nums = {10, 20, 30, 20}` gives `{10, 20, 30}`

### Difference between Dictionary and Set
- Dictionary uses key-value pairs.
- Set stores only single values.
- Dictionary allows access through keys.
- Set does not support indexing.
- Dictionary is used when data is related to names or labels.
- Set is used when we need unique elements only.

### Example
```python
student = {
    "name": "Rohit",
    "age": 22,
    "class": "Python"
}

print(student["name"])  # Rohit

numbers = {1, 2, 3, 2, 4}
print(numbers)  # {1, 2, 3, 4}
```

> Remember: Use a dictionary for structured data and a set for unique values.

**task1: create a dictionary named mark  to store mark of three subjects and add subject one by one and print the final dictionary**

<img width="1191" height="569" alt="image" src="https://github.com/user-attachments/assets/db238938-435f-487c-82a5-3c780d11c05a" />
