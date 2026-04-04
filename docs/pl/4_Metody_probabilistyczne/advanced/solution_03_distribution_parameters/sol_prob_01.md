# 🔢 Task 1 — Binomial Model (Quality Control)

## Step 1

We inspect **3 consecutive screws**.

Each screw can be:

- **G** = good
- **D** = defective

The probability that a screw is defective is:

\[
p
\]

So the probability that a screw is good is:

\[
1-p
\]

The inspections are independent.

---

## Step 2

Each of the 3 screws has **2 possible outcomes**.

So the sample space is:

\[
\Omega = \{GGG, GGD, GDG, DGG, GDD, DGD, DDG, DDD\}
\]

Number of all possible outcomes:

\[
2^3 = 8
\]

---

## Step 3

Now we assign probabilities to the sample points.

Since the inspections are independent, we multiply the probabilities.

For example:

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

## Step 4

In this model, a **success** means:

\[
\text{a defective screw}
\]

Let \(X\) be the number of defective screws among the 3 inspected screws.

Then the random variable has binomial distribution:

\[
X \sim \mathrm{Binomial}(3,p)
\]

---

## 📊 Final Summary

| Step | Result |
|------|--------|
| Step 1 | 3 independent screw inspections |
| Step 2 | \(\Omega = \{GGG, GGD, GDG, DGG, GDD, DGD, DDG, DDD\}\) |
| Step 3 | Probabilities are found by multiplication |
| Step 4 | Success = defective screw |
| Model | \(X \sim \mathrm{Binomial}(3,p)\) |
