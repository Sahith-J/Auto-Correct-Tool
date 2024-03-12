# AutoCorrect-Tool
Auto Correct Tool

This project demonstrates an auto-correct tool implemented in Python. The tool takes a sentence as input and corrects any misspelled words or suggests the closest alternatives based on edit distance.

Key Features:
- Calculates edit distance: The tool uses dynamic programming to calculate the edit distance between two words, which represents the minimum number of operations required to transform one word into another.
- Finds closest word: It searches for the closest word in a predefined dictionary based on the calculated edit distance.
- Auto-corrects sentence: The tool tokenizes the input sentence, identifies misspelled words, and replaces them with the correct words or the closest alternatives.

Usage:
1. Define the dictionary of correct words.
2. Enter a sentence to be auto-corrected.
3. The tool analyzes the sentence, identifies misspelled words, and suggests corrections or replacements.
4. The corrected sentence is displayed as the output.

Dependencies:
- No external modules are used in this implementation, making it lightweight and self-contained.

Note:
- This implementation uses the concept of edit distance to suggest corrections. The accuracy of the auto-correct tool may vary based on the dictionary size and the nature of the input text.

Feel free to modify the dictionary or input sentence as needed to test different scenarios.

