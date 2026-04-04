# 🔢 Task 3 — Geometric Model (Waiting for the First Event)

## ✅ Solution

### Step 1

Each printed page can be:

- E = page contains an error
- N = page contains no error

The probability that a page contains an error is:

\[
P(E)=p, \quad P(N)=1-p
\]

Pages are independent, and we observe consecutive pages until the **first error** appears.

So this is a **geometric experiment**.

---

### Step 2

The sample space consists of all sequences that end with the **first error**:

\[
Ω=\{E,\;NE,\;NNE,\;NNNE,\;NNNNE,\;\dots\}
\]

This means:

- \(E\) = the first page already has an error
- \(NE\) = the first page has no error, the second page has an error
- \(NNE\) = the first two pages have no error, the third page has an error
- and so on

So the sample space is infinite.

---

### Step 3

Let:

\[
X=\text{number of pages observed until the first error}
\]

Then the possible values of \(X\) are:

\[
X \in \{1,2,3,\dots\}
\]

For the first error to appear on the \(k\)-th page:

- the first \(k-1\) pages must contain no error
- the \(k\)-th page must contain an error

Therefore:

\[
P(X=k)=(1-p)^{k-1}p, \qquad k=1,2,3,\dots
\]

This is the **geometric distribution**.

---

### Step 4

In this model, a **success** means:

\[
\text{a page contains an error}
\]

So the geometric random variable counts how many pages are observed until the first success.

Thus:

\[
X \sim \mathrm{Geometric}(p)
\]

---

## 📊 Final Summary

| Item | Result |
|------|--------|
| Model | Geometric |
| Outcomes per page | Error / No error |
| Success | A page contains an error |
| Sample space | \(Ω=\{E,NE,NNE,NNNE,\dots\}\) |
| Random variable | \(X=\) number of pages until the first error |
| Possible values of \(X\) | \(\{1,2,3,\dots\}\) |
| Probability distribution | \(P(X=k)=(1-p)^{k-1}p\) |
