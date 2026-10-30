# 5. Supports and load models

[Learning path](../README.md) · [Previous](04-moments-and-couples.md) · [Next: equilibrium](06-equilibrium.md)

A support reaction represents what a connection can exert on the isolated body. Model the allowed motion before choosing unknowns.

## Ideal supports in two dimensions

| Connection | Reactions on body | Modeling assumption |
| --- | --- | --- |
| Pin/hinge | $A_x,A_y$ | Prevents translation, allows rotation; no reaction couple |
| Roller or smooth contact | One normal force | Frictionless; permits tangential motion and rotation |
| Fixed support | $A_x,A_y,M_A$ | Prevents planar translation and rotation |
| Ideal flexible cable | Tension along cable | Pulls away from body; cannot push |
| Ideal two-force member | Force along line joining its two force application points | Only two external forces, no applied couple, in equilibrium |

A roller on a slope reacts **normal to that slope**, not necessarily vertically. An ordinary unrestrained contact can push but cannot pull the body toward the surface. A negative normal-force result may mean loss of contact. A negative tension means the assumed taut-cable equilibrium is not physically possible under that model; a cable cannot carry compression.

Three unknown reactions do not automatically guarantee solvability. Geometry and support arrangement must also prevent unconstrained motion; for example, three parallel reaction directions cannot resist an arbitrary horizontal load.

## Point loads and distributed loads

A point load idealizes a force acting at one location. A distributed load acts over length. For a uniform downward intensity $w$ over length $L$, its equivalent resultant is

$$F_{\mathrm{eq}}=wL,$$

acting downward at the midpoint of the loaded interval. This replacement preserves external resultant force and moment for equilibrium. It does not reproduce the internal loading at every section.

## Worked example 1: uniform distributed load

**Given:** $w=2\ \text{kN/m}$ downward from $x=1$ m to $x=4$ m on a beam. **Find:** equivalent point load.

Loaded length $L=4-1=3$ m, so

$$F_{\mathrm{eq}}=2(3)=6\ \text{kN},\qquad x_{\mathrm{eq}}=1+\frac32=2.5\ \text{m}.$$

About $x=0$, its moment is $-6(2.5)=-15$ kN·m. Use the center of the **loaded interval**, not the center of the entire beam.

## Worked example 2: a fixed support

**Given:** A weightless horizontal cantilever extends 2 m right from fixed support A. A 300 N downward load acts at the free end. **Find:** reactions.

FBD: $A_x$, $A_y$, reaction couple $M_A$, and the end load. Assume right/up/counterclockwise positive.

$$\sum F_x=A_x=0,$$
$$\sum F_y=A_y-300=0\Rightarrow A_y=300\ \text{N},$$
$$\sum M_A=M_A-300(2)=0\Rightarrow M_A=600\ \text{N·m}.$$

**Check:** The upward reaction balances the force; the counterclockwise reaction couple balances the clockwise load moment. A pin at A alone could not supply that couple.

**Try next:** [P10–P11](../practice/problems.md).
