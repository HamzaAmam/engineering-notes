# 4. Moments and couples

[Learning path](../README.md) · [Previous](03-free-body-diagrams.md) · [Next: supports](05-supports-and-loads.md)

A moment measures how strongly a force tends to rotate a body about a point or axis. Pushing a door near its hinge is less effective than pushing farther away.

## Two ways to compute a planar moment

Magnitude:

$$|M_O|=F d_\perp.$$

$d_\perp$ is the shortest, perpendicular distance from O to the force's **line of action**. It is not automatically the distance to the point where the force is applied. Choose the sign by the turning direction: counterclockwise positive here.

Using components, with $\mathbf r=(r_x,r_y)$ from O to any point on the force's line of action:

$$M_O=r_xF_y-r_yF_x.$$

This is the out-of-plane component of $\mathbf r\times\mathbf F$. A force whose line of action passes through O has zero moment about O even if its magnitude is large.

## Worked example 1: perpendicular load

**Given:** A 200 N downward force acts 3 m right of O. **Find:** its moment about O.

$$M_O=(3)(-200)-(0)(0)=-600\ \text{N·m}.$$

It turns clockwise, so the negative sign agrees with the drawing. Magnitude check: $Fd_\perp=200(3)=600$ N·m.

## Worked example 2: a force with two components

**Given:** Relative to O, the application point is $(2,1)$ m; the force is $(100,-150)$ N.

$$M_O=(2)(-150)-(1)(100)=-400\ \text{N·m}.$$

The downward component gives $-300$ N·m and the rightward component above O gives $-100$ N·m. Both turn clockwise. Ignoring the height would miss the second contribution.

## Couples

A couple consists of equal and opposite parallel forces on different lines of action. Its net force is zero but its net moment is generally not:

$$|M_c|=Fd,$$

where $d$ is the perpendicular separation between the lines. An applied couple contributes the same moment about every reference point. Moving a single force sideways is different: it changes the moment unless a compensating couple is added.

## Worked example 3: pure couple

**Given:** A 50 N upward force at $x=0$ and a 50 N downward force at $x=0.4$ m, both at $y=0$.

$$\sum\mathbf F=\mathbf0,\qquad M_c=0(50)+0.4(-50)=-20\ \text{N·m}.$$

About $x=1$ m, the moment is $(-1)(50)+(-0.6)(-50)=-20$ N·m again. Thus zero net force alone does not establish rigid-body equilibrium.

**Try next:** [P7–P9](../practice/problems.md).
