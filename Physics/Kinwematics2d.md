---
markmap:
  colorFreezeLevel: 3
---

# Kinwematics2d

#### Based on the comprehensive lecture transcript provided, here is an ultra-detailed, multi-level hierarchical outline of Motion in a Plane (Kinematics 2D).
## I. Fundamentals of Vectors in Physics
### A. Need for Vectors
#### Limitation of Scalars
  - Some physical quantities cannot be added using simple arithmetic (e.g., $4N + 2N$ forces might not equal $6N$ if directions differ)
#### Directional Importance
  - The impact of a physical quantity (like force) depends heavily on the direction in which it is applied
#### Examples
  - Velocity, acceleration, displacement, force, and momentum are vector quantities requiring direction for full description
### B. Representation and Unit Vectors
#### Graphical Representation
  - Vectors are drawn as arrows where length represents magnitude and the arrow head indicates direction
#### Unit Vectors
  - Used to specify direction without changing magnitude.
##### a.  Definition: A vector divided by its magnitude ($\hat{f} = \vec{f} / |\vec{f}|$)
##### b.  Rectangular Unit Vectors: In a 3D world, we use $\hat{i}$ (x-axis), $\hat{j}$ (y-axis), and $\hat{k}$ (z-axis)
##### c.  Scale Factor: These act as scale factors (like boxes on a graph paper) to define movement in 3D space
### C. Position and Displacement Vectors
#### Position Vector
  - Defines a point's location relative to the origin (e.g., $\vec{OA} = x\hat{i} + y\hat{j} + z\hat{k}$)
#### Displacement Vector
  - Represents the change in position between two points.
##### a.  Calculation: Calculated as Final Vector minus Initial Vector (Head minus Tail)
##### b.  Magnitude: Found using the distance formula: $\sqrt{(x_2-x_1)^2 + (y_2-y_1)^2 + (z_2-z_1)^2}$
### D. Resolution of Vectors
#### Concept
  - Breaking a single vector into components along specific axes (usually $x$ and $y$)
#### Trigonometric Components
##### a.  Base/Adjacent: The component along the angle $\theta$ is $v \cos\theta$
##### b.  Perpendicular: The component opposite the angle $\theta$ is $v \sin\theta$
## II. Introduction to Two-Dimensional (2D) Motion
### A. Conditions for 2D Motion
#### Velocity-Acceleration Angle
  - 2D motion occurs when the angle between velocity ($v$) and acceleration ($a$) is not $0^\circ$ or $180^\circ$
##### a.  If angle is $0^\circ$: 1D Speed up (rectilinear).
##### b.  If angle is $180^\circ$: 1D Slow down/Retardation.
#### Component Effect
  - Acceleration has a component perpendicular to velocity, causing the particle to change direction and enter a plane
### B. Independence of Motions
#### Core Principle
  - Motion along the x-axis and motion along the y-axis can be treated as two independent 1D motions
#### Calculation Strategy
##### a.  Perform calculations for $x$ (displacement, velocity) separately.
##### b.  Perform calculations for $y$ separately.
##### c.  Combine results using $\hat{i}$ and $\hat{j}$ to get the net vector
## III. Ground-to-Ground Projectile Motion
### A. Basic Parameters and Setup
#### Initial Velocity
  - Projectile launched with speed $u$ at angle $\theta$.
