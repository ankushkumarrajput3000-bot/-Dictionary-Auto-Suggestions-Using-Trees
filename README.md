# 📖 Dictionary with Auto-Suggestions
### ⚡ A Smart Dictionary Application Using Trie Data Structure in C++

<p align="center">
  <img src="https://img.shields.io/badge/Language-C++-blue?style=for-the-badge&logo=cplusplus" />
  <img src="https://img.shields.io/badge/Concept-Trie%20Data%20Structure-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Project-DSA-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
</p>

<p align="center">
  <b>🔍 Search smarter. Type less. Discover words faster!</b>
</p>

---

## 🌟 About The Project

**Dictionary with Auto-Suggestions** is a console-based application developed using **C++** that demonstrates the practical implementation of the **Trie (Prefix Tree) Data Structure**.

Unlike traditional dictionaries, this application provides word suggestions while searching based on the prefix entered by the user.

The project demonstrates how Trie can efficiently manage words and perform prefix-based searching.

## ✨ Key Features

| Feature | Description |
|---|---|
| ➕ Insert Word | Add new words to the dictionary |
| 🔎 Search Word | Check whether a complete word exists |
| 💡 Auto-Suggestions | Generate suggestions based on a prefix |
| 📚 Display All | Display all stored dictionary words |
| 🔡 Case Insensitive | Supports uppercase and lowercase English input |
| 🖥️ Interactive Menu | Simple menu-driven console interface |

## 🧠 Data Structure Used — Trie

A **Trie** is a tree-like data structure used to store and retrieve strings efficiently.

Each node represents a character, and words with common prefixes share the same path.

### Example

Suppose the dictionary contains:

- Apple
- Application
- Apply
- Appointment
- Banana

Searching with the prefix `app` generates:

```text
Input: app

Suggestions:
  1. apple
  2. application
  3. appointment
  4. apply
```

## ⚙️ How It Works

```text
             START
               |
          Create Trie
               |
        Insert Dictionary Words
               |
          Display Menu
               |
     +---------+---------+
     |         |         |
   Insert    Search   Auto-Suggest
     |         |         |
  Add Word  Check Word  Enter Prefix
     |         |         |
     +---------+---------+
               |
          Display Result
               |
          Continue / Exit
```

## ⏱️ Time Complexity Analysis

Let:
- `L` = Length of the word
- `P` = Length of the prefix

| Operation | Time Complexity |
|---|---|
| Insertion | O(L) |
| Exact Search | O(L) |
| Prefix Lookup | O(P) |
| Suggestion Listing | Depends on subtree size |

## 🛠️ Technologies & Concepts

**Programming Language**
- C++

**Libraries**
- `iostream`
- `unordered_map`
- `vector`
- `string`
- `algorithm`

**DSA Concepts**
- Trie Data Structure
- Tree Traversal
- Depth First Search (DFS)
- Recursion
- Hash Maps
- Pointers
- String Manipulation

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Dictionary-Auto-Suggestions-Using-Trie.git
```

### 2. Navigate to the Project Folder

```bash
cd Dictionary-Auto-Suggestions-Using-Trie
```

### 3. Compile the Program

```bash
g++ main.cpp -o dictionary
```

### 4. Run the Application

**Windows:**
```bash
dictionary.exe
```

**Linux / macOS:**
```bash
./dictionary
```

## 📸 Application Preview

_Add screenshots of your program's terminal output here._

<!-- Example:
![Application Output](screenshots/output.png)
-->

## 🔮 Future Improvements

- 💾 Permanent storage using file handling.
- 🎨 Graphical User Interface (GUI).
- 🗑️ Word deletion functionality.
- 📊 Suggestion ranking based on word frequency.
- ✍️ Spell correction and typo detection.
- 🌐 Support for multiple languages.

## 📂 Project Structure

```text
Dictionary-Auto-Suggestions-Using-Trie/
│
├── main.cpp
├── README.md
├── Dictionary_Auto_Suggestions_Project_Report.pdf
└── screenshots/
    └── output.png
```

## 👨‍💻 Project Contributors

**Arun**

**Ankush Kumar Rajput**

🎓 Bachelor of Engineering – Computer Science & Engineering

📚 Academic Project | Data Structures & Algorithms

---

## ⭐ Support

If you find this project interesting or helpful, consider giving this repository a ⭐ on GitHub!

<p align="center">
  <b>Made with ❤️ using C++ and Data Structures</b>
</p>
