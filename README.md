# 🧩 Sudoku Solver

## 📌 Task-04

A Python program that automatically solves a 9x9 Sudoku puzzle using the Backtracking Algorithm.

---

## 🎯 Objective

Create a program that:
- Accepts an unsolved Sudoku grid
- Uses backtracking to explore possible number placements
- Finds the correct solution
- Displays the completed Sudoku board

---

## 🛠 Technologies Used

- Python 3
- Backtracking Algorithm
- Recursion

---

## 🧠 Algorithm Used

### 🔄 Backtracking

Backtracking is a recursive algorithm that:

1. Finds an empty cell.
2. Tries numbers 1–9.
3. Checks if the number is valid:
   - Not in the same row
   - Not in the same column
   - Not in the same 3x3 grid
4. If valid → place number and move forward.
5. If stuck → backtrack and try another number.

---


## 📋 Sample Input

```
7 8 0 4 0 0 1 2 0
6 0 0 0 7 5 0 0 9
0 0 0 6 0 1 0 7 8
0 0 7 0 4 0 2 6 0
0 0 1 0 5 0 9 3 0
9 0 4 0 6 0 0 0 5
0 7 0 3 0 0 0 1 2
1 2 0 0 0 7 4 0 0
0 4 9 2 0 6 0 0 7
```

---

## ✅ Output

Displays the fully solved Sudoku grid in the terminal.

---


## 👩‍💻 Author
- Name : Pruonh Kimliya
- Email: kimliyapruonh@gmail.com
