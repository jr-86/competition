# Question 2b

## Problem

Oliver teaches a class of six pairs of twins. He wishes to set up teams for a competition, but wants to avoid any pair of twins into the same team. Given this condition:

B. In how many ways can he split them into three teams of four?

## Solution

We'll start by calling one pair of twins A1 and A2.

A1 must be on a team. We'll call that Team 1.

A2 must be on a team. We'll call that Team 2.

Let's call the other team Team 3.

### Filling Team 1

We have three open spots on Team 1 and 5 pairs of twins to choose from.

The first spot may be filled by any of the 10. This takes one member, and excludes their twin from joining team 1.

Thus, there are 8 choices for the second open spot. Again, this takes a member, and excludes their twin from joining team 1.

So there are 6 choices for the third open spot.

Thus, there are $ 10 \cdot 8 \cdot 6 $ ways to pick the three other members of Team 1.

However, we needed to consider that these "ways to pick" are counting every order in which the participants can be picked - this is a permutation.

We need to account for this by making it a combination - dividing by the number of permutations that result in the same three participants.

There are $3!$ ways of ordering the same three participants, so the number of different possible combinations of A1's Team 1 teammates is given by

$$
\frac{10 \cdot 8 \cdot 6}{3!} = 80
$$
