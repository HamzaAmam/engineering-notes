# 2. Forces and vectors

[Learning path](../README.md) · [Previous](01-math-and-units.md) · [Next: FBDs](03-free-body-diagrams.md)

A force needs a magnitude, direction, and, for a rigid body, a line of action. A 100 N upward force near one end of a beam can have a different turning effect from the same force near the other end.

## Components

For a force of magnitude $F$ at angle $\theta$ measured counterclockwise from $+x$:

$$F_x=F\cos\theta,\qquad F_y=F\sin\theta,\qquad
\mathbf F=F_x\mathbf i+F_y\mathbf j.$$

$\mathbf i$ and $\mathbf j$ are unit vectors pointing along $+x$ and $+y$. If a diagram instead gives an acute angle to an axis, assign signs from the actual arrows.

To add forces, add matching components:

$$R_x=\sum F_x,\qquad R_y=\sum F_y,\qquad
R=\sqrt{R_x^2+R_y^2}.$$

Use $\theta_R=\operatorname{atan2}(R_y,R_x)$ for the correct quadrant. A calculator's ordinary $\tan^{-1}(R_y/R_x)$ needs a quadrant check and fails when $R_x=0$. A zero resultant has no defined direction.

## Worked example 1: an angled force

**Given:** A 500 N force points right and up, 30° above horizontal. **Find:** its components.

$$F_x=500\cos30^\circ=433.013\ \text{N},\qquad
F_y=500\sin30^\circ=250\ \text{N}.$$

**Check:** Both signs are positive; $\sqrt{433.013^2+250^2}\approx500$ N. The components replace the angled force in the calculation. Do not count the original force again.

## Worked example 2: force along a cable

**Given:** A cable pulls point A toward point B. Relative to A, B is 3 m left and 4 m up. Cable tension is 250 N. **Find:** force components on A.

The direction vector from A to B is $(-3,4)$ m. Its length is 5 m, so its unit vector is $(-3/5,4/5)$.

$$\mathbf F=250\left(-\frac35\mathbf i+\frac45\mathbf j\right)
=-150\mathbf i+200\mathbf j\ \text{N}.$$

**Check:** $\sqrt{150^2+200^2}=250$ N. The leftward component must be negative. The cable force on B would point toward A instead.

## Worked example 3: resultant

**Given:** $\mathbf F_1=(300,400)$ N and $\mathbf F_2=(-500,100)$ N, both applied at a ring. **Find:** the resultant.

$$\mathbf R=(-200,500)\ \text{N},\qquad R=\sqrt{(-200)^2+500^2}=538.516\ \text{N}.$$

The angle is $\operatorname{atan2}(500,-200)=111.801^\circ$ counterclockwise from $+x$.

**Check:** Left and up puts the force in quadrant II. Adding magnitudes, $500+509.902$, would give the wrong resultant.

**Try next:** [P3–P5](../practice/problems.md).
