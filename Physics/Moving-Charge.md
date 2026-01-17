---
markmap:
  colorFreezeLevel: 3
---

# Moving-Charge

## I. Introduction to Magnetic Fields and Current
### A. Oersted’s Observation and Basic Concepts
#### 1. Fundamental Principle
##### a. When current passes through a wire or conductor, it generates an associated magnetic field property
##### b. A magnetic material placed near a current-carrying wire experiences a force
#### 2. Direction of Magnetic Field (Right Hand Thumb Rule)
##### a. Procedure
  - i. Use the right hand to grip the wire with the thumb pointing in the direction of the current
  - ii. The curl of the fingers represents the direction of the magnetic field lines
##### b. Application to Loops
  - i. If fingers curl in the direction of the current, the thumb indicates the magnetic field direction
  - ii. Conversely, if the thumb points along the current in a wire, the curling fingers show the magnetic field
##### c. Notation
  - i. Cross ($\times$): Represents magnetic field pointing inward (e.g., $-z$ axis)
  - ii. Dot ($\cdot$): Represents magnetic field pointing outward (e.g., $+z$ axis)
## II. Biot-Savart Law
### A. Mathematical Formulation
#### 1. The Current Element
##### a. Current ($I$) is a scalar quantity, but current element ($I\vec{dl}$) is treated as a vector
##### b. The direction of the current element is the same as the current
#### 2. The Formula
##### a. The magnetic field ($d\vec{B}$) due to a small current element is $\frac{\mu_0}{4\pi} \frac{I (\vec{dl} \times \vec{r})}{r^3}$ 6.b. Magnitude form: $dB = \frac{\mu_0 I dl \sin\theta}{4\pi r^2}$
##### c. Direction is determined by the cross product $\vec{dl} \times \vec{r}$
### B. Applications of Biot-Savart Law
#### 1. Finite Straight Wire
##### a. Formula: $B = \frac{\mu_0 I}{4\pi r} (\sin\theta_1 + \sin\theta_2)$
##### b. Parameters
  - i. $r$ is the perpendicular distance from the wire
  - ii. $\theta_1$ and $\theta_2$ are angles measured from the perpendicular to the ends of the wire in opposite directions
##### c. Direction: Use the Right Hand Thumb Rule; one side of the wire has inward field, the other outward
#### 2. Infinite and Semi-Infinite Wires
##### a. Infinite Wire: Angles become $90^\circ$, resulting in $B = \frac{\mu_0 I}{2\pi r}$
##### b. Semi-Infinite Wire: One angle is $90^\circ$, the other is $0^\circ$, resulting in $B = \frac{\mu_0 I}{4\pi r}$
#### 3. Axial Points of a Wire
##### a. The magnetic field at a point directly in front of or behind the current vector is zero
##### b. This is because the angle $\theta$ is either $0^\circ$ or $180^\circ$, making the cross product zero
#### 4. Circular Arcs and Loops
##### a. General Arc: $B = \frac{\mu_0 I \theta}{4\pi r}$, where $\theta$ is the angle subtended at the center
##### b. Full Circle: $\theta = 2\pi$, resulting in $B = \frac{\mu_0 I}{2 r}$ at the center
##### c. Semi-Circle: $\theta = \pi$, resulting in $B = \frac{\mu_0 I}{4 r}$
#### 5. On the Axis of a Current-Carrying Coil
##### a. Formula: $B = \frac{\mu_0 N I R^2}{2(R^2 + x^2)^{3/2}}$ 17.i. $N$ is the number of turns, $R$ is the radius, and $x$ is the distance from the center along the axis
##### b. Comparison with Electric Field:
  - i. Electric field on the axis of a ring has $x$ in the numerator and is zero at the center
  - ii. Magnetic field is maximum at the center ($x=0$) and decreases as $x$ tends to infinity
