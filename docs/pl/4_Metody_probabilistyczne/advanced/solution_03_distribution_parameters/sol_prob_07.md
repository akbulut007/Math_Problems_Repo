# 🔢 Task 7 — Hypergeometric Model

## ✅ Solution

### Step 1

The box contains:

- 12 working light bulbs
- 3 defective light bulbs

So the total number of bulbs is:

\[
N=15
\]

We draw:

\[
n=5
\]

bulbs **without replacement**.

Let:

\[
X=\text{number of defective bulbs in the sample}
\]

Since the selection is made without replacement, we use the **hypergeometric distribution**.

---

### Step 2

We want the probability that the sample contains **exactly 2 defective bulbs**.

So we calculate:

\[
P(X=2)
\]

The hypergeometric formula is:

\[
P(X=k)=\frac{\binom{K}{k}\binom{N-K}{n-k}}{\binom{N}{n}}
\]

Here:

- \(N=15\) total bulbs
- \(K=3\) defective bulbs
- \(n=5\) drawn bulbs
- \(k=2\) defective bulbs in the sample

Substitute into the formula:

\[
P(X=2)=\frac{\binom{3}{2}\binom{12}{3}}{\binom{15}{5}}
\]

---

### Step 3

Now compute the combinations:

\[
\binom{3}{2}=3
\]

\[
\binom{12}{3}=220
\]

\[
\binom{15}{5}=3003
\]

So:

\[
P(X=2)=\frac{3 \cdot 220}{3003}
\]

\[
P(X=2)=\frac{660}{3003}
\]

\[
P(X=2)\approx 0.21978
\]

---

## 📊 Final Summary

| Event | Formula | Result |
|------|---------|--------|
| Exactly 2 defective bulbs | \(\dfrac{\binom{3}{2}\binom{12}{3}}{\binom{15}{5}}\) | \(\dfrac{660}{3003}\approx 0.21978\) |
