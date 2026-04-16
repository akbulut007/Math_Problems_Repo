# 🎲 Problem 4 — Building Complex Statements from Simple Ones

## 🧪 Representation

Each outcome is denoted by a pair **(i, j)**, where:

| Symbol | Meaning |
|--------|---------|
| i      | Result of the first die (row) |
| j      | Result of the second die (column) |

---

## 📌 Part A — Basic Events

### A: The sum is equal to 7

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | . | . | . | . | . | X |
| 2    | . | . | . | . | X | . |
| 3    | . | . | . | X | . | . |
| 4    | . | . | X | . | . | . |
| 5    | . | X | . | . | . | . |
| 6    | X | . | . | . | . | . |

---

### B: The first die is greater than the second

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | . | . | . | . | . | . |
| 2    | X | . | . | . | . | . |
| 3    | X | X | . | . | . | . |
| 4    | X | X | X | . | . | . |
| 5    | X | X | X | X | . | . |
| 6    | X | X | X | X | X | . |

---

### C: At least one die shows 6

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | . | . | . | . | . | X |
| 2    | . | . | . | . | . | X |
| 3    | . | . | . | . | . | X |
| 4    | . | . | . | . | . | X |
| 5    | . | . | . | . | . | X |
| 6    | X | X | X | X | X | X |

---

## 🧠 Part B — Compound Events

### 1. A ∪ C  
**(sum = 7 OR at least one die is 6)**

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | . | . | . | . | . | X |
| 2    | . | . | . | . | X | X |
| 3    | . | . | . | X | . | X |
| 4    | . | . | X | . | . | X |
| 5    | . | X | . | . | . | X |
| 6    | X | X | X | X | X | X |

---

### 2. A ∩ C  
**(sum = 7 AND at least one die is 6)**

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | . | . | . | . | . | X |
| 2    | . | . | . | . | . | . |
| 3    | . | . | . | . | . | . |
| 4    | . | . | . | . | . | . |
| 5    | . | . | . | . | . | . |
| 6    | X | . | . | . | . | . |

---

### 3. B ∩ C  
**(first die > second AND at least one die is 6)**

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | . | . | . | . | . | . |
| 2    | . | . | . | . | . | . |
| 3    | . | . | . | . | . | . |
| 4    | . | . | . | . | . | . |
| 5    | . | . | . | . | . | . |
| 6    | X | X | X | X | X | . |

---

### 4. A ∩ (not B)  
**(sum = 7 AND first ≤ second)**

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | . | . | . | . | . | X |
| 2    | . | . | . | . | X | . |
| 3    | . | . | . | X | . | . |
| 4    | . | . | . | . | . | . |
| 5    | . | . | . | . | . | . |
| 6    | . | . | . | . | . | . |

---

### 5. A ∩ (no 6)  
**(sum = 7 AND no die shows 6)**

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | . | . | . | . | . | . |
| 2    | . | . | . | . | X | . |
| 3    | . | . | . | X | . | . |
| 4    | . | . | X | . | . | . |
| 5    | . | X | . | . | . | . |
| 6    | . | . | . | . | . | . |

---

### 6. C ∩ (not A)  
**(at least one die is 6 AND sum ≠ 7)**

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | . | . | . | . | . | . |
| 2    | . | . | . | . | . | X |
| 3    | . | . | . | . | . | X |
| 4    | . | . | . | . | . | X |
| 5    | . | . | . | . | . | X |
| 6    | . | X | X | X | X | X |

---

### 7. (not A) ∩ B  
**(sum ≠ 7 AND first die > second)**

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | . | . | . | . | . | . |
| 2    | X | . | . | . | . | . |
| 3    | X | X | . | . | . | . |
| 4    | X | X | X | . | . | . |
| 5    | X | X | X | X | . | . |
| 6    | . | X | X | X | X | . |

---

### 8. (not B) ∩ C  
**(first die ≤ second AND at least one die is 6)**

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | . | . | . | . | . | X |
| 2    | . | . | . | . | . | X |
| 3    | . | . | . | . | . | X |
| 4    | . | . | . | . | . | X |
| 5    | . | . | . | . | . | X |
| 6    | . | . | . | . | . | X |

---

### 9. not (A ∪ C)  
**(neither sum = 7 nor any die shows 6)**

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | X | X | X | X | X | . |
| 2    | X | X | X | X | . | . |
| 3    | X | X | X | . | X | . |
| 4    | X | X | . | X | X | . |
| 5    | X | . | X | X | X | . |
| 6    | . | . | . | . | . | . |

---

### 10. not (A ∩ C)  
**(not both sum = 7 and at least one die is 6)**

| i \ j | 1 | 2 | 3 | 4 | 5 | 6 |
|------|---|---|---|---|---|---|
| 1    | X | X | X | X | X | . |
| 2    | X | X | X | X | X | X |
| 3    | X | X | X | X | X | X |
| 4    | X | X | X | X | X | X |
| 5    | X | X | X | X | X | X |
| 6    | . | X | X | X | X | X |

---

## ✅ Final Summary

| Event | Meaning |
|------|---------|
| A | Sum is equal to 7 |
| B | First die is greater than the second |
| C | At least one die shows 6 |
| A ∪ C | Sum = 7 OR at least one die is 6 |
| A ∩ C | Sum = 7 AND at least one die is 6 |
| B ∩ C | First die > second AND at least one die is 6 |
| A ∩ (not B) | Sum = 7 AND first ≤ second |
| A ∩ (no 6) | Sum = 7 AND no die shows 6 |
| C ∩ (not A) | At least one die is 6 AND sum ≠ 7 |
| (not A) ∩ B | Sum ≠ 7 AND first die > second |
| (not B) ∩ C | First die ≤ second AND at least one die is 6 |
| not (A ∪ C) | Neither sum = 7 nor any die shows 6 |
| not (A ∩ C) | Not both sum = 7 and at least one die is 6 |

---
