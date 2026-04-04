# 🔢 Task 2 — Hypergeometric Model (Sampling from a Batch)

## ✅ Solution

### Step 1

A warehouse contains:

- 20 components in total
- 5 defective components
- 15 functional components

We randomly select **4 components without replacement**.

This means that after one component is selected, it is **not returned** to the batch.

So this is a **hypergeometric experiment**.

---

### Step 2

Let:

\[
X=\text{number of defective components in the sample}
\]

We want to determine the possible values of \(X\).

Since we select 4 components, the minimum number of defective components is:

\[
0
\]

The maximum number of defective components is:

\[
4
\]

because we draw only 4 components, and there are at least 4 defective-or-functional combinations available.

So:

\[
X \in \{0,1,2,3,4\}
\]

---

### Step 3

In the hypergeometric model, the probability distribution is:

\[
P(X=k)=\frac{\binom{5}{k}\binom{15}{4-k}}{\binom{20}{4}}
\]

where:

- \(\binom{5}{k}\) = number of ways to choose \(k\) defective components
- \(\binom{15}{4-k}\) = number of ways to choose \(4-k\) functional components
- \(\binom{20}{4}\) = total number of ways to choose 4 components from 20

---

### Step 4

Now we write the distribution for all possible values of \(X\).

#### For \(X=0\)

\[
P(X=0)=\frac{\binom{5}{0}\binom{15}{4}}{\binom{20}{4}}
\]

#### For \(X=1\)

\[
P(X=1)=\frac{\binom{5}{1}\binom{15}{3}}{\binom{20}{4}}
\]

#### For \(X=2\)

\[
P(X=2)=\frac{\binom{5}{2}\binom{15}{2}}{\binom{20}{4}}
\]

#### For \(X=3\)

\[
P(X=3)=\frac{\binom{5}{3}\binom{15}{1}}{\binom{20}{4}}
\]

#### For \(X=4\)

\[
P(X=4)=\frac{\binom{5}{4}\binom{15}{0}}{\binom{20}{4}}
\]

---

### Step 5

In this model, a **success** means:

\[
\text{selecting a defective component}
\]

So \(X\) counts how many defective components are chosen among the 4 selected components.

---

## 📊 Final Summary

| Item | Result |
|------|--------|
| Model | Hypergeometric |
| Total number of components | 20 |
| Defective components | 5 |
| Functional components | 15 |
| Number selected | 4 |
| Random variable | \(X=\) number of defective components |
| Possible values of \(X\) | \(\{0,1,2,3,4\}\) |
| Probability formula | \(\displaystyle P(X=k)=\frac{\binom{5}{k}\binom{15}{4-k}}{\binom{20}{4}}\) |
| Success | Selecting a defective component |
