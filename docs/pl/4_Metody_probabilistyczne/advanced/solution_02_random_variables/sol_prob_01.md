# Task 1 — Recognizing Counting Models

Determine which combinatorial model applies in each situation.

Models
- permutation
- circular permutation
- combination
- k-permutation
- sequence with repetition
- permutation with repeated elements


------------------------------------------------
Step 1 — Arranging 7 students in a line
------------------------------------------------

We use all students.

Order matters because different orders create different arrangements.

Example

ABCDEF G
GFEDCBA

These are different.

No repetition is allowed because each student appears once.

Model

Permutation

Formula

7!


------------------------------------------------
Step 2 — Choosing 4 members of a committee from 12 people
------------------------------------------------

We choose only some of the people.

Order does not matter.

Example

{A,B,C,D}
{D,C,B,A}

These represent the same committee.

Model

Combination

Formula

C(12,4)


------------------------------------------------
Step 3 — Assigning gold, silver and bronze medals among 15 athletes
------------------------------------------------

We choose 3 athletes from 15.

Order matters because

Gold ≠ Silver ≠ Bronze.

Example

(A,B,C)
(C,B,A)

These represent different results.

Repetition is not allowed.

Model

k-permutation

Formula

P(15,3)


------------------------------------------------
Step 4 — Forming a 6-digit PIN code
------------------------------------------------

We create a sequence of digits.

Order matters.

Example

123456
654321

Different codes.

Digits may repeat.

Example

111111

Model

Sequence with repetition

Number of outcomes

10^6


------------------------------------------------
Step 5 — Arranging the letters of BANANA
------------------------------------------------

Letters

B A N A N A

Total letters = 6

Repeated letters

A appears 3 times
N appears 2 times

Model

Permutation with repeated elements

Formula

6! / (3! 2!)


------------------------------------------------
Step 6 — Seating 6 people around a round table
------------------------------------------------

All people are used.

The arrangement is circular.

Rotations are considered the same.

Example

A B C D E F
B C D E F A

These represent the same seating.

Model

Circular permutation

Formula

(6 - 1)! = 5!


# Quick intuition
text
One card
heart -> 13 out of 52
king  -> 4 out of 52

With replacement
second draw uses full deck again

Without replacement
second draw uses 51 cards
