# Task 3 — Permutations with Repeated Elements

1. How many distinct arrangements of the word MISSISSIPPI are possible?  
2. How many distinct arrangements of the word STATISTICS are possible?  
3. How many of the arrangements of STATISTICS start with the letter S?

---

# Step 1 — Arrangements of MISSISSIPPI

Word

MISSISSIPPI

Total number of letters

11

Repeated letters

M = 1  
I = 4  
S = 4  
P = 2

If all letters were different, the number of arrangements would be

11!

But the repeated letters are indistinguishable, so we divide by

4! for I,  
4! for S,  
2! for P.

Number of distinct arrangements

11! / (4! · 4! · 2!)

= 39916800 / (24 · 24 · 2)

= 39916800 / 1152

= 34650

---

# Step 2 — Arrangements of STATISTICS

Word

STATISTICS

Total number of letters

10

Repeated letters

S = 3  
T = 3  
I = 2  
A = 1  
C = 1

If all letters were different, the number of arrangements would be

10!

Because some letters repeat, we divide by

3! for S,  
3! for T,  
2! for I.

Number of distinct arrangements

10! / (3! · 3! · 2!)

= 3628800 / (6 · 6 · 2)

= 3628800 / 72

= 50400

---

# Step 3 — Arrangements of STATISTICS that start with S

We fix the first letter as S.

So we arrange only the remaining letters.

Remaining letters

T A T I S T I C S

Total remaining letters

9

Repeated letters among them

T = 3  
S = 2  
I = 2  
A = 1  
C = 1

If all 9 remaining letters were different, the number of arrangements would be

9!

Because some letters repeat, we divide by

3! for T,  
2! for S,  
2! for I.

Number of distinct arrangements

9! / (3! · 2! · 2!)

= 362880 / (6 · 2 · 2)

= 362880 / 24

= 15120

---

## Final Result

| Situation | Result |
|-----------|--------|
| Arrangements of MISSISSIPPI | 11! / (4! · 4! · 2!) = 34650 |
| Arrangements of STATISTICS | 10! / (3! · 3! · 2!) = 50400 |
| Arrangements of STATISTICS starting with S | 9! / (3! · 2! · 2!) = 15120 |
