# 🔢 Task 9 — Poisson Model

## ✅ Solution

### Step 1

The customer service center receives on average:

\[
\lambda=5
\]

requests per hour.

Let:

\[
X=\text{number of requests received in one hour}
\]

Since the number of requests in a fixed time interval follows a Poisson model, we write:

\[
X \sim \mathrm{Poisson}(5)
\]

---

### Step 2

We calculate the probability that there are **exactly 3 requests** in one hour.

For a Poisson random variable:

\[
P(X=k)=\frac{e^{-\lambda}\lambda^k}{k!}
\]

Substitute \(k=3\) and \(\lambda=5\):

\[
P(X=3)=\frac{e^{-5}5^3}{3!}
\]

\[
P(X=3)=\frac{e^{-5}\cdot 125}{6}
\]

Using \(e^{-5}\approx 0.006737947\):

\[
P(X=3)\approx \frac{0.006737947 \cdot 125}{6}
\]

\[
P(X=3)\approx 0.14037
\]

---

### Step 3

Now we calculate the probability that there is **at least one request** in one hour.

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
P(X=0)=\frac{e^{-5}5^0}{0!}=e^{-5}
\]

\[
P(X=0)\approx 0.006737947
\]

So:

\[
P(X \geq 1)=1-0.006737947
\]

\[
P(X \geq 1)\approx 0.99326
\]

---

## 📊 Final Summary

| Event | Formula | Result |
|------|---------|--------|
| Exactly 3 requests | \(\dfrac{e^{-5}5^3}{3!}\) | \(\approx 0.14037\) |
| At least 1 request | \(1-e^{-5}\) | \(\approx 0.99326\) |
