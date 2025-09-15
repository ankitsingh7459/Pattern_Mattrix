# 🧮 Pattern Matrix Problem (Matricia Land)

This project solves a matrix-based problem where we draw letters (`Z`, `D`, `A`, `X`) using numbers inside an `N × N` matrix.  
It is implemented in **Java**.

---

## 📖 Problem Description

In the land of **Matricia**, the king encodes messages by drawing patterns on square grids.

You are given:
1. A **square matrix** of size `N × N` filled with numbers from `1` to `N×N` in **row-major order**.
2. A **character `ch`** which can be:
   - `Z` → Draw the letter **Z**
   - `D` → Draw the letter **D**
   - `A` → Draw the letter **A**
   - `X` → Draw the letter **X**

### Your Task
- Construct the chosen letter pattern using matrix elements.
- Replace all **non-pattern** positions with `0`.
- Print the resulting matrix.
- Print the **sum of all values used** in the pattern.

---

## 📌 Input Format
- First line: a character `ch` (one of `Z, D, A, X`)
- Second line: an integer `N` (matrix size, `3 ≤ N ≤ 20`)

## 📌 Output Format
- The `N × N` matrix showing only the chosen pattern.
- The sum of all values included in the pattern.

---
