# Task 9 — Digit Restrictions

1. How many 5-digit numbers exist?  
2. How many of them are even?  
3. How many contain no repeated digits?  
4. How many contain at least one repeated digit?

---

# Step 1 — Number of all 5-digit numbers

A 5-digit number cannot start with 0.

So:

- first digit: 9 choices (1–9)
- second digit: 10 choices
- third digit: 10 choices
- fourth digit: 10 choices
- fifth digit: 10 choices

Number of all 5-digit numbers

9 · 10 · 10 · 10 · 10

= 9 · 10^4

= 90000

---

# Step 2 — Number of even 5-digit numbers

An even number must end in

0, 2, 4, 6, or 8

So the last digit has 5 choices.

The first digit still cannot be 0, so it has 9 choices.

The middle three digits can be any digits from 0 to 9, so each has 10 choices.

Number of even 5-digit numbers

9 · 10 · 10 · 10 · 5

= 45000

---

# Step 3 — Number of 5-digit numbers with no repeated digits

The first digit cannot be 0, so it has 9 choices.

After choosing the first digit:

- second digit: 9 choices
- third digit: 8 choices
- fourth digit: 7 choices
- fifth digit: 6 choices

Number of such numbers

9 · 9 · 8 · 7 · 6

= 27216

---

# Step 4 — Number of 5-digit numbers with at least one repeated digit

We use the complement method.

First count all 5-digit numbers

90000

Then subtract the numbers with no repeated digits

27216

Therefore, the number of 5-digit numbers with at least one repeated digit is

90000 - 27216

= 62784

---

## Final Result

| Situation | Result |
|-----------|--------|
| All 5-digit numbers | 9 · 10^4 = 90000 |
| Even 5-digit numbers | 9 · 10^3 · 5 = 45000 |
| 5-digit numbers with no repeated digits | 9 · 9 · 8 · 7 · 6 = 27216 |
| 5-digit numbers with at least one repeated digit | 90000 - 27216 = 62784 |
