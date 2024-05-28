# CMP-202-ARRAY-ASSIGNMENT
ALGORITHM


STEP 1: First, convert the input word to a character array using the toCharArray() method.
STEP 2: Initialize two pointers, start and end, to the beginning and end of the character array, respectively.
STEP 3: Iterate through the character array, comparing the characters at the start and end pointers. If they are not equal, the word is not a palindrome.
STEP 4: If the characters at the start and end pointers are equal, swap them using a temporary variable and move the start pointer to the right and the end pointer to the left.
STEP 5: Repeat steps 3 and 4 until the start pointer is greater than or equal to the end pointer.
STEP 6: If the loop completes without finding any unequal characters, the word is a palindrome.
