# 6. Two-dimensional equilibrium

[Learning path](../README.md) · [Previous](05-supports-and-loads.md) · [Next: practice](../practice/problems.md)

## Which equations apply?

For a particle with coplanar forces:

$$\sum F_x=0,\qquad\sum F_y=0.$$

For a rigid body under coplanar loading:

$$\sum F_x=0,\qquad\sum F_y=0,\qquad\sum M_O=0.$$

O can be any point. The first two equations prevent translational acceleration; the third prevents angular acceleration. All three must hold for rigid-body equilibrium. Extra moment equations are useful checks, but do not give more than three independent planar equilibrium equations for one rigid body.

## Repeatable procedure

1. Draw and label the FBD.
2. Resolve angled forces into signed components.
3. Count unknowns and identify independent equations. If there are too many unknowns, look for additional valid bodies/relations; do not invent restraints.
4. Choose a moment center that eliminates convenient unknowns. A force through the center has zero moment about it.
5. Solve, keeping units.
6. Substitute into all equilibrium equations and check physical constraints such as tension and contact.

## Worked example 1: two cables supporting a ring

**Given:** A weightless ring supports a 100 N downward load. The left cable pulls 30° above the leftward horizontal; the right cable pulls 60° above the rightward horizontal. **Find:** tensions $T_L,T_R$.

Treat the ring as a particle. Its three forces are the two cable tensions, pointing away from the ring, and the load downward.

$$\sum F_x=-T_L\cos30^\circ+T_R\cos60^\circ=0.$$

Thus $T_R=(\cos30^\circ/\cos60^\circ)T_L=\sqrt3T_L$.

$$\sum F_y=T_L\sin30^\circ+T_R\sin60^\circ-100=0.$$

Substitute: $0.5T_L+(\sqrt3T_L)(\sqrt3/2)=100$, so $2T_L=100$.

$$T_L=50\ \text{N},\qquad T_R=86.603\ \text{N}.$$

**Check:** Horizontal components are $-43.301$ and $+43.301$ N; vertical components are 25 and 75 N. Both tensions are positive and the upward sum is 100 N.

## Worked example 2: pin-and-roller beam

**Given:** The weightless 4 m beam from lesson 3: pin A at $(0,0)$ m, roller B at $(4,0)$ m on a horizontal floor, 600 N downward at $(1,0)$ m. **Find:** support reactions.

FBD unknowns: $A_x$ right, $A_y$ up, $B_y$ up. Take moments about A to eliminate both A reactions:

$$\sum M_A=4B_y-600(1)=0\Rightarrow B_y=150\ \text{N}.$$
$$\sum F_y=A_y+B_y-600=0\Rightarrow A_y=450\ \text{N}.$$
$$\sum F_x=A_x=0.$$

**Independent check about B:** $-4(450)+(-3)(-600)=0$ N·m. The support closer to the load carries more of it, which fits the geometry.

## Worked example 3: angled load and beam weight

**Given:** A uniform horizontal beam is 5 m long and weighs 200 N. It has a pin at A, $x=0$, and a roller on a horizontal floor at B, $x=5$ m. A 500 N load acts at $x=3$ m, directed 30° below $+x$. All force application points lie at $y=0$. **Find:** support reactions.

FBD: $A_x,A_y,B_y$, beam weight 200 N downward at $x=2.5$ m, and the angled load at $x=3$ m.

Load components: $F_x=500\cos30^\circ=433.013$ N and $F_y=-500\sin30^\circ=-250$ N.

$$\sum M_A=5B_y-200(2.5)-250(3)=0\Rightarrow B_y=250\ \text{N}.$$

The horizontal component has zero moment about A because its line of action is at $y=0$.

$$\sum F_y=A_y+250-200-250=0\Rightarrow A_y=200\ \text{N},$$
$$\sum F_x=A_x+433.013=0\Rightarrow A_x=-433.013\ \text{N}.$$

Thus A exerts 433.013 N left and 200 N up; B exerts 250 N up.

**Check about B:** $-5(200)+(-2.5)(-200)+(-2)(-250)=0$ N·m. The negative $A_x$ is an ordinary direction correction, not a failure of the pin model.

## When equations are not enough

More than three unknown reactions on a single planar body generally requires extra information, such as member deformation, to determine all reactions; count independent equations and inspect geometry. Conversely, too few independent restraints may make equilibrium impossible under the given loading. Equilibrium calculations alone also do not establish structural strength or buckling safety.

**Try next:** [P12–P16](../practice/problems.md), then consult the [answers](../practice/answers.md).
