
"""
Description:
------------
The `MyString` class extends Python's built-in `str` class to provide additional functionality
for finding the first and last occurrence of a character within a string. 

The class provides two methods, `indexOf` and `lastIndexOf`, which find the index of the first
and last occurrence of a character within a string, respectively.

Functions:
----------
1. `indexOf(self, ch, fromIndex)`: 
    - Finds the index of the first occurrence of a character (`ch`) in the string starting from a given index.
2. `lastIndexOf(self, ch, fromIndex)`:
    - Finds the index of the last occurrence of a character (`ch`) in the string before or at a given index.

Parameters:
-----------
- `ch`: The character to search for in the string.
- `fromIndex`: The starting or ending index for the search.

Input:
------
- A string instance of `MyString` and character(s) for the search.
- Starting or ending index for the search.

Output:
-------
- The index of the first or last occurrence of the character if found.
- `-1` if the character is not found within the specified range.

Date: 11/23/24
Author: Cherry

"""

class MyString(str): # Inherit from the built-in `str` class
    def __new__(cls, s=""): # Override the __new__ method to ensure proper initialization
        
        # Use str's __new__ to create a new instance of the string
        instance = super(MyString, cls).__new__(cls, s)
        return instance
    
    def indexOf(self, ch, fromIndex): # fromIndex is exclusive
       
        try:
            # Use the built-in `index` method to find the character
            index = self.index(ch, fromIndex)
            return index
        except ValueError:
            # Return -1 if the character is not found
            return -1
    
    def lastIndexOf(self, ch, fromIndex):  # fromIndex is inclusive
   
        try:
            # Use the built-in `rfind` method to find the character from the end
            index = self.rfind(ch, 0, fromIndex + 1)
            return index
        except ValueError:
            # Return -1 if the character is not found
            return -1


def main():

    # Create an instance of MyString
    s = MyString("Programming is fun. Programming is fun.")
    
    # Define the character to search for
    ch = 'i'

    # Test and print results for indexOf and lastIndexOf methods
    print(s.indexOf(ch, 10))  # Expected: Index of 'i' after index 10 (12)
    print(s.indexOf(ch, 23))  # Expected: Index of 'i' after index 23 (28)
    print(s.lastIndexOf(ch, 29))  # Expected: Last index of 'i' before or at index 29 (28)
    print(s.lastIndexOf(ch, 4))   # Expected: Last index of 'i' before or at index 4 (-1)


# Run the main function to test the code
main()
