Task 4 — Circular Permutations
1. In how many ways can 7 people sit around a round table?

When people sit around a round table, arrangements that differ only by rotation are counted as the same.

So instead of counting all 
7
!
7! linear arrangements, we use the circular permutation formula:

(
7
−
1
)
!
=
6
!
=
720
(7−1)!=6!=720

So the number of ways is:

720
720
	​

2. In how many ways can they sit if two particular people must sit next to each other?

Let the two particular people be A and B.

If they must sit together, we treat them as one single block:

(
𝐴
,
𝐵
)
or
(
𝐵
,
𝐴
)
(A,B)or(B,A)

Now instead of 7 separate people, we have:

1 block
5 other people

So there are 6 objects around the table.

The number of circular arrangements of 6 objects is:

(
6
−
1
)
!
=
5
!
=
120
(6−1)!=5!=120

But inside the block, A and B can switch places in:

2
 ways
2 ways

Therefore the total number of arrangements is:

5
!
⋅
2
=
120
⋅
2
=
240
5!⋅2=120⋅2=240

So the answer is:

240
240
	​

3. In how many ways can they sit if those two people must sit opposite each other?

Let one of the two particular people be fixed first.

This removes rotational symmetry, which is standard in circular arrangements.

Once that person is fixed, the other particular person must sit in the seat directly opposite.
There is only one such seat.

So both of their positions are now determined.

That leaves the remaining 5 people to be arranged in the remaining 5 seats:

5
!
=
120
5!=120

So the number of arrangements is:

120
120
	​

## Final Result

Around a round table: 
(
7
−
1
)
!
=
6
!
=
720
Around a round table: (7−1)!=6!=
720
	​

Two particular people next to each other: 
5
!
⋅
2
=
240
Two particular people next to each other: 5!⋅2=
240
	​

Two particular people opposite each other: 
5
!
=
120
Two particular people opposite each other: 5!=
120
