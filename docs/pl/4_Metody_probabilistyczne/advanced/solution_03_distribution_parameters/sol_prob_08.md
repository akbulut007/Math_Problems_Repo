# 🔢 Task 8 — Geometric Model

## ✅ Solution

### Step 1

The probability of an error in one compilation is:

\[
p=0.1
\]

So the probability of **no error** is:

\[
1-p=0.9
\]

Let:

\[
X=\text{number of compilations until the first error}
\]

Since compilations are independent, we use the **geometric distribution**:

\[
X \sim \mathrm{Geometric}(0.1)
\]

---

### Step 2

We calculate the probability that the **first error appears on the 4th compilation**.

For a geometric random variable:

\[
P(X=k)=(1-p)^{k-1}p
\]

Substitute \(k=4\):

\[
P(X=4)=(0.9)^3(0.1)
\]

\[
P(X=4)=0.729 \cdot 0.1
\]

\[
P(X=4)=0.0729
\]

---

### Step 3

Now we calculate the probability that the first error appears **no later than the 3rd compilation**.

This means:

\[
P(X \leq 3)
\]

We use:

\[
P(X \leq 3)=P(X=1)+P(X=2)+P(X=3)
\]

So:

\[
P(X \leq 3)=0.1+0.9(0.1)+(0.9)^2(0.1)
\]

\[
P(X \leq 3)=0.1+0.09+0.081
\]

\[
P(X \leq 3)=0.271
\]

Alternatively, using the complement:

\[
P(X \leq 3)=1-P(X>3)
\]

\[
P(X>3)=0.9^3=0.729
\]

\[
P(X \leq 3)=1-0.729=0.271
\]

---

## 📊 Final Summary

| Event | Formula | Result |
|------|---------|--------|
| First error on the 4th compilation | \((0.9)^3(0.1)\) | \(0.0729\) |
| First error no later than the 3rd compilation | \(1-(0.9)^3\) | \(0.271\) |