##### a.  Horizontal component: $u_x = u \cos\theta$ 14.b.  Vertical component: $u_y = u \sin\theta$
#### Acceleration
##### a.  Horizontal ($a_x$): $0$ (No force in horizontal direction)
##### b.  Vertical ($a_y$): $-g$ (Gravity acts downwards)
### B. Key Formulas (Derived from 1D Equations)
#### Time of Flight ($T$)
##### a.  Determined by vertical motion (when the particle returns to ground).
##### b.  Formula: $T = \frac{2u_y}{g} = \frac{2u \sin\theta}{g}$
#### Maximum Height ($H_{max}$)
##### a.  Determined by vertical component reaching zero velocity.
##### b.  Formula: $H = \frac{u_y^2}{2g} = \frac{u^2 \sin^2\theta}{2g}$
#### Horizontal Range ($R$)
##### a.  Distance traveled horizontally during Time of Flight.
##### b.  Formula: $R = u_x \times T = \frac{u^2 \sin 2\theta}{g}$
##### c.  Maximum Range: Occurs at $\theta = 45^\circ$, where $R_{max} = \frac{u^2}{g}$
### C. Important Properties
#### Top of Trajectory
##### a.  Vertical velocity is zero ($v_y = 0$).
##### b.  Net velocity is minimum but not zero: $v_{net} = u \cos\theta$ (horizontal component remains constant)
##### c.  Velocity and Acceleration are perpendicular ($90^\circ$) at this point
#### Complementary Angles
##### a.  Projectiles launched at $\theta$ and $(90^\circ - \theta)$ have the same Range
##### b.  Height Relation: $H_1 + H_2$ equals the height of a vertical projection with the same speed ($H_{vertical}$)
##### c.  Time Relation: $T_1^2 + T_2^2 = T_{vertical}^2$
### D. Equation of Trajectory
#### Definition
  - The mathematical relationship between $y$ and $x$ (path of the particle)
#### Derivation
  - Eliminate time ($t$) from $x(t)$ and $y(t)$ equations
#### Standard Form
  - $y = x \tan\theta - \frac{g x^2}{2u^2 \cos^2\theta}$
#### Range Form
  - $y = x \tan\theta \left(1 - \frac{x}{R}\right)$
## IV. Projectile Motion from a Height
### A. Horizontal Projection
#### Setup
  - Projectile thrown horizontally ($u_x = u, u_y = 0$) from height $h$
#### Analysis
##### a.  Treat as "Drop" case for vertical motion (Initial vertical velocity = 0).
##### b.  Time of Flight: $T = \sqrt{\frac{2h}{g}}$
##### c.  Range: $R = u \times \sqrt{\frac{2h}{g}}$
##### d.  Trajectory: Still parabolic; horizontal velocity remains constant while vertical velocity increases
### B. Projection at an Angle
#### Setup
  - Thrown with velocity $u$ at angle $\theta$ from a height $h$
#### Methodology
##### a.  Do not rely on standard formulas.
##### b.  Use the displacement equation vectorially: $\vec{s}_y = u_y t + \frac{1}{2} a_y t^2$ where displacement $s_y = -h$
##### c.  Solving the resulting quadratic equation yields the Time of Flight
### C. Application: Moving Platform (e.g., Airplane)
#### Drop Concept
  - If an object is dropped from a moving body (plane), it inherits the velocity of the carrier ($u_{object} = u_{plane}$)
#### Viewpoints
##### a.  Ground Observer: Sees a parabolic path.
##### b.  Pilot Observer: Sees the object falling in a straight vertical line (since horizontal velocities match)
## V. Inclined Plane Projectile Motion
### A. Coordinate System Shift
#### New Axes
##### a.  X-axis: Along the incline.
##### b.  Y-axis: Perpendicular to the incline
#### Effective Acceleration
  - Gravity ($g$) must be resolved.
##### a.  $a_x = -g \sin\alpha$ (Retardation along the incline)
##### b.  $a_y = -g \cos\alpha$ (Effective gravity perpendicular to incline)
### B. Key Parameters (Relative to Incline)
#### Time of Flight
  - Depends on $u_y$ and $a_y$.
