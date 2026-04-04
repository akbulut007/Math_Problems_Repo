# 🔢 Task 6 — Binomial Model

## ✅ Solution

### Step 1

The probability that a part is defective is:

\[
p=0.04
\]

The inspector checks:

\[
n=10
\]

Let:

\[
X=\text{number of defective parts among 10}
\]

Since the trials are independent, we use the **binomial distribution**:

\[
X \sim \mathrm{Binomial}(10,0.04)
\]

---

### Step 2

We calculate the probability that **exactly 2 parts are defective**.

For a binomial random variable:

\[
P(X=k)=\binom{n}{k}p^k(1-p)^{n-k}
\]

Substitute:

\[
P(X=2)=\binom{10}{2}(0.04)^2(0.96)^8
\]

Now:

\[
\binom{10}{2}=45
\]

\[
(0.04)^2=0.0016
\]

\[
(0.96)^8 \approx 0.7213895789838334
\]

Therefore:

\[
P(X=2)=45 \cdot 0.0016 \cdot 0.7213895789838334
\]

\[
P(X=2)\approx 0.05194
\]

---

### Step 3

Now we calculate the probability that **at least one part is defective**.

This means:

\[
P(X \geq 1)
\]

It is easier to use the complement:

\[
P(X \geq 1)=1-P(X=0)
\]

Now:

\[
P(X=0)=\binom{10}{0}(0.04)^0(0.96)^{10}=(0.96)^{10}
\]

\[
(0.96)^{10}\approx 0.664832635991501
\]

So:

\[
P(X \geq 1)=1-0.664832635991501
\]

\[
P(X \geq 1)\approx 0.33517
\]

---

## 📊 Final Summary

| Event | Formula | Result |
|------|---------|--------|
| Exactly 2 defective parts | \(\binom{10}{2}(0.04)^2(0.96)^8\) | \(\approx 0.05194\) |
| At least 1 defective part | \(1-(0.96)^{10}\) | \(\approx 0.33517\) |
