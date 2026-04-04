# 🔢 Task 5 — Multinomial Model (Categories of Outcomes)

## ✅ Solution

### Step 1

A die is rolled **5 times**.

The outcomes are grouped into 3 categories:

- small numbers: \(1,2\)
- medium numbers: \(3,4\)
- large numbers: \(5,6\)

Since each category contains 2 outcomes out of 6, the probabilities are:

\[
P(\text{small})=\frac{2}{6}=\frac{1}{3}
\]

\[
P(\text{medium})=\frac{2}{6}=\frac{1}{3}
\]

\[
P(\text{large})=\frac{2}{6}=\frac{1}{3}
\]

So this is a **multinomial experiment** with 5 independent trials and 3 categories.

---

### Step 2

The sample space can be described as all ordered sequences of length 5, where each roll is classified as:

- \(S\) = small
- \(M\) = medium
- \(L\) = large

Thus:

\[
Ω=\{(x_1,x_2,x_3,x_4,x_5): x_i \in \{S,M,L\}\}
\]

Since each of the 5 rolls has 3 possible category outcomes, the number of elements in the sample space is:

\[
|Ω|=3^5=243
\]

---

### Step 3

Let:

\[
X_1=\text{number of small outcomes}
\]

\[
X_2=\text{number of medium outcomes}
\]

\[
X_3=\text{number of large outcomes}
\]

Then:

\[
X_1+X_2+X_3=5
\]

The multinomial distribution is:

\[
P(X_1=x_1,X_2=x_2,X_3=x_3)=\frac{5!}{x_1!x_2!x_3!}\left(\frac{1}{3}\right)^{x_1}\left(\frac{1}{3}\right)^{x_2}\left(\frac{1}{3}\right)^{x_3}
\]

where:

\[
x_1+x_2+x_3=5
\]

Since all three probabilities are equal to \(1/3\), this can be simplified to:

\[
P(X_1=x_1,X_2=x_2,X_3=x_3)=\frac{5!}{x_1!x_2!x_3!}\left(\frac{1}{3}\right)^5
\]

---

### Step 4

Interpretation of the parameters:

- \(n=5\) = number of trials
- \(p_1=\frac{1}{3}\) = probability of a small outcome
- \(p_2=\frac{1}{3}\) = probability of a medium outcome
- \(p_3=\frac{1}{3}\) = probability of a large outcome

So the model is:

\[
(X_1,X_2,X_3)\sim \mathrm{Multinomial}\left(5;\frac{1}{3},\frac{1}{3},\frac{1}{3}\right)
\]

---

## 📊 Final Summary

| Item | Result |
|------|--------|
| Model | Multinomial |
| Number of trials | \(n=5\) |
| Categories | small, medium, large |
| Category probabilities | \(\frac{1}{3}, \frac{1}{3}, \frac{1}{3}\) |
| Sample space | \(Ω=\{(x_1,x_2,x_3,x_4,x_5): x_i \in \{S,M,L\}\}\) |
| Sample space size | \(3^5=243\) |
| Random variables | \(X_1, X_2, X_3\) |
| Constraint | \(X_1+X_2+X_3=5\) |
| Distribution | \((X_1,X_2,X_3)\sim \mathrm{Multinomial}\left(5;\frac{1}{3},\frac{1}{3},\frac{1}{3}\right)\) |
