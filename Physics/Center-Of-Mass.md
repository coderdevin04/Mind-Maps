---
markmap:
  colorFreezeLevel: 3
---

# Center-Of-Mass

#### Based on the provided transcripts from the "JEE Wallah" lecture on Center of Mass and Collisions, here is an ultra-detailed, multi-level hierarchical outline of the topic.
## I. Fundamentals of Center of Mass (COM)
### A. Definition and Conceptual Understanding
#### Physical Definition
  - The Center of Mass is often described as a point in space where the whole mass of the body is assumed to be concentrated
#### Mathematical Definition
  - It is strictly defined as the point about which the net "Mass Moment" is zero
##### a. Mass Moment ($Z$ vector): This is a mathematical tool defined as the product of the mass of a particle and its position vector relative to a point ($Z = m \times \vec{r}$)
##### b. Calculation: For a particle of mass $m$ at a specific coordinate, the mass moment is calculated by multiplying the mass by its position vector relative to the origin or a specific point
#### Distribution Logic
  - The COM is always located closer to the heavier portion of the system
##### a. Two-Particle System: If masses are equal ($m, m$), the COM is exactly in the middle; if masses differ ($m, 3m$), the COM shifts toward the heavier mass so that the net mass moment remains zero
##### b. Symmetry: For symmetrical bodies with homogeneous distribution, the COM coincides with the geometric center
### B. Calculation for Discrete Particle Systems
#### General Position Vector Formula
  - The position of the center of mass ($\vec{r}_{cm}$) is the sum of individual mass-position products divided by the total mass
##### a. Formula: $\vec{r}_{cm} = \frac{m_1\vec{r}_1 + m_2\vec{r}_2 + \dots}{m_1 + m_2 + \dots}$
#### Coordinate Formulas
  - The general vector formula can be broken down into $x$, $y$, and $z$ coordinates
##### a. X-Coordinate: $X_{cm} = \frac{m_1x_1 + m_2x_2 + \dots}{\sum m_i}$
##### b. Y and Z Coordinates: Similar formulas apply for $Y_{cm}$ and $Z_{cm}$ using corresponding coordinates
#### Independence from Coordinates
  - The physical location of the COM is independent of the choice of the coordinate system or origin, though the coordinate values will change
#### Two-Particle System Shortcut
  - For two masses $m_1$ and $m_2$ separated by distance $d$:
##### a. Distance from $m_1$: The distance is $\frac{m_2 d}{m_1 + m_2}$
##### b. Distance from $m_2$: The distance is $\frac{m_1 d}{m_1 + m_2}$
### C. Calculation for Continuous Mass Distributions
#### Integration Method
  - For bodies like rods, rings, and discs, summation ($\Sigma$) is replaced by integration ($\int$)
##### a. Formula: $X_{cm} = \frac{\int x \, dm}{\int dm}$, where $x$ is the coordinate of the COM of the chosen element
#### Selecting the Differential Element ($dm$)
##### a. Linear Distribution: For rods or wires, $dm = \lambda \, dx$ (where $\lambda$ is mass per unit length)
##### b. Areal Distribution: For plates or discs, $dm = \sigma \, dA$ (where $\sigma$ is mass per unit area)
##### c. Volumetric Distribution: For solid bodies, $dm = \rho \, dV$ (where $\rho$ is mass per unit volume)
## II. Standard Results for Specific Geometries
### A. Linear and Arc Structures
#### Uniform Rod
  - The COM lies at the geometric center ($L/2$)
#### Semi-Circular Ring
  - The COM is at a distance of $\frac{2R}{\pi}$ from the center
#### Circular Arc
  - For an arc subtending a total angle $2\theta$, the COM distance from the center is $\frac{R \sin\theta}{\theta}$ on the angle bisector
##### a. Quarter Ring: Derived by setting $2\theta = \pi/2$, resulting in distance $\frac{2\sqrt{2}R}{\pi}$
### B. Planar and 2D Structures
#### Semi-Circular Disc
  - The COM is located at a distance of $\frac{4R}{3\pi}$ from the center
