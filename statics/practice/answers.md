# Worked practice answers

[Problems](problems.md) · [Learning path](../README.md)

Answers use right/up/counterclockwise positive. Rounded values may leave small residuals. Use unrounded values in checks.

## P1 — Weight

$$W=mg=12(9.81)=117.72\ \text{N}.$$

It acts vertically downward: $\mathbf W=(0,-117.72)$ N. Mass remains 12 kg.

## P2 — Convert length before computing moment

$$250\ \text{mm}=0.250\ \text{m},\qquad M_O=(0.250)(-400)=-100\ \text{N·m}.$$

The force turns the arm clockwise. Using 250 with meters would overstate the moment by a factor of 1000.

## P3 — Angle is measured from vertical

$$F_x=200\sin30^\circ=100\ \text{N},\qquad
F_y=200\cos30^\circ=173.205\ \text{N}.$$

Both are positive. Check: $\sqrt{100^2+(100\sqrt3)^2}=200$ N.

## P4 — Normalize the cable direction

Distance AB is $\sqrt{6^2+8^2}=10$ m. The unit vector is $(0.6,0.8)$, so

$$\mathbf F_A=500(0.6\mathbf i+0.8\mathbf j)=300\mathbf i+400\mathbf j\ \text{N}.$$

Check: $\sqrt{300^2+400^2}=500$ N; the arrow points from A toward B.

## P5 — Add components, then find magnitude

$$R_x=120-40=80\ \text{N},\qquad R_y=-50+110=60\ \text{N},$$
$$R=\sqrt{80^2+60^2}=100\ \text{N},\qquad
\theta=\operatorname{atan2}(60,80)=36.870^\circ.$$

Check: $100\cos\theta=80$ N and $100\sin\theta=60$ N.

## P6 — FBD inventory

| External interaction | Location | Force on beam |
| --- | --- | --- |
| Pin A | $x=0$ | Unknown $A_x$ right and $A_y$ up, as assumed arrows |
| Roller B | $x=4$ m | Unknown $B_y$ up; no horizontal reaction or reaction couple |
| Gravity | $x=2$ m | $W=10(9.81)=98.1$ N down |
| Cable | $x=2$ m | $T_x=40\cos45^\circ=28.284$ N right; $T_y=40\sin45^\circ=28.284$ N up |

Show the cable either as one angled 40 N arrow or as its two components, never both in the force sums. The pin allows rotation and supplies no couple. The support forces the beam exerts on the floor/pin do not belong on this FBD.

## P7 — Both components contribute to moment

$$M_O=r_xF_y-r_yF_x=3(-80)-2(60)=-360\ \text{N·m}.$$

Both components turn clockwise: $-240-120=-360$ N·m.

## P8 — Line of action passes through O

$$M_O=2(0)-0(150)=0\ \text{N·m}.$$

The force acts along the x-axis through O, so the perpendicular lever arm is zero. The application point being 2 m from O does not make the perpendicular lever arm 2 m.

## P9 — Zero force, nonzero moment

$$\sum F_y=-100+100=0,\qquad\sum F_x=0,$$
$$M_O=0(-100)+0.3(100)=+30\ \text{N·m}.$$

The couple is counterclockwise, with the same net moment about any point. These forces alone do not put a rigid body in equilibrium.

## P10 — Normal to the surface

The up-left normal is at $30^\circ+90^\circ=120^\circ$ from $+x$.

$$R_x=R\cos120^\circ=-0.5R,\qquad
R_y=R\sin120^\circ=\frac{\sqrt3}{2}R\approx0.866025R.$$

Check perpendicularity using the surface unit tangent $(\cos30^\circ,\sin30^\circ)$: its dot product with $(-0.5,\sqrt3/2)$ is zero.

## P11 — Load intensity times loaded length

$$L=6-2=4\ \text{m},\qquad F_{\mathrm{eq}}=3(4)=12\ \text{kN}\text{ downward},$$
$$x_{\mathrm{eq}}=2+4/2=4\ \text{m},\qquad M_0=-12(4)=-48\ \text{kN·m}.$$

The resultant acts at the midpoint because this distribution is uniform.

## P12 — Symmetric ring

FBD: $T_L$ left/up, $T_R$ right/up, 200 N down.

$$\sum F_x=-T_L\cos45^\circ+T_R\cos45^\circ=0\Rightarrow T_L=T_R=T,$$
$$\sum F_y=2T\sin45^\circ-200=0\Rightarrow
T=100\sqrt2=141.421\ \text{N}.$$

Check: Each cable contributes 100 N upward; its horizontal component is 100 N, canceling the other cable's horizontal component.

## P13 — Pin-and-roller beam

FBD: $A_x,A_y$ at A, $B_y$ at B, and 800 N down at $x=2$ m.

$$\sum M_A=6B_y-800(2)=0\Rightarrow B_y=266.667\ \text{N},$$
$$\sum F_y=A_y+B_y-800=0\Rightarrow A_y=533.333\ \text{N},$$
$$\sum F_x=A_x=0.$$

Check about B: $-6(533.333\ldots)+(-4)(-800)=0$ N·m.

## P14 — Fixed support with applied couple

FBD: $A_x,A_y,M_A$ at A; end load 400 N down; applied couple $-200$ N·m. The couple enters directly, without multiplying by a distance.

$$\sum F_x=A_x=0,\qquad\sum F_y=A_y-400=0\Rightarrow A_y=400\ \text{N},$$
$$\sum M_A=M_A-400(3)-200=0\Rightarrow M_A=1400\ \text{N·m}.$$

$M_A$ is counterclockwise. Check about the free end: $1400-400(3)-200=0$ N·m; the end force has zero moment there, while $A_y$ contributes $-1200$ N·m.

## P15 — Uniform load plus point load

Replace the uniform load by $2(6)=12$ kN downward at $x=3$ m. FBD also includes 6 kN down at $x=4$ m and the three support components.

$$\sum M_A=6B_y-12(3)-6(4)=0\Rightarrow B_y=10\ \text{kN},$$
$$\sum F_y=A_y+10-12-6=0\Rightarrow A_y=8\ \text{kN},$$
$$\sum F_x=A_x=0.$$

Check about B: $-6(8)+(-3)(-12)+(-2)(-6)=0$ kN·m.

## P16 — Algebraic result versus valid contact

FBD under the assumed contact: $A_x,A_y$ at A, $B_y$ up at $x=2$ m, and 100 N up at $x=4$ m.

$$\sum M_A=2B_y+100(4)=0\Rightarrow B_y=-200\ \text{N},$$
$$\sum F_y=A_y-200+100=0\Rightarrow A_y=100\ \text{N},\qquad A_x=0.$$

These algebraic values balance the equations, but require B to pull down. An unrestrained roller on a floor cannot do that. The assumed contact equilibrium is impossible. With contact lost, $B_y=0$ and the upward load leaves $+400$ N·m about the pin; no static equilibrium exists in the stated horizontal configuration. A hold-down connection would be a different physical model.
