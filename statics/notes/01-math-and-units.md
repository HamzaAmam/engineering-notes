# 1. Math and units

[Learning path](../README.md) · [Next: vectors](02-forces-and-vectors.md)

## What you need

Statics begins with algebra, right-triangle trigonometry, and consistent units. You do not need calculus for the point-load and uniform-load examples in this guide.

| Quantity | Meaning | SI unit |
| --- | --- | --- |
| Mass $m$ | Amount of matter/inertial property | kilogram, kg |
| Force $F$ | A push or pull | newton, N = kg·m/s² |
| Weight $W$ | Gravitational force | N |
| Distance $L$ | Length or lever arm | meter, m |
| Moment $M$ | Turning effect of a force | N·m |
| Load intensity $w$ | Force per length | N/m or kN/m |

Near Earth's surface, use $W=mg$, with $g=9.81\ \text{m/s}^2$ unless a problem supplies another value. Kilograms are not newtons. Also, $1\ \text{kN}=1000\ \text{N}$ and $1\ \text{m}=1000\ \text{mm}$. N·m is the conventional moment unit; although dimensionally equivalent to a joule, a moment is not energy.

## Triangle basics

For an angle $\theta$ in a right triangle:

$$\cos\theta=\frac{\text{adjacent}}{\text{hypotenuse}},\qquad
\sin\theta=\frac{\text{opposite}}{\text{hypotenuse}}.$$

The hypotenuse is $\sqrt{a^2+b^2}$. Use degree mode when the problem gives degrees. If an angle is measured from vertical, the adjacent component is vertical: do not automatically attach cosine to the horizontal axis.

## Worked example 1: mass to weight

**Given:** A 20 kg body near Earth's surface. **Find:** its weight.

$$W=(20\ \text{kg})(9.81\ \text{m/s}^2)=196.2\ \text{N}.$$

The weight vector is $(0,-196.2)$ N with up positive. The magnitude $W$ is positive; the component is negative because gravity acts downward.

**Check:** kg·m/s² is N, so the units are force units.

## Worked example 2: solve a moment equation

**Given:** $4R-600(2)=0$, where distances are in meters and the 600 is a force in newtons. **Find:** $R$.

$$4R=1200\ \text{N·m},\qquad R=\frac{1200\ \text{N·m}}{4\ \text{m}}=300\ \text{N}.$$

The coefficient 4 carries units of meters. Dividing moment by length gives force.

## Avoid these mistakes

- Converting only some distances from mm to m.
- Adding a force in N to a moment in N·m. Different quantities cannot be added.
- Rounding intermediate values aggressively; keep several digits and round the final result sensibly.

**Try next:** [P1–P2](../practice/problems.md).
