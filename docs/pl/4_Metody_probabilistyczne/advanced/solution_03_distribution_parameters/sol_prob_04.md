# 🔢 Task 4 — Poisson Model (Arrival of Events)

## ✅ Solution

### Step 1

A web service receives on average **3 error reports per hour**.

Let:

\[
X=\text{number of error reports received in one hour}
\]

Since the number of events in a fixed time interval is modeled by a Poisson distribution, this is a **Poisson experiment**.

---

### Step 2

The sample space is:

\[
Ω=\{0,1,2,3,\dots\}
\]

This is because the number of reports in one hour can be:

- 0
- 1
- 2
- 3
- and so on

So the sample space consists of all non-negative integers.

---

### Step 3

For a Poisson random variable, the probability distribution is:

\[
P(X=k)=\frac{e^{-\lambda}\lambda^k}{k!}, \qquad k=0,1,2,3,\dots
\]

This formula gives the probability of receiving exactly \(k\) error reports in one hour.

---

### Step 4

The parameter \(\lambda\) represents the **average number of events** in the given interval.

Here, the average number of error reports per hour is 3, so:

\[
\lambda=3
\]

Therefore, for one hour:

\[
X \sim \mathrm{Poisson}(3)
\]

and the probability distribution becomes:

\[
P(X=k)=\frac{e^{-3}3^k}{k!}, \qquad k=0,1,2,3,\dots
\]

---

## 📊 Final Summary

| Item | Result |
|------|--------|
| Model | Poisson |
| Random variable | \(X=\) number of error reports in one hour |
| Sample space | \(Ω=\{0,1,2,3,\dots\}\) |
| General formula | \(P(X=k)=\dfrac{e^{-\lambda}\lambda^k}{k!}\) |
| Parameter meaning | Average number of events in the interval |
| Value of parameter | \(\lambda=3\) |
| Final model | \(X \sim \mathrm{Poisson}(3)\) |