## III. Ampere’s Circuital Law
### A. Statement and Convention
#### 1. Definition
##### a. The line integral of the magnetic field across a closed loop is $\mu_0$ times the enclosed current: $\oint \vec{B} \cdot \vec{dl} = \mu_0 I_{enclosed}$
##### b. This uses an "Amperian loop," not a surface (Gaussian surface)
#### 2. Sign Convention
##### a. Curl fingers in the direction of the loop integration; the thumb indicates the positive current direction
##### b. Enclosed current is the algebraic sum based on this direction ($I_{net} = I_{in} - I_{out}$)
### B. Applications of Ampere's Law
#### 1. Infinite Straight Wire
##### a. Using a circular loop of radius $r$, $\oint B \cdot dl = B(2\pi r) = \mu_0 I$ 25.b. Result: $B$ is inversely proportional to $r$ ($B \propto 1/r$)
#### 2. Cylindrical Conductors
##### a. Hollow Cylinder:
  - i. Inside ($r < R$): No enclosed current, so $B = 0$
  - ii. Outside ($r > R$): Behaves like a wire, $B = \frac{\mu_0 I}{2\pi r}$
##### b. Solid Cylinder (Uniform Current Density):
  - i. Outside ($r > R$): $B = \frac{\mu_0 I}{2\pi r}$
  - ii. Inside ($r < R$): Current enclosed is proportional to area ($I \frac{r^2}{R^2}$), resulting in $B = \frac{\mu_0 I r}{2\pi R^2}$
  - iii. Graph: Linear increase ($B \propto r$) inside, hyperbolic decrease ($B \propto 1/r$) outside
##### c. Variable Current Density:
  - i. If current density $J$ depends on $r$ (e.g., $J = kr$), integration is required to find $I_{enclosed}$
  - ii. Example: If $J \propto r$, internal $B$ may depend on $r^2$ or higher powers
## IV. Solenoid and Toroid
### A. The Solenoid
#### 1. Structure and Ideal Properties
##### a. A coil where length is much greater than radius
##### b. Ideal infinite solenoid has uniform magnetic field inside and zero field just outside
#### 2. Magnetic Field Formulas
##### a. Inside (Center): $B = \mu_0 n I$, where $n$ is turns per unit length
##### b. At Ends: $B = \frac{\mu_0 n I}{2}$ (half the value at the center)
##### c. General Finite Solenoid: $B = \frac{\mu_0 n I}{2} (\sin\theta_1 + \sin\theta_2)$
### B. The Toroid
#### 1. Structure
##### a. A solenoid bent into a circular shape (endless solenoid)
##### b. It creates a closed magnetic field loop with no poles
#### 2. Magnetic Field Characteristics
##### a. Inside the Core: $B = \frac{\mu_0 N I}{2\pi r}$
##### b. Non-Uniformity: Unlike a straight solenoid, the field inside a toroid is not uniform; it varies inversely with radius ($r$)
##### c. Outside: Magnetic field is zero in the empty space inside and outside the toroid
#### 3. Flux Calculation: For rectangular cross-sections, integrate $B \cdot dA$ because $B$ varies with distance from the center
## V. Motion of Charged Particles in Magnetic Fields
### A. Magnetic Force
#### 1. The Formula: $\vec{F} = q (\vec{v} \times \vec{B})$
#### 2. Properties:
##### a. Force is perpendicular to both velocity ($\vec{v}$) and magnetic field ($\vec{B}$)
##### b. Magnetic force does zero work because force is perpendicular to displacement; therefore, kinetic energy and speed remain constant
### B. Trajectories based on Entry Angle ($\theta$)
#### 1. Parallel/Anti-Parallel ($\theta = 0^\circ$ or $180^\circ$)
##### a. Force is zero
##### b. Trajectory: Straight line
#### 2. Perpendicular ($\theta = 90^\circ$)
##### a. Trajectory: Uniform Circular Motion
##### b. Radius: $R = \frac{mv}{qB} = \frac{p}{qB} = \frac{\sqrt{2mK}}{qB}$
##### c. Time Period: $T = \frac{2\pi m}{qB}$
  - i. Independent of speed ($v$) and radius ($R$)
  - ii. Depends on charge-to-mass ratio ($q/m$)
