

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

