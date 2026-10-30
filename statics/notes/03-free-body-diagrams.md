# 3. Free-body diagrams (FBDs)

[Learning path](../README.md) · [Previous](02-forces-and-vectors.md) · [Next: moments](04-moments-and-couples.md)

An FBD is a drawing of **one isolated body and all external forces and applied couples acting on it**. It is the physical model behind your equations. A correct calculation cannot rescue a missing force.

## Build one in this order

1. Choose the system: one ring, one beam, or an entire assembly. Name it.
2. Draw its outline alone. Remove the surrounding objects.
3. Replace every removed contact or connection with the appropriate reaction force(s) or moment.
4. Add specified loads and weight if included in the problem. If weight is neglected, say so. Put weight at the center of gravity; use the midpoint only for a uniform member in uniform gravity.
5. Label directions, unknowns, coordinates, dimensions, and angles. Locations matter for moments.
6. Check each interaction: what external object exerts this force on the chosen body?

You may assume a direction for an unknown reaction. A negative answer means the actual direction is opposite your assumed arrow, provided that the support can physically exert it.

## Worked example: hanging light

**Given:** A light of weight 100 N hangs at rest from an ideal vertical cable. **System:** the light alone. **Find:** cable tension.

Its FBD has two arrows: tension $T$ upward at the cable attachment and weight 100 N downward through the center of gravity. Choose up positive.

$$\sum F_y=T-100=0\quad\Rightarrow\quad T=100\ \text{N}.$$

**Check:** Net vertical force is zero. There is no horizontal force in this model. The arrows are collinear, so no unbalanced turning effect remains.

The downward force the light exerts on the cable belongs on the **cable's** FBD, not the light's. Newton's third-law pairs act on different bodies and do not cancel each other on one body's FBD.

## Beam FBD example: setting up before solving

**Given:** A weightless horizontal beam AB, length 4 m, has a pin at A, a roller on a horizontal floor at B, and a 600 N downward load 1 m right of A.

Draw the isolated beam with:

- $A_x$ to the right and $A_y$ up at A;
- $B_y$ up at B; the floor is horizontal, so its normal is vertical;
- the 600 N downward load at $x=1$ m;
- $x_A=0$, $x_B=4$ m, and the chosen axes.

Do not draw a pin reaction moment or a horizontal roller force. Those would add restraints absent from this ideal model. The full solution appears in [lesson 6](06-equilibrium.md).

## External versus internal

For an entire connected assembly, forces between its own members are internal and do not appear on the whole-assembly FBD. Isolate a single member and those connection forces become external to that member.

**Try next:** [P6](../practice/problems.md). Describe the FBD before writing equations.
