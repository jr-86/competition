# Question 2b

## Problem

Oliver teaches a class of six pairs of twins. He wishes to set up teams for a competition, but wants to avoid any pair of twins into the same team. Given this condition:

B. In how many ways can he split them into three teams of four?

## Solution

We'll start by calling one pair of twins Dave and Bob.

Dave must be on a team. We'll call that Team 1.

Bob must be on a team. We'll call that Team 2.

Let's call the other team Team 3.

### Filling Team 1

Dave is already on Team 1, so we have three open spots on Team 1 and 5 pairs of twins to choose from.

The first spot may be filled by any of the 10. This takes one member, and excludes their twin from joining Team 1.

Thus, there are 8 choices for the second open spot. Again, this takes a member, and excludes their twin from joining Team 1.

So there are 6 choices for the third open spot.

Therefore, there are $ 10 \cdot 8 \cdot 6 $ ways to pick the three other members of Team 1.

However, we needed to consider that these "ways to pick" are counting every order in which the participants can be picked - this is a permutation.

We need to account for this by making it a combination - dividing by the number of permutations that result in the same three participants.

There are $3!$ ways of ordering the same three participants, so the number of different possible combinations of Dave's Team 1 teammates is given by

$$
\frac{10 \cdot 8 \cdot 6}{3!} = 80
$$

### Filling Team 2

With Team 1 filled, and Bob already on Team 2, we have three open spots to fill.

Two of Bob's teammates must be from pairs of twins not selected for Team 1, to avoid them being forced into Team 3 together. There are $2 \cdot 2$ ways of choosing them, as order does not matter.

The final teammate must then be the twin of one of the three put into Team 1 alongside Dave. So the number of ways Team 2 may be filled is

$$
2 \cdot 2 \cdot 3 = 12
$$

### Filling Team 3

With 8 participants selected, only 4 are left to fill Team 3.

There is $1$ way to do this.

### Answer

Thus, the number of ways in which the three teams can be arranged is given by $ 80 \cdot 12 \cdot 1 $

The answer is `960`.