##### a.  Formula: $T = \frac{2u \sin\theta}{g \cos\alpha}$ (where $\theta$ is angle with incline)
#### Maximum Height (from Incline)
##### a.  Formula: $H = \frac{u^2 \sin^2\theta}{2g \cos\alpha}$
#### Range
##### a.  Calculated using $s_x = u_x t + \frac{1}{2} a_x t^2$ where $a_x$ is non-zero
##### b.  Alternative Method: Calculate horizontal distance ($x$) relative to ground and project it onto the incline ($R = x / \cos\alpha$)
### C. Special Conditions
#### Perpendicular Hit
  - For a projectile to hit the incline perpendicularly, the final velocity along the x-axis (incline) must be zero ($v_x = 0$)
#### Elastic Collision on Incline
  - If $e=1$, the angle of incidence equals angle of reflection relative to the normal. If it hits horizontally on a $45^\circ$ incline, it rebounds vertically
## VI. Relative Motion
### A. Core Philosophy
#### The Observer Principle
  - The observer always considers themselves at rest
#### Technique
  - To analyze motion of Particle B with respect to Observer A:
##### a.  Apply the negative of A's velocity to B.
##### b.  Apply the negative of A's acceleration to B.
##### c.  Analyze B's resulting motion as if A is fixed
#### Vector Definition
  - $\vec{v}_{BA} = \vec{v}_B - \vec{v}_A$
### B. Specific Scenarios
#### Mid-Air Collision (Two Projectiles)
##### a.  Relative Acceleration: Since both experience $g$ downwards, relative acceleration is zero ($\vec{a}_{rel} = \vec{g} - \vec{g} = 0$)
##### b.  Result: The motion of one projectile as seen from the other is a straight line
##### c.  Collision Condition: The relative velocity vector must point directly from one particle to the other
#### Minimum Distance of Approach
##### a.  Stop one particle.
##### b.  Calculate the relative velocity vector of the second particle.
##### c.  The perpendicular distance from the stationary particle to the line of motion of the second is the closest distance
### C. Rain-Man Problems
#### Concept
  - Rain appears to fall differently when the observer is moving.
#### Analysis
  - $\vec{v}_{RM} = \vec{v}_R - \vec{v}_M$
#### Vertical Rain Condition
  - For rain to appear vertical to a moving man, the horizontal component of the man's velocity must cancel the horizontal component of the rain's velocity ($v_{man} = v_{rain, x}$)
### D. River-Boat Problems
#### Crossing the River
  - A swimmer/boat has velocity relative to water ($v_{br}$) and water has velocity ($v_r$).
#### Case 1
  - Minimum Distance (Shortest Path):
##### a.  Swimmer aims upstream to cancel river flow.
##### b.  Condition: $v_{br} \sin\theta = v_r$ (Net drift is zero)
##### c.  Path is perpendicular to the bank.
#### Case 2
  - Minimum Time:
##### a.  Swimmer aims directly perpendicular to the flow ($\theta = 0$ relative to vertical).
##### b.  River flow carries them downstream (Drift), but crossing time is minimized ($T = d / v_{br}$)
## VII. Advanced Applications & Problem Solving
### A. Angular Momentum in Projectiles
#### Calculation
  - Uses the cross product $\vec{L} = \vec{r} \times \vec{p}$
#### Method
  - Use determinant method with unit vectors ($\hat{i}, -\hat{j}, \hat{k}$) to solve the cross product
#### At Specific Points
  - Can be calculated at the top of trajectory or point of impact using position and velocity vectors
### B. Elastic Collisions in Trajectories
#### Vertical Walls
  - If $e=1$ (perfectly elastic), the velocity component perpendicular to the wall reverses, but magnitude stays same ($u \to -u$). The horizontal component parallel to the wall remains unchanged
#### Effect on Range
  - If walls are placed symmetrically or at specific distances with $e=1$, the ball may return to the point of projection
### C. Maximizing Range (Wedge/Efflux Analogy)
#### Scenario
  - Dropping a ball onto a wedge to convert vertical motion to horizontal.
#### Optimization
  - Similar to fluid efflux, maximum range occurs when the drop height/hole is at half the total height ($H/2$)