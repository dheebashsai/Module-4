## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

      # Step 1: Define two dictionaries
      dict1 = {'a': 100, 'b': 200}
      dict2 = {'b': 300, 'c': 400}
      
      # Step 2: Define the merge function
      def merge(d1, d2):
          merged_dict = {**d1, **d2}
          return merged_dict
      
      # Step 3: Call the function and print result
      result = merge(dict1, dict2)
      print("Merged Dictionary:", result)


## Output
Merged Dictionary: {'a': 100, 'b': 300, 'c': 400}


## Result
The program successfully merges two dictionaries, combining their key-value pairs, with overlapping keys resolved by using the value from the second dictionary.


