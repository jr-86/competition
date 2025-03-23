# Question 2a

## Problem

Oliver teaches a class of six pairs of twins. He wishes to set up teams for a competition, but wants to avoid any pair of twins into the same team. Given this condition:

A. In how many ways can he split them into two teams of six?

## Solution

There are 6 binary choices assigning players to teams, giving $2^6$ permutations.

Each permutation will happen twice, because we don't distinguish between the teams, so we need to divide this by $2$.

$$
\frac{2^6}{2} = 2^5 = 32
$$

The answer is `32`.