#### Sector of a Disc
  - For a sector with total angle $2\theta$, the COM is at $\frac{2R \sin\theta}{3\theta}$
#### Triangular Plate
  - The COM is located at the centroid of the triangle
### C. 3D and Volumetric Structures
#### Hollow Hemisphere (Shell)
  - The COM is at a distance of $R/2$ from the center
#### Solid Hemisphere
  - The COM is at a distance of $\frac{3R}{8}$ from the center
#### Solid Cone
  - The COM is at a height of $h/4$ from the base
#### Hollow Cone
  - The COM is at a height of $h/3$ from the base
## III. Composite Bodies and Cavity Problems
### A. Additive Systems (Composite Bodies)
#### Principle
  - Bodies are joined to form a system, and mass can be treated as concentrated at individual COMs
#### Methodology
  - Use the standard weighted average formula, substituting mass with Area ($A$) for 2D or Volume ($V$) for 3D uniform bodies
##### a. Formula: $X_{cm} = \frac{A_1 x_1 + A_2 x_2}{A_1 + A_2}$ (for 2D)
### B. Negative Mass Systems (Cavity Problems)
#### Principle
  - A part of the body is removed; this is treated mathematically as adding "negative mass" or "negative area"
#### Methodology
  - The removed part is treated as having negative dimensions in the standard formula
##### a. Formula: $X_{cm} = \frac{A_{big} X_{big} - A_{removed} X_{removed}}{A_{big} - A_{removed}}$
##### b. Critical Step: Ensure coordinates ($X_{big}, X_{removed}$) are measured from the same origin
## IV. Motion of Center of Mass
### A. Shift in Position
#### Shift Formula
  - If individual particles shift by $\Delta \vec{r}i$, the COM shift is $\Delta \vec{r}{cm} = \frac{m_1 \Delta \vec{r}_1 + m_2 \Delta \vec{r}_2}{m_1 + m_2}$
#### No External Force Condition
  - If no external force acts on the system, the COM position does not shift ($\Delta \vec{r}_{cm} = 0$)
##### a. Application: If particles move internally (e.g., swapping places), $m_1 \Delta \vec{r}_1 + m_2 \Delta \vec{r}_2 = 0$
### B. Velocity and Acceleration
#### Velocity of COM
  - Defined as the derivative of position: $\vec{v}_{cm} = \frac{m_1 \vec{v}_1 + m_2 \vec{v}2}{M{total}}$
#### Acceleration of COM
  - Defined as the derivative of velocity: $\vec{a}_{cm} = \frac{m_1 \vec{a}_1 + m_2 \vec{a}2}{M{total}}$
#### Calculation Rule
  - Always use vector notation ($\hat{i}, \hat{j}, \hat{k}$) to avoid errors with speed vs. velocity
## V. Conservation of Linear Momentum
### A. Fundamental Principles
#### Condition for Conservation
  - If the net external force on a system is zero, the initial momentum equals the final momentum ($P_{initial} = P_{final}$)
#### State of COM
##### a. At Rest: If the COM is initially at rest and $F_{ext}=0$, it remains at rest
##### b. In Motion: If the COM is moving and $F_{ext}=0$, its velocity remains constant
### B. Applications: Boat and Plank Problems
#### Scenario
  - A person walks on a floating boat or plank where friction is an internal force
#### Shift Logic
  - Since there is no external horizontal force, the COM of the "Man + Boat" system does not shift
#### Shortcut Formula
  - The shift of the boat ($x$) when a person moves a relative length $L_{rel}$ is given by $x = \frac{m_{person} L_{rel}}{m_{person} + M_{boat}}$
### C. Applications: Recoil of Gun
#### Mechanism
  - Firing is an internal combustion process (internal force), so system momentum is conserved
#### Velocity Definitions
##### a. Case 1 (Ground Frame): Velocity given relative to the ground is used directly in conservation equations
##### b. Case 2 (Muzzle Velocity): Velocity given relative to the gun ($v_{rel}$) must be converted to ground frame ($v_{bullet} = v_{rel} - v_{recoil}$)
#### Calculation
  - For a gun of mass $M$ and bullet $m$ with relative speed $v_r$, recoil velocity is $V = \frac{m v_r}{M + m}$
