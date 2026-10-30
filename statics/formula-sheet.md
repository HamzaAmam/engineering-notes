# Statics formula sheet

[Learning path](README.md) · [Practice](practice/problems.md)

Use after learning the setup. A formula sheet cannot decide which forces belong on your FBD.

## Units and signs

Use consistent units: N and m, or kN and m. Moments are N·m or kN·m. Load intensity is force/length. In these notes: right/up/counterclockwise positive; numerical angles in degrees.

| Relation | Meaning and conditions |
| --- | --- |
| $W=mg$ | Weight magnitude; near Earth use $g=9.81\ \text{m/s}^2$ unless specified |
| $F_x=F\cos\theta$, $F_y=F\sin\theta$ | $\theta$ is measured counterclockwise from $+x$ |
| $\mathbf u_{AB}=(\mathbf r_B-\mathbf r_A)/\lVert\mathbf r_B-\mathbf r_A\rVert$ | Unit direction from A toward distinct point B |
| $\mathbf F=T\mathbf u_{AB}$ | Cable force on A pulling toward B |
| $R_x=\sum F_x$, $R_y=\sum F_y$ | Resultant force components |
| $R=\sqrt{R_x^2+R_y^2}$ | Resultant magnitude |
| $\theta_R=\operatorname{atan2}(R_y,R_x)$ | Resultant direction; undefined if $R=0$; convert radians if needed |
| $M_O=r_xF_y-r_yF_x$ | Signed planar moment; position vector starts at O |
| $|M_O|=Fd_\perp$ | Moment magnitude; choose sign by turning tendency |
| $|M_c|=Fd$ | Couple magnitude; $d$ separates parallel force lines perpendicularly |
| $F_{\mathrm{eq}}=wL$ | Uniform distributed load over length $L$; acts at loaded interval midpoint |

Particle equilibrium in 2D:

$$\sum F_x=0,\qquad\sum F_y=0.$$

Rigid-body equilibrium in 2D:

$$\sum F_x=0,\qquad\sum F_y=0,\qquad\sum M_O=0.$$

Include applied couples in the moment sum. A pin supplies two force components, a frictionless roller one normal force, and a fixed support two force components plus a reaction couple. Cable tension and compressive contact magnitudes must be nonnegative for their assumed active models.

## Last check

FBD → components → moment equation → force equations → substitute back → check physical support behavior. For particles, skip the rigid-body moment step.
