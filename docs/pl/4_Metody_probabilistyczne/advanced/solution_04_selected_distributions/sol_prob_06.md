# 🎯 Problem 6 — Final Discussion: The Axiomatic Point of View

## 📌 Axiomatic Formulation of Probability

Probability is defined as a function \( P \) that assigns a number to each event in a sample space \( \Omega \).

---

## 📐 Kolmogorov Axioms

A probability measure \( P \) satisfies:

### 1. Non-negativity

\[
P(A) \ge 0
\]

for every event \( A \).

---

### 2. Normalization

\[
P(\Omega) = 1
\]

---

### 3. Countable Additivity

For any pairwise disjoint events \( A_1, A_2, A_3, \dots \),

\[
P\left(\bigcup_{i=1}^{\infty} A_i\right)
=
\sum_{i=1}^{\infty} P(A_i)
\]

---

## 🔗 Connection with Earlier Problems

From recorded frequencies, we defined:

\[
f(A) = \frac{n(A)}{N}
\]

This naturally gives:

| Property | Frequency Form |
|----------|----------------|
| Non-negativity | \( f(A) \ge 0 \) |
| Normalization | \( f(\Omega) = 1 \) |
| Finite additivity | \( f(A \cup B) = f(A) + f(B) \) for disjoint \(A,B\) |

---

## ⚠️ What Is New?

Earlier problems only used:

- finite sample spaces
- finite unions of events

The new point in the axiomatic approach is:

- **countable additivity**
- infinite collections of events
- limit-based reasoning

---

## ✅ Key Idea

Finite experiments justify:

- non-negativity
- normalization
- finite additivity

But **countable additivity** cannot be checked directly from finite data.  
It is added as a mathematical axiom to make probability work in infinite settings.

---

## 🧾 Final Conclusion

Probability connects:

1. **events and outcomes**
2. **observed frequencies**
3. **abstract mathematical structure**

So, probability is a rigorous mathematical model built from empirical intuition.

---
