# Dictionary with Auto-Suggestions 

A console-based Dictionary Application developed in **C++** using the **Trie (Prefix Tree) Data Structure**.

## About the Project

This project implements a simple dictionary that allows users to insert words, search for complete words, display all stored words, and receive auto-suggestions based on a given prefix.

It uses a Trie data structure to make prefix-based searching efficient.

## Features

- Insert new words into the dictionary.
- Search for a complete word.
- Generate auto-suggestions based on a prefix.
- Display all stored words.
- Case-insensitive word handling.
- Menu-driven console interface.

## Data Structures and Concepts Used

- Trie Data Structure
- Pointers
- Recursion
- DFS (Depth First Search)
- Hash Maps (`unordered_map`)
- Vectors
- String Manipulation
- Sorting Algorithms

## Time Complexity

| Operation | Time Complexity |
|---|---|
| Insertion | O(L) |
| Exact Search | O(L) |
| Prefix Lookup | O(P) |
| Suggestions | Depends on subtree size |

Where L is the word length and P is the prefix length.

## Technologies Used

- Language: C++
- Compiler: GCC / G++
- IDE: VS Code / Code::Blocks

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/Dictionary-Auto-Suggestions-Using-Trie.git
   ```

2. Open the project folder.

3. Compile the program:

   ```bash
   g++ main.cpp -o dictionary
   ```

4. Run the program:

   ```bash
   ./dictionary
   ```

   On Windows:

   ```bash
   dictionary.exe
   ```

## Future Enhancements

- File-based permanent storage.
- Graphical User Interface (GUI).
- Word deletion functionality.
- Suggestion ranking by frequency.
- Spell correction.

## Authors

- Arun
- Ankush Kumar Rajput

## Project Type

Academic Project – Data Structures and Algorithms (DSA)

**Language:** C++
