---
markmap:
  colorFreezeLevel: 3
---

# Rotation

## I. Introduction to Rigid Bodies and Types of Motion
### A. Definition and Characteristics of a Rigid Body
#### Idealization of a Rigid Body
##### a. Defined as a collection of particles where the distance between any two particles remains unchanged under any conditions or applied force1.
##### b. In reality, bodies deform (like a tire), but for the syllabus, bodies are assumed to be ideal and rigid1.
#### Kinematic Constraints
##### a. The velocity of particles along the line joining them must be the same to maintain a fixed distance ($v_1 \cos \alpha = v_2 \cos \beta$)1.
##### b. Particles can possess angular velocity relative to one another, but the linear distance is constant1.
### B. Classification of Motion
#### Pure Translational Motion
##### a. Every particle in the body undergoes the same displacement in any given time interval1.
##### b. Examples include a block sliding or a wheel skidding without rotating1.
#### Pure Rotational Motion (Fixed Axis)
##### a. The body rotates about a fixed axis where every particle executes circular motion around that axis1.
##### b. The angular displacement is the same for every particle, though linear velocities vary with radius ($v = r\omega$)8.
#### Combined Translational and Rotational Motion (CTRM)
##### a. The body rotates while its center of mass translates through space (e.g., a rolling wheel)[1]10.
##### b. Motion is analyzed as a superposition of the center of mass motion and rotation about the center of mass12.
## II. Moment of Inertia (MOI)
### A. Physical Significance and Properties
#### Definition
##### a. It is the rotational analogue of mass, representing a body's tendency to oppose changes in its rotational state13.
##### b. Depends on the total mass and the distribution of mass relative to the axis of rotation ($mr^2$)15.
#### Tensor Nature
##### a. MOI is a tensor quantity (rank 2), not a simple scalar or vector15.
##### b. Addition or subtraction requires calculation about a common axis; values cannot be added directly if axes differ17.
### B. Calculation for Discrete Particle Systems
#### Formula
##### a. $I = \sum m_i r_i^2$, where $r_i$ is the perpendicular distance from the axis of rotation19.
##### b. Requires identifying the perpendicular distance for every individual particle17.
#### Examples
##### a. Two masses on a rod or particles on vertices of a polygon (e.g., hexagon)19.
##### b. If a particle lies on the axis of rotation, its contribution to MOI is zero22.
### C. Calculation for Continuous Mass Distributions
#### Integration Method
##### a. Formula: $I = \int r^2 dm$, where $dm$ is a small mass element24.
##### b. Mass elements ($dm$) are defined by density: Linear ($\lambda dx$), Areal ($\sigma dA$), or Volumetric ($\rho dV$)24.
#### Standard Object Formulas (About Center of Mass/Symmetry Axis)
##### a. Ring or Hollow Cylinder: $MR^2$27.
##### b. Disc or Solid Cylinder: $MR^2/2$[27]29.
##### c. Thin Rod (about center): $ML^2/12$27.
##### d. Thin Rod (about end): $ML^2/3$27.
##### e. Solid Sphere: $2/5 MR^2$27.f. Hollow Sphere: $2/3 MR^2$27.
##### g. Rectangular Plate: $M(L^2 + B^2)/12$ (about axis perpendicular to center)35.
### D. Theorems of Moment of Inertia
#### Perpendicular Axis Theorem
##### a. Valid only for planar (2D/laminar) objects like rings, discs, and sheets37.
##### b. Formula: $I_z = I_x + I_y$, where $x$ and $y$ are in the plane and $z$ is perpendicular to the plane37.
##### c. Useful for finding MOI about diameters of symmetric objects40.
#### Parallel Axis Theorem
##### a. Valid for all rigid bodies (1D, 2D, 3D)42.
##### b. Formula: $I_{new} = I_{CM} + Md^2$, where $d$ is the perpendicular shift distance42.
##### c. Constraint: One axis must pass through the Center of Mass for the theorem to apply42.
### E. Radius of Gyration ($k$)
#### Definition
##### a. The distance at which the entire mass of the body can be theoretically concentrated to yield the same inertia46.
##### b. It replaces the mass distribution with a single point mass equivalent46.
#### Calculation
##### a. Formula: $I = Mk^2$ or $k = \sqrt{I/M}$46.
##### b. Dependent on the axis of rotation; changes if the axis changes50.
### F. Cavity Problems (Negative Mass Concept)
#### Superposition Principle
##### a. Treat the removed portion as a body with negative mass to subtract its inertia51.
##### b. Formula: $I_{remaining} = I_{total} - I_{removed}$18.
#### Methodology
##### a. Calculate MOI of the whole body (as if solid) about the desired axis18.
##### b. Calculate MOI of the removed part about the same common axis (often requiring Parallel Axis Theorem)18.
##### c. Subtract the values to find the final inertia18.
## III. Torque ($\tau$)
### A. Definition and Mathematical Formulation
#### Rotational Analog of Force
##### a. Represents the "turning effect" or moment of force necessary to cause angular acceleration56.
##### b. Vector Definition: $\vec{\tau} = \vec{r} \times \vec{F}$58.
#### Magnitude Calculation
##### a. $\tau = rF \sin\theta$, where $\theta$ is the angle between the position vector and force58.
##### b. Alternative Method 1: $\tau = r F_{\perp}$ (Force component perpendicular to radius)60.
##### c. Alternative Method 2: $\tau = r_{\perp} F$ (Perpendicular distance/Lever arm $\times$ Force)62.
### B. Properties and Calculation Rules
#### Direction
##### a. Determined by the Right-Hand Thumb Rule (perpendicular to the plane of $r$ and $F$)64.
##### b. Convention: Counter-clockwise is often taken as positive, clockwise as negative (or vice versa)66.
#### Point of Application
##### a. Torque depends on the point about which it is calculated58.
##### b. Torque about an axis is the component of the torque vector along that axis69.
##### c. If the line of force passes through the axis or pivot, torque is zero71.
### C. Equilibrium Conditions
#### Translational Equilibrium
##### a. Net external force is zero ($\sum F = 0$)73.
#### Rotational Equilibrium
##### a. Net external torque is zero ($\sum \tau = 0$) about any point73.
##### b. If net force is zero, the torque is the same about any point in space75.
## IV. Dynamics of Fixed Axis Rotation
### A. Newton's Second Law for Rotation
#### Fundamental Equation
##### a. $\tau_{ext} = I \alpha$ (Net Torque = Moment of Inertia $\times$ Angular Acceleration)76.
##### b. Analogous to $F = ma$ in linear dynamics76.
#### Application to Pulley Systems
##### a. Massive pulleys (with inertia $I$) result in different tensions on either side ($T_1 \neq T_2$)78.
##### b. Torque equation for pulley: $(T_1 - T_2)R = I\alpha$80.
##### c. No-slip condition: $a = R\alpha$ relates linear and angular acceleration80.
### B. Work and Energy in Rotation
#### Kinetic Energy
##### a. Rotational Kinetic Energy: $K_{rot} = \frac{1}{2} I \omega^2$82.
##### b. Total Energy in Rolling: $K_{total} = \frac{1}{2} Mv_{cm}^2 + \frac{1}{2} I_{cm} \omega^2$82.
#### Work and Power
##### a. Power: $P = \vec{\tau} \cdot \vec{\omega}$85.
##### b. Work Done: $W = \int \tau d\theta$85.
#### Work-Energy Theorem
##### a. Work done by all torques equals the change in rotational kinetic energy86.
##### b. Work done by static friction in pure rolling is zero88.
### C. Hinge Forces
#### Nature of Forces
##### a. Reaction forces exerted by the hinge to maintain the axis of rotation90.
##### b. Components: Often resolved into radial (centripetal) and tangential directions92.
#### Calculation Strategy
##### a. Use $\sum F_{ext} = m a_{cm}$ for the center of mass motion92.
##### b. Radial force provides centripetal acceleration ($m \omega^2 R_{cm}$)92.
##### c. Tangential force relates to tangential acceleration ($m \alpha R_{cm}$)92.
## V. Angular Momentum ($L$)
### A. Definition for Particle and Rigid Body
#### Particle Definition
##### a. $\vec{L} = \vec{r} \times \vec{p} = m(\vec{r} \times \vec{v})$96.
##### b. Magnitude: $L = mvr \sin\theta = m v r_{\perp}$96.
#### Rigid Body Definition
##### a. Fixed Axis Rotation: $L = I \omega$99.
##### b. General Motion (CTRM): $L = I_{CM} \omega + (\vec{r}{CM} \times m\vec{v}{CM})$ (Orbital + Spin)101.
### B. Conservation of Angular Momentum (COAM)
#### Principle
##### a. If net external torque $\tau_{ext} = 0$, then $\frac{dL}{dt} = 0$, so $L$ is constant103.
##### b. $I_1 \omega_1 = I_2 \omega_2$ (if moment of inertia changes, angular velocity adjusts)105.
#### Applications
##### a. Ice Skater/Diver: Changing $I$ by moving limbs changes spin rate $\omega$105.
##### b. Planetary Motion: Area velocity is constant because torque is zero105.
##### c. Collisions: Angular momentum is conserved about a pivot if impact forces are internal or pass through the pivot107.
### C. Angular Impulse
#### Relation to Momentum
##### a. Angular Impulse ($J$) equals the change in angular momentum ($\Delta L$)109.
##### b. Formula: $J = \int \tau dt = L_f - L_i$109.
##### c. Analogous to linear impulse changing linear momentum103.
## VI. Combined Translational and Rotational Motion (Rolling)
### A. Kinematics of Rolling
#### Decomposition
##### a. Motion is viewed as translation of the Center of Mass ($v_{cm}$) plus rotation about the Center of Mass ($\omega$)111.
##### b. Velocity of any point: Vector sum $\vec{v}{net} = \vec{v}{cm} + \vec{v}_{rot}$112.
#### Pure Rolling (No Slipping)
##### a. Condition: Velocity of the point of contact relative to the surface is zero112.
##### b. Constraint Equations: $v_{cm} = R\omega$ and $a_{cm} = R\alpha$112.c. Velocity Profile: Top point $2v$, Center $v$, Bottom $0$115.
### B. Instantaneous Axis of Rotation (IAR)
#### Concept
##### a. The point of contact (in pure rolling) acts as a momentary fixed pivot117.
##### b. The whole body appears to rotate purely about the IAR at that instant117.
#### Velocity Calculation
##### a. $v_P = r_{IAR} \omega$, where $r_{IAR}$ is the distance from the contact point117.
### C. Dynamics on an Inclined Plane
#### Forces and Equations
##### a. Gravity ($mg \sin\theta$), Normal force, and Friction act on the body118.
##### b. Friction provides the torque relative to the center of mass to cause rotation118.
#### Acceleration Formula
##### a. $a = \frac{g \sin \theta}{1 + I/MR^2}$ or $a = \frac{g \sin \theta}{1 + k^2/R^2}$50.
##### b. $k$ is the radius of gyration; bodies with smaller $k$ (e.g., Solid Sphere) accelerate faster50.
#### Friction Requirements
##### a. Static friction is required to prevent slipping ($a = R\alpha$)123.
##### b. Minimum coefficient of friction: $\mu_{min} = \frac{\tan \theta}{1 + MR^2/I}$124.
### D. Energy in Rolling
#### Total Kinetic Energy
##### a. Sum of translational and rotational kinetic energy82.
##### b. $K_{total} = \frac{1}{2} M v_{cm}^2 (1 + k^2/R^2)$ for pure rolling88.
#### Conservation
##### a. If rolling is pure (static friction), mechanical energy is conserved because static friction does no work88.
## VII. Toppling
### A. Mechanism
#### Normal Force Shift
##### a. As an external force is applied, the line of action of the Normal force shifts to generate a counter-torque127.
##### b. Toppling occurs when the Normal force shifts to the extreme edge of the base129.
### B. Conditions
#### Critical Force
##### a. Torque of applied force $>$ Torque of weight about the pivot edge131.
##### b. Condition: $F \cdot h > mg \cdot (a/2)$ (where $a$ is base width, $h$ is force height)131.
#### Toppling vs. Sliding
##### a. Block slides if $F > \mu mg$ before the toppling torque is reached133.
##### b. Block topples if the force required to topple is less than the limiting friction ($\mu > a/2h$)133.
