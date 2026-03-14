# Task 8 — Sequences with Repetition

1. How many 5-digit PIN codes are possible if digits may repeat?  
2. How many such codes contain at least one repeated digit?  
3. How many such codes have all digits different?

---

# Step 1 — Number of all 5-digit PIN codes

A PIN code uses digits

0, 1, 2, 3, 4, 5, 6, 7, 8, 9

So each position has 10 possible choices.

Since the PIN has 5 digits and repetition is allowed, we use the product rule.

Number of all possible PIN codes

10 · 10 · 10 · 10 · 10

= 10^5

= 100000

---

# Step 2 — Number of 5-digit PIN codes with all digits different

We now count the codes in which no digit is repeated.

For the first digit, we have 10 choices.  
For the second digit, we have 9 choices.  
For the third digit, we have 8 choices.  
For the fourth digit, we have 7 choices.  
For the fifth digit, we have 6 choices.

Number of such PIN codes

10 · 9 · 8 · 7 · 6

= 30240

---

# Step 3 — Number of 5-digit PIN codes with at least one repeated digit

We use the complement method.

First count all PIN codes

10^5 = 100000

Then subtract the PIN codes with all digits different

10 · 9 · 8 · 7 · 6 = 30240

Therefore, the number of PIN codes with at least one repeated digit is

100000 - 30240

= 69760

---

## Final Result

| Situation | Result |
|-----------|--------|
| All 5-digit PIN codes | 10^5 = 100000 |
| 5-digit PIN codes with at least one repeated digit | 10^5 - (10 · 9 · 8 · 7 · 6) = 69760 |
| 5-digit PIN codes with all digits different | 10 · 9 · 8 · 7 · 6 = 30240 |
