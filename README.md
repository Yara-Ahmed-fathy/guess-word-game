# Guess Word Terminal Game 🎮

Welcome to my very first university programming project! This is a classic **Word Guessing Game** built entirely in C++ that runs directly in the terminal. 

The project was designed to demonstrate fundamental programming concepts, particularly memory management using pointers and structural logic in C++.

---

## 📌 Project Overview & Logic

This is a **static game**, meaning the secret word is hardcoded (`"programming"`) rather than dynamically fetched from an external API or file. The primary objective was to focus on core logic and memory manipulation rather than dynamic data handling.

### Key Features & Concepts Used:
* **Pointers & Memory Management:** Utilised pointers (`int* pLives`) to directly track and modify the player's remaining lives across different scopes.
* **String Manipulation:** Pass-by-pointer approach to dynamically update the hidden word display (`string* displayWord`) as the player guesses correctly.
* **Game Loop Logic:** A structured `while` loop that continuously validates user input, manages game states, and checks win/loss conditions.

---

