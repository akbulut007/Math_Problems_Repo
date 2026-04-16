# 🎲 Problem 2 — Die × Die

## 🧪 Sample Space

The experiment consists of two dice rolls:

| Notation | Description |
|----------|------------|
| (i, j)   | i = first die, j = second die |
| i, j ∈ {1,2,3,4,5,6} |

---

## 📌 Part A — Events

### 1. The sum is equal to 8

| Outcomes |
|----------|
| (2,6)    |
| (3,5)    |
| (4,4)    |
| (5,3)    |
| (6,2)    |

---

### 2. The first die is greater than the second

| Outcomes |
|----------|
| (2,1)    |
| (3,1)    |
| (3,2)    |
| (4,1)    |
| (4,2)    |
| (4,3)    |
| (5,1)    |
| (5,2)    |
| (5,3)    |
| (5,4)    |
| (6,1)    |
| (6,2)    |
| (6,3)    |
| (6,4)    |
| (6,5)    |

---

### 3. Both dice show even numbers

| Outcomes |
|----------|
| (2,2)    |
| (2,4)    |
| (2,6)    |
| (4,2)    |
| (4,4)    |
| (4,6)    |
| (6,2)    |
| (6,4)    |
| (6,6)    |

---

### 4. At least one die shows 6

| Outcomes |
|----------|
| (6,1)    |
| (6,2)    |
| (6,3)    |
| (6,4)    |
| (6,5)    |
| (6,6)    |
| (1,6)    |
| (2,6)    |
| (3,6)    |
| (4,6)    |
| (5,6)    |

---

### 5. Exactly one die shows 1

| Outcomes |
|----------|
| (1,2)    |
| (1,3)    |
| (1,4)    |
| (1,5)    |
| (1,6)    |
| (2,1)    |
| (3,1)    |
| (4,1)    |
| (5,1)    |
| (6,1)    |

---

## 🧠 Part B — Interpretation

### Case 1

| Condition |
|-----------|
| i ≥ 3, j ≥ 3 |

**Interpretation:**  
👉 Both dice show values greater than or equal to 3.

---

### Case 2

| Outcomes |
|----------|
| (1,1)    |
| (2,2)    |
| (3,3)    |
| (4,4)    |
| (5,5)    |
| (6,6)    |

**Interpretation:**  
👉 Both dice show the same number.

---

## ✅ Final Summary

| Event Description                  | Outcomes |
|----------------------------------|----------|
| Sum = 8                          | (2,6), (3,5), (4,4), (5,3), (6,2) |
| First die > second               | Multiple (see above) |
| Both even                       | (2,2), (2,4), (2,6), (4,2), (4,4), (4,6), (6,2), (6,4), (6,6) |
| At least one 6                  | All pairs containing 6 |
| Exactly one 1                   | All pairs with a single 1 |

---
