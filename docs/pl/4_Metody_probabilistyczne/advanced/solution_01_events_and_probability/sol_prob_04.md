# Task 4 — Drawing Two Cards

# Problem

Two cards are drawn from a standard deck of 52 cards.

Determine the number of possible outcomes in the following cases:

• with replacement  
• without replacement

---

# Step 1 — With replacement

With replacement means:

• draw one card  
• put it back into the deck  
• draw the second card

First draw:

52 possible cards

Second draw:

again 52 possible cards

So the total number of outcomes is:

|Ω₂| = 52 × 52 = 2704

---

# Step 2 — Without replacement

Without replacement means:

• draw one card  
• do not put it back  
• draw the second card

First draw:

52 possible cards

Second draw:

51 remaining cards

So the total number of outcomes is:

|Ω₂'| = 52 × 51 = 2652

---

# Final Result

With replacement:

|Ω₂| = 52 × 52 = 2704

Without replacement:

|Ω₂'| = 52 × 51 = 2652

---

# Quick intuition

```text
With replacement

first draw  -> 52 cards
second draw -> 52 cards

52 × 52


Without replacement

first draw  -> 52 cards
second draw -> 51 cards

52 × 51
```