### D. Applications: Explosion
#### Internal Force Nature
  - Explosions occur due to internal forces; net external force is zero, so momentum is conserved
#### Energy
  - Internal chemical energy converts to kinetic energy, so kinetic energy increases (is not conserved)
#### Projectile Explosion
  - If a projectile explodes mid-air, the COM continues on the original parabolic path as if no explosion occurred (gravity is the only external force)
## VI. Collisions
### A. Basic Concepts and Terminology
#### Definition
  - An event where energy and momentum are exchanged; physical contact is not strictly necessary (e.g., charge repulsion), but 11th-grade physics focuses on contact forces like Normal Reaction
#### Line of Impact (LOI)
  - The line along which the internal impulsive forces (Normal Reaction) act
##### a. Momentum Change: Momentum of individual bodies changes only along the LOI
##### b. No Change: Momentum perpendicular to the LOI remains constant for individual bodies
#### Impact Parameter ($P$)
  - The perpendicular distance between the velocity vectors of approaching bodies; determines if collision is head-on ($P=0$) or oblique
### B. Coefficient of Restitution ($e$)
#### Definition
  - The ratio of velocity of separation to velocity of approach along the Line of Impact
##### a. Formula: $e = \frac{|\vec{v}_2 - \vec{v}_1|}{|\vec{u}_1 - \vec{u}_2|}$
#### Types of Materials/Collisions
##### a. Perfectly Elastic ($e=1$): No loss of energy; body regains shape completely
##### b. Inelastic ($0 < e < 1$): Partial loss of energy; partial regain of shape
##### c. Perfectly Inelastic ($e=0$): Maximum energy loss; bodies stick together and move with common velocity
### C. Head-On Collisions (1D)
#### General Velocity Formulas
##### a. Final Velocity $v_1$: $v_1 = \frac{(m_1 - e m_2)u_1 + (1+e)m_2 u_2}{m_1 + m_2}$
##### b. Final Velocity $v_2$: $v_2 = \frac{(m_2 - e m_1)u_2 + (1+e)m_1 u_1}{m_1 + m_2}$
#### Special Cases
##### a. Equal Mass, Elastic ($e=1$): Velocities are exchanged ($v_1 = u_2, v_2 = u_1$)
##### b. Massive Body ($m_1 \gg m_2$): The heavy body's velocity is unchanged; the light body reflects at twice the speed if the heavy body was moving at it ($v_2 \approx -u_2 + 2u_1$)
#### Energy Loss Formula
  - Loss $= \frac{1}{2} \frac{m_1 m_2}{m_1 + m_2} (u_1 - u_2)^2 (1 - e^2)$
### D. Oblique Collisions (2D)
#### Analysis Strategy
##### a. Resolve Vectors: Break velocities into components along the Line of Impact (LOI) and perpendicular to LOI
##### b. Perpendicular Component: This component never changes for either body as no force acts in this direction
##### c. Along LOI: Apply the coefficient of restitution formula and conservation of momentum along this line
#### Collisions with Surfaces
##### a. Parallel Component: Remains unchanged ($u \sin\theta$)
##### b. Perpendicular Component: Reverses and is scaled by $e$ ($e \cdot u \cos\theta$)
##### c. Angle of Reflection: $\tan \alpha = \frac{\tan \theta}{e}$
### E. Bouncing Ball (Rebounding)
#### Sequential Collisions
  - Each bounce reduces the speed by a factor of $e$
#### Parameters after $n$ collisions
##### a. Velocity: $v_n = e^n u$
##### b. Height: $h_n = e^{2n} h_0$
##### c. Time of Flight: $T_n = e^n T_0$
#### Total Values (Infinite Bounces)
##### a. Total Time: $T_{total} = T_0 \left(\frac{1+e}{1-e}\right)$
##### b. Total Distance: $H_{total} = h_0 \left(\frac{1+e^2}{1-e^2}\right)$