#### 3. Oblique Angle ($0^\circ < \theta < 90^\circ$)
##### a. Trajectory: Helical path
##### b. Velocity Components:
  - i. $v_{\parallel} = v \cos\theta$ (responsible for linear motion/pitch)
  - ii. $v_{\perp} = v \sin\theta$ (responsible for circular motion/radius)
##### c. Parameters:
  - i. Radius of Helix: $R = \frac{m v_{\perp}}{qB}$
  - ii. Pitch: Linear distance per revolution $= v_{\parallel} \times T = v \cos\theta \frac{2\pi m}{qB}$
## VI. Motion in Combined Fields (Lorentz Force)
### A. General Concept
#### 1. Total force $\vec{F} = q\vec{E} + q(\vec{v} \times \vec{B})$
### B. Special Cases
#### 1. Velocity Selector
##### a. Used to select particles of a specific speed from a beam
##### b. Condition: Electric force balances Magnetic force ($qE = qvB$) 59.c. Selected velocity: $v = \frac{E}{B}$
#### 2. Cyclotron
##### a. Purpose: Device to accelerate heavy charged particles (protons, ions)
##### b. Working Principle:
  - i. Uses crossed electric and magnetic fields.
  - ii. Magnetic field provides circular path; oscillating electric field accelerates the particle across the gap between "Dees"
##### c. Resonance Condition: The frequency of the oscillator must match the cyclotron frequency ($\nu = \frac{qB}{2\pi m}$)
##### d. Limitations:
  - i. Not suitable for electrons because their small mass leads to rapid relativistic mass increase, causing them to fall out of sync with the oscillator
  - ii. Not suitable for neutral particles
#### 3. Complex Trajectories: If electric field is parallel to magnetic field, the particle accelerates linearly while circling, resulting in a helix with increasing pitch
## VII. Force on Current-Carrying Conductors
### A. Force Formula
#### 1. General Vector Form: $\vec{F} = I (\vec{L} \times \vec{B})$
#### 2. Magnitude: $F = B I L \sin\theta$, where $\theta$ is the angle between the length vector and magnetic field
### B. Special Configurations
#### 1. Straight Wire:
##### a. If $\vec{L} \parallel \vec{B}$, force is zero
##### b. If $\vec{L} \perp \vec{B}$, force is maximum ($BIL$)
#### 2. Arbitrary Shaped Wire:
##### a. For a wire in a uniform magnetic field, use the Effective Length ($L_{eff}$)
##### b. $L_{eff}$ is the straight vector connecting the initial and final points of the conductor
#### 3. Closed Loop:
##### a. In a uniform magnetic field, the net force on any closed current loop is zero because the vector sum of $L_{eff}$ is zero
### C. Force Between Two Parallel Conductors
#### 1. Mechanism:
##### a. Wire 1 creates a magnetic field at the location of Wire 2; Wire 2 experiences a force due to this field
#### 2. Formula: Force per unit length $\frac{F}{L} = \frac{\mu_0 I_1 I_2}{2\pi d}$
#### 3. Nature of Force:
##### a. Attraction: If currents flow in the same direction
##### b. Repulsion: If currents flow in opposite directions
### D. Interaction with Non-Uniform Fields (Variable Distance)
#### 1. Wire Perpendicular to an Infinite Wire:
##### a. Since the magnetic field varies with distance ($\frac{\mu_0 I}{2\pi x}$), integration is required
##### b. Result involves natural log: $F = \frac{\mu_0 I_1 I_2}{2\pi} \ln\left(\frac{x+L}{x}\right)$
#### 2. Flat Ribbon/Sheet:
##### a. Requires considering a small strip of width $dx$ with current $dI$ and integrating across the width