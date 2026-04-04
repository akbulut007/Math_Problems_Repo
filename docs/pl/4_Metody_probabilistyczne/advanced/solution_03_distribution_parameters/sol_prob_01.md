# 🔢 Task 1 — Binomial Model (Quality Control)

## ✅ Solution

### Step 1

We inspect **3 consecutive screws**.

Each screw can be:

- **G** = good  
- **D** = defective  

\[
P(D)=p, \quad P(G)=1-p
\]

This is a binomial experiment with:

\[
n=3
\]

---

### Step 2

The sample space is:

\[
Ω=\{(G,G,G),(G,G,D),(G,D,G),(D,G,G),(G,D,D),(D,G,D),(D,D,G),(D,D,D)\}
\]

\[
|Ω|=2^3=8
\]

---

### Step 3

Since the trials are independent, probabilities are computed by multiplication:

\[
P((G,G,G))=(1-p)^3
\]

\[
P((G,G,D))=(1-p)^2p
\]

\[
P((G,D,G))=(1-p)^2p
\]

\[
P((D,G,G))=(1-p)^2p
\]

\[
P((G,D,D))=(1-p)p^2
\]

\[
P((D,G,D))=(1-p)p^2
\]

\[
P((D,D,G))=(1-p)p^2
\]

\[
P((D,D,D))=p^3
\]

---

### Step 4

A success means:

\[
\text{defective screw}
\]

Let:

\[
X=\text{number of defective screws}
\]

Then:

\[
X \sim \mathrm{Binomial}(3,p)
\]

---

## 📊 Final Summary

| Item | Result |
|------|--------|
| Model | Binomial |
| Trials | \(n=3\) |
| Probability | \(p\) |
| Sample space | \(Ω\) with 8 elements |
| Random variable | \(X \sim \mathrm{Binomial}(3,p)\) |
