# 🎲 Problem 5 — From Recorded Frequencies to Probability

## 🧪 Experiment

A student rolled a six-sided die **1000 times**.

### 📊 Observed Frequencies

| Outcome | Count n({i}) | Frequency f({i}) |
|--------|-------------|------------------|
| 1      | 168         | 0.168            |
| 2      | 154         | 0.154            |
| 3      | 181         | 0.181            |
| 4      | 167         | 0.167            |
| 5      | 160         | 0.160            |
| 6      | 170         | 0.170            |
| **Total** | **1000** | **1.000**        |

---

## 📌 Definition

\[
f(A) = \frac{n(A)}{1000}
\]

---

## 📌 Part A — From Elementary Outcomes to Events

| Event | Set | n(A) | f(A) |
|------|-----|------|------|
| A | {2,4,6} | 491 | 0.491 |
| B | {1,2,3} | 503 | 0.503 |
| C | {5,6}   | 330 | 0.330 |
| D | {1,3,5} | 509 | 0.509 |
| E | {1,2,3,4} | 670 | 0.670 |

---

## 🧠 Part B — How Frequencies Combine

### ✔ Disjoint Addition

\[
f(\{2,4,6\}) = f(\{2\}) + f(\{4\}) + f(\{6\})
\]

\[
0.491 = 0.154 + 0.167 + 0.170
\]

**Explanation:**  
👉 Disjoint events → frequencies add.

---

### ✔ Union of Disjoint Sets

\[
f(\{1,2,3,4\}) = f(\{1,2\}) + f(\{3,4\})
\]

\[
0.670 = 0.322 + 0.348
\]

---

### ✔ Complementary Events

\[
f(\{1,3,5\}) + f(\{2,4,6\}) = 1
\]

\[
0.509 + 0.491 = 1
\]

---

### ✔ Complement Rule

\[
f(\{5,6\}) = 1 - f(\{1,2,3,4\})
\]

\[
0.330 = 1 - 0.670
\]

---

## ⚠️ Part C — When Addition Works and When It Fails

### ✔ Works (Disjoint Sets)

\[
f(\{1,2\} \cup \{5,6\}) = f(\{1,2\}) + f(\{5,6\})
\]

\[
0.652 = 0.322 + 0.330
\]

---

### ❌ Fails (Non-Disjoint Sets)

Let:

- M = {1,2,3}
- N = {3,4,5}

| Set | f |
|-----|---|
| M   | 0.503 |
| N   | 0.508 |

\[
f(M) + f(N) = 1.011
\]

But:

\[
f(M \cup N) = 0.830
\]

---

### ❗ Reason

👉 Outcome **{3}** is counted twice.

---

## 📦 Part D — Covering the Whole Sample Space

### ✔ Total

\[
f(\{1\}) + f(\{2\}) + ... + f(\{6\}) = 1
\]

---

### ✔ Partition Example

| Set | f |
|-----|---|
| {1,2} | 0.322 |
| {3,4} | 0.348 |
| {5,6} | 0.330 |

\[
0.322 + 0.348 + 0.330 = 1
\]

---

### 📌 General Statement

👉 For any **disjoint partition of Ω**, the sum of frequencies equals **1**.

---

## 📐 Part E — From Frequency to Probability

We define:

\[
f(A) = \frac{n(A)}{1000}
\]

This function satisfies:

- \(0 \le f(A) \le 1\)
- \(f(\emptyset) = 0\)
- \(f(\Omega) = 1\)
- If A ∩ B = ∅ → \(f(A \cup B) = f(A) + f(B)\)
- \(f(A^c) = 1 - f(A)\)

👉 Therefore, **f behaves like a probability measure**.

---

## 🧾 Part F — Conclusion

### 🔗 The Three Levels

1. **Elementary outcomes & events**  
   → All possible results of an experiment

2. **Observed frequencies**  
   → Real data from repeated trials

3. **Probability**  
   → Mathematical model of long-run behavior

---

### 🎯 Final Insight

👉 Probability is a **generalization of observed frequencies**.

It transforms real-world data into a **predictive mathematical framework**.

---
