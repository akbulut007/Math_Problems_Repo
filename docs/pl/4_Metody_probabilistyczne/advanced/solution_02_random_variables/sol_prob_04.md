# Task 4 — Circular Permutations

1. In how many ways can 7 people sit around a round table?  
2. In how many ways can they sit if two particular people must sit next to each other?  
3. In how many ways can they sit if those two people must sit opposite each other?

---

# Step 1 — 7 people sit around a round table

For circular arrangements, rotations are considered the same.

So the number of ways to arrange 7 people around a round table is

(7 - 1)!

= 6!

= 720

---

# Step 2 — Two particular people must sit next to each other

Let the two particular people be A and B.

If they must sit next to each other, treat them as one block:

(A,B)

or

(B,A)

Now we have:

- 1 block
- 5 other people

So in total we have 6 objects around the table.

The number of circular arrangements of 6 objects is

(6 - 1)! = 5!

Inside the block, A and B can switch places in

2

ways.

So the total number of arrangements is

5! · 2

= 120 · 2

= 240

---

# Step 3 — Two particular people must sit opposite each other

Let one of the two particular people be fixed.

In a circular arrangement, we can fix one person's position to remove rotational symmetry.

Then the second particular person must sit exactly opposite.

Since there is only one opposite seat, that position is fixed.

Now the remaining 5 people can be arranged in the remaining 5 seats in

5!

ways.

So the total number of arrangements is

5!

= 120

---

## Final Result

| Situation | Result |
|-----------|--------|
| 7 people around a round table | 6! = 720 |
| Two particular people must sit next to each other | 5! · 2 = 240 |
| Two particular people must sit opposite each other | 5! = 120 |
