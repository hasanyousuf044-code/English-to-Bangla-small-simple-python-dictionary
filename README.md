# English-to-Bangla-small-simple-python-dictionary

# 📚 English-to-Bangla Console Dictionary

![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg?style=flat-square&logo=python)
![Build Status](https://img.shields.io/badge/Status-Active-success.svg?style=flat-square)
![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-green.svg?style=flat-square)

## 🚀 Overview

The **English-to-Bangla Console Dictionary** is a lightweight, blazing-fast, Command-Line Interface (CLI) application built entirely in Python. It is designed to provide instantaneous English to Bengali word translations. By leveraging Python's native dictionary (Hash Map) data structure, the application ensures **O(1) time complexity** for word lookups, making it highly efficient.

This project is perfect for quick vocabulary referencing directly from the terminal without the need for an internet connection or external APIs.

## ✨ Key Features

* **Lightning Fast Lookups:** Utilizes Python dictionary hashing for instant data retrieval.
* **Case-Insensitive Search:** Built-in input normalization (`.lower()`) ensures that queries like "Word", "WORD", and "word" yield the exact same accurate result.
* **Rich Vocabulary Base:** Comes pre-loaded with an extensive and categorized vocabulary, including:
    * *Numerals & Time* (Days, Months)
    * *Pronouns & Question Words*
    * *Action Verbs & Daily Activities*
    * *Family, Relationships & Occupations*
    * *Nature, Animals & Weather*
    * *Technology & Vehicles*
* **Intuitive Error Handling:** Graceful visual feedback (❌) prevents crashes and alerts the user if a specific word is outside the current vocabulary scope.

## 🛠️ Technical Stack

* **Language:** Python 3.x
* **Environment:** Any standard terminal or command-line interface (Windows CMD, PowerShell, Linux/macOS Terminal).
* **Dependencies:** Standard Python Library (No external packages like `pip` required).

## 💻 Installation & Usage

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/hasanyousuf044-code/English-to-Bangla-small-simple-python-dictionary.git](https://github.com/hasanyousuf044-code/English-to-Bangla-small-simple-python-dictionary.git)
2.**Navigate to the Directory:**
  ```bash
cd English-to-Bangla-small-simple-python-dictionary
```
3.**Run the Script:**
Execute the Python file directly from your terminal:
```bash
python Dictionary.py
```
4.Enter a Word:
When prompted with enter a word: , type any English word (e.g., Mother, computer, sky) and press Enter to get the Bengali translation.
--- 
## 🧩 Code Architecture

​*The script operates on a straightforward but robust logic flow:*

​* **Data Storage: A large, statically typed dictionary variable acts as the primary local database.**

​* **User Input: Captures user keystrokes and immediately sanitizes the string to lowercase.**

​* **Conditional Logic: - An if-else block verifies the existence of the key within the hash map.**

​* **Upon a match, it prints the corresponding value.**

​* **Upon a miss, it outputs a pre-defined exception string.**

## 🤝 Contribution

​Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute to expanding the dictionary database or optimizing the code structure.
