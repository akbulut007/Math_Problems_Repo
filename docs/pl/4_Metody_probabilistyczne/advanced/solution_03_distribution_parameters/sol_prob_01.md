## 🔢 Task 1 — Binomial Model (Quality Control)

In a factory, screws are inspected.  
Each screw can be either **good (G)** or **defective (D)**.  
The probability that a screw is defective is denoted by \( p \).

Additionally:

- Inspections are **independent**
- Each screw has the same probability \( p \)
- We inspect **3 consecutive screws**

---

### 1️⃣ Random experiment

The experiment consists of:

**Inspecting 3 consecutive screws and recording whether each one is good or defective.**

Each trial has two possible outcomes:

- G = Good
- D = Defective

Thus, this is a sequence of **3 independent Bernoulli trials**.

---

### 2️⃣ Sample space \( \Omega \)

Each screw has 2 possible outcomes, so:

\[
|\Omega| = 2^3 = 8
\]

\[
\Omega = \{GGG, GGD, GDG, DGG, GDD, DGD, DDG, DDD\}
\]

---

### 3️⃣ Probabilities of outcomes

- \( P(G) = 1 - p \)
- \( P(D) = p \)

Since trials are independent:

\[
P(GGG) = (1-p)^3
\]

\[
P(GGD) = (1-p)^2 p
\]

\[
P(GDG) = (1-p)^2 p
\]

\[
P(DGG) = (1-p)^2 p
\]

\[
P(GDD) = (1-p)p^2
\]

\[
P(DGD) = (1-p)p^2
\]

\[
P(DDG) = (1-p)p^2
\]

\[
P(DDD) = p^3
\]

---

### 4️⃣ Definition of success

In this model, we define:

**Success = a defective screw**

Let:

\[
X = \text{number of defective screws among 3}
\]

Then:

\[
X \sim \text{Binomial}(n=3, p)
\]

---

## ✅ Final Summary

| Element | Result |
|--------|--------|
| Model | Binomial |
| Number of trials | \( n = 3 \) |
| Probability of success | \( p \) |
| Success definition | Defective screw |
| Sample space size | 8 |

---
