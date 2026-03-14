# Task 6 — Combinations in Card Problems

A standard deck contains 52 cards.

1. In how many ways can 5 cards be drawn so that the hand contains exactly 2 hearts?  
2. In how many ways can a 5-card hand contain at least one heart?  
3. In how many ways can a 5-card hand contain no face cards (J, Q, K)?

---

# Step 1 — A 5-card hand contains exactly 2 hearts

A deck has

- 13 hearts
- 39 non-hearts

We want exactly 2 hearts in a 5-card hand.

So we choose

- 2 cards from the 13 hearts
- 3 cards from the 39 non-hearts

Number of hands

C(13,2) · C(39,3)

= 78 · 9139

= 712842

---

# Step 2 — A 5-card hand contains at least one heart

First count all possible 5-card hands.

C(52,5)

= 2598960

Now subtract the hands with no hearts.

If there are no hearts, then all 5 cards must come from the 39 non-hearts.

Number of hands with no hearts

C(39,5)

= 575757

Therefore, the number of hands with at least one heart is

C(52,5) - C(39,5)

= 2598960 - 575757

= 2023203

---

# Step 3 — A 5-card hand contains no face cards

Face cards are

J, Q, K

There are 3 face cards in each of the 4 suits.

So the number of face cards is

3 · 4 = 12

Therefore, the number of non-face cards is

52 - 12 = 40

We want all 5 cards to be chosen from these 40 non-face cards.

Number of hands

C(40,5)

= 658008

---

## Final Result

| Situation | Result |
|-----------|--------|
| 5-card hand with exactly 2 hearts | C(13,2) · C(39,3) = 712842 |
| 5-card hand with at least one heart | C(52,5) - C(39,5) = 2023203 |
| 5-card hand with no face cards | C(40,5) = 658008 |
