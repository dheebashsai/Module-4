# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
      # Step 2: Define the dictionary
      my_dict = {'banana': 'yellow', 'apple': 'red', 'grape': 'purple', 'cherry': 'red'}
      
      # Step 3: Sort by keys
      sorted_by_keys = dict(sorted(my_dict.items()))
      
      # Step 4: Sort by values
      sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))
      
      # Step 5: Display results
      print("Original Dictionary:", my_dict)
      print("Dictionary Sorted by Keys:", sorted_by_keys)
      print("Dictionary Sorted by Values:", sorted_by_values)


## Sample Output
Original Dictionary: {'banana': 'yellow', 'apple': 'red', 'grape': 'purple', 'cherry': 'red'}
Dictionary Sorted by Keys: {'apple': 'red', 'banana': 'yellow', 'cherry': 'red', 'grape': 'purple'}
Dictionary Sorted by Values: {'grape': 'purple', 'apple': 'red', 'cherry': 'red', 'banana': 'yellow'}


## Result
The program successfully sorts the dictionary by both keys and values in alphabetical order and displays the results.
