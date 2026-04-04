# 🔢 Task 10 — Multinomial Model

## ✅ Solution

### Step 1

The probabilities of the three candy flavors are:

\[
P(\text{strawberry})=0.40
\]

\[
P(\text{lemon})=0.35
\]

\[
P(\text{mint})=0.25
\]

We perform:

\[
n=6
\]

independent selections **with replacement**.

Let:

- \(X_1=\) number of strawberry candies
- \(X_2=\) number of lemon candies
- \(X_3=\) number of mint candies

We want the probability of getting:

\[
X_1=3,\quad X_2=2,\quad X_3=1
\]

Since there are more than two categories, we use the **multinomial distribution**.

---

### Step 2

The multinomial formula is:

\[
P(X_1=x_1,X_2=x_2,X_3=x_3)
=
\frac{n!}{x_1!x_2!x_3!}
p_1^{x_1}p_2^{x_2}p_3^{x_3}
\]

Substitute:

\[
n=6,\quad x_1=3,\quad x_2=2,\quad x_3=1
\]

\[
p_1=0.40,\quad p_2=0.35,\quad p_3=0.25
\]

So:

\[
P(X_1=3,X_2=2,X_3=1)
=
\frac{6!}{3!2!1!}(0.40)^3(0.35)^2(0.25)^1
\]

---

### Step 3

Now compute the multinomial coefficient:

\[
\frac{6!}{3!2!1!}
=
\frac{720}{6 \cdot 2 \cdot 1}
=
60
\]

Now compute the powers:

\[
(0.40)^3=0.064
\]

\[
(0.35)^2=0.1225
\]

\[
(0.25)^1=0.25
\]

So:

\[
P(X_1=3,X_2=2,X_3=1)=60 \cdot 0.064 \cdot 0.1225 \cdot 0.25
\]

\[
P(X_1=3,X_2=2,X_3=1)=60 \cdot 0.00196
\]

\[
P(X_1=3,X_2=2,X_3=1)=0.1176
\]

---

## 📊 Final Summary

| Event | Formula | Result |
|------|---------|--------|
| 3 strawberry, 2 lemon, 1 mint | \(\dfrac{6!}{3!2!1!}(0.40)^3(0.35)^2(0.25)\) | \(0.1176\) |
