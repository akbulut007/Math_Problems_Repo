# Task 2 — Permutations

1. In how many ways can 8 different books be arranged on a shelf?  
2. In how many ways can 8 people sit in a row if two particular people must sit next to each other?  
3. In how many ways can they sit if those two people must not sit next to each other?  
4. In how many ways can 10 questions in a test be ordered if the first question is fixed?

---

# Step 1 — Arranging 8 different books on a shelf

All 8 books are different.

We arrange all of them in a line.

Since order matters, we use permutations.

Number of arrangements

8! = 40320

---

# Step 2 — 8 people sit in a row if two particular people must sit next to each other

Let the two particular people be A and B.

If they must sit together, treat them as one block:

(A,B)

or

(B,A)

Now we have:

- 1 block
- 6 other people

So in total we arrange 7 objects.

These 7 objects can be arranged in

7!

ways.

Inside the block, A and B can switch places in

2!

ways.

Total number of arrangements

7! · 2! = 5040 · 2 = 10080

---

# Step 3 — 8 people sit in a row if those two particular people must not sit next to each other

First count all possible arrangements of 8 people

8! = 40320

From this subtract the arrangements where the two people sit together.

From Step 2, the number of arrangements where they sit next to each other is

7! · 2! = 10080

Therefore

8! - 7! · 2! = 40320 - 10080 = 30240

---

# Step 4 — Ordering 10 questions in a test if the first question is fixed

There are 10 questions in total.

The first question is already fixed, so it does not move.

That means we only arrange the remaining 9 questions.

Number of arrangements

9! = 362880

---

## Final Result

| Question | Result |
|----------|--------|
| 8 different books on a shelf | 8! = 40320 |
| 8 people in a row, two particular people must sit next to each other | 7! · 2! = 10080 |
| 8 people in a row, two particular people must not sit next to each other | 8! - 7! · 2! = 30240 |
| 10 questions ordered, first question fixed | 9! = 362880 |
