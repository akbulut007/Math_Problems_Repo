# Task 8 — Card Probabilities

# Problem

Cards are drawn from a standard deck of 52 cards.

Find the probabilities of the following events.

For one card:

• A₁ — the card is a heart  
• B₁ — the card is a king  
• C₁ — the card is not a face card  

For two cards with replacement:

• A₂ — both cards are hearts  
• B₂ — both cards have the same rank  
• C₂ — at least one card is an ace  

For two cards without replacement:

• A₃ — both cards are hearts  
• B₃ — both cards have the same rank  
• C₃ — one card is a king and the other is a queen

---

# Step 1 — One card

In a standard deck:

• hearts = 13 cards  
• kings = 4 cards  
• face cards = 12 cards  
• total cards = 52

### Event A₁ — heart

P(A₁) = 13/52 = 1/4

### Event B₁ — king

P(B₁) = 4/52 = 1/13

### Event C₁ — not a face card

Number of non-face cards:

52 - 12 = 40

P(C₁) = 40/52 = 10/13

---

# Step 2 — Two cards with replacement

With replacement means the first card is returned to the deck.

### Event A₂ — both cards are hearts

P(A₂) = (13/52) · (13/52) = 1/4 · 1/4 = 1/16

### Event B₂ — same rank

After the first card is drawn, there are 4 cards of that same rank in a full deck of 52 cards.

P(B₂) = 4/52 = 1/13

### Event C₂ — at least one ace

It is easier to use the complement.

Probability of no ace in one draw:

48/52 = 12/13

Probability of no ace in two draws:

(12/13) · (12/13) = 144/169

So:

P(C₂) = 1 - 144/169 = 25/169

---

# Step 3 — Two cards without replacement

Without replacement means the first card is not returned.

### Event A₃ — both cards are hearts

P(A₃) = (13/52) · (12/51) = 1/17

### Event B₃ — same rank

After the first card is drawn, 3 cards of the same rank remain among 51 cards.

P(B₃) = 3/51 = 1/17

### Event C₃ — one king and one queen

There are two orders:

• king then queen  
• queen then king

So:

P(C₃) = (4/52) · (4/51) + (4/52) · (4/51)

P(C₃) = 32/2652 = 8/663

---

# Final Result

P(A₁) = 1/4  
P(B₁) = 1/13  
P(C₁) = 10/13  

P(A₂) = 1/16  
P(B₂) = 1/13  
P(C₂) = 25/169  

P(A₃) = 1/17  
P(B₃) = 1/17  
P(C₃) = 8/663

---

# Quick intuition

```text
One card
heart -> 13 out of 52
king  -> 4 out of 52

With replacement
second draw uses full deck again

Without replacement
second draw uses 51 cards
```
