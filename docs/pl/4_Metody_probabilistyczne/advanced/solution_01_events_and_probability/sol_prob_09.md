# Task 9 — Weekly Weather Probabilities

# Problem

The weather is observed for 7 days.

Each day can be:

• S — sunny  
• C — cloudy  
• R — rainy

Assume that each type of weather is equally likely, so:

P(S) = P(C) = P(R) = 1/3

Find the probabilities of the following events:

• A — the entire weekend is sunny  
• B — Wednesday, Thursday, and Friday are rainy  
• C — at least one day during the week is sunny  
• D — no rainy day occurs during the week  
• E — exactly two days are sunny

---

# Step 1 — Basic idea

Each day is independent.

For one day:

P(S) = 1/3  
P(C) = 1/3  
P(R) = 1/3

So we multiply probabilities for several fixed days.

---

# Step 2 — Event A

A = the weekend is sunny.

This means:

• Saturday is sunny  
• Sunday is sunny

So:

P(A) = (1/3) · (1/3) = 1/9

---

# Step 3 — Event B

B = Wednesday, Thursday, and Friday are rainy.

So:

P(B) = (1/3) · (1/3) · (1/3) = (1/3)³ = 1/27

---

# Step 4 — Event C

C = at least one day is sunny.

It is easier to use the complement:

no sunny day

If a day is not sunny, then it is cloudy or rainy.

So for one day:

P(not sunny) = 2/3

For 7 days:

P(no sunny day) = (2/3)⁷

Therefore:

P(C) = 1 - (2/3)⁷

---

# Step 5 — Event D

D = no rainy day occurs.

So every day must be:

• sunny or cloudy

For one day:

P(not rainy) = 2/3

For 7 days:

P(D) = (2/3)⁷

---

# Step 6 — Event E

E = exactly two sunny days occur.

First choose which 2 of the 7 days are sunny:

C(7,2) = 21

For one such choice:

• 2 sunny days → (1/3)²  
• 5 non-sunny days → (2/3)⁵

So:

P(E) = C(7,2) · (1/3)² · (2/3)⁵

P(E) = 21 · (1/9) · (32/243)

P(E) = 224/729

---

# Final Result

P(A) = 1/9  
P(B) = 1/27  
P(C) = 1 - (2/3)⁷  
P(D) = (2/3)⁷  
P(E) = 224/729

---

# Quick intuition

```text
Weekend sunny
S on Saturday
S on Sunday
-> (1/3)(1/3)

At least one sunny
= 1 - no sunny day

No rainy day
each day is S or C
-> (2/3)^7

Exactly two sunny days
choose 2 days from 7
-> C(7,2)
```
