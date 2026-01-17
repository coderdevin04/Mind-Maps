---
markmap:
  colorFreezeLevel: 3
---

# Electric-Potential-Capacitance

## I. Fundamentals of Electric Potential and Energy
### A. Definition of Electric Potential
#### 1. Concept and Physical Meaning
##### a. Defined as the work done by an external agent to bring a unit positive charge from infinity to a specific point
##### b. The work done against the electric field is stored in the system as potential energy
##### c. Mathematical definition: Potential ($V$) is potential energy per unit charge ($V = U/q_0$)
#### 2. Potential due to Point Charge
##### a. Formula: For a charge $Q$ at distance $R$, $V = KQ/R$
##### b.Nature: It is a scalar quantity, having magnitude but no direction, so vector resolution is not required
##### c. Sign Convention: The sign of the charge must be included; positive charge creates positive potential, negative charge creates negative potential
### B. Electric Potential Energy
#### 1. Two-Charge System
##### a. Formula: For charges $q$ and $q_0$ separated by distance $r$, $U = K q q_0 / r$
##### b. Limitation: Electric potential energy is strictly defined for pairs of charges
#### 2. Multiple Charge Systems
##### a. Calculation: Total energy is the sum of the energies of all unique pairs
##### b. Number of Pairs: For $n$ charges, the number of pairs is $n(n-1)/2$
##### c. Example (Cube): A cube with 8 charges has 28 pairs: 12 edges (dist $L$), 12 face diagonals (dist $L\sqrt{2}$), and 4 body diagonals (dist $L\sqrt{3}$)
### C. Relation between Electric Field and Potential
#### 1. Integral and Differential Forms
##### a. Change in potential equals the negative dot product of electric field and displacement ($\Delta V = -\vec{E} \cdot \vec{d}$)
##### b. In differential form: $E = -dV/dx$ (for x-component), meaning field is the negative gradient of potential
##### c. Implication: Moving in the direction of the electric field results in a decrease in potential
#### 2. Calculation from Potential Function
##### a. If $V$ is given as a function of $x, y, z$, the electric field components are found by partial differentiation with a negative sign (e.g., $E_x = -dV/dx$)
## II. Potential of Continuous Charge Distributions
### A. Charged Rod
#### 1. Setup
##### a. A rod of length $L$ and charge $Q$ with a point $P$ at distance $a$ from one end on its axis
#### 2. Formula
##### a. Calculated by integrating elements $dq$: $V = (KQ/L) \ln((a+L)/a)$
### B. Charged Ring
#### 1. At the Center
##### a. Potential is $KQ/R$, where $R$ is the radius
##### b. This holds true whether the charge is uniformly distributed or non-uniformly distributed
##### c. Semicircles or arcs at the center also follow the $KQ/R$ logic based on total charge present
#### 2. On the Axis
##### a. At distance $x$ from the center, the distance to the rim is $\sqrt{R^2+x^2}$
##### b. Formula: $V = KQ / \sqrt{R^2 + x^2}$
### C. Charged Disc
#### 1. On the Axis
##### a. Formula for a disc of radius $R$ and surface charge density $\sigma$ at distance $x$
##### b. $V = \frac{\sigma}{2\epsilon_0} \sqrt{x^2 + R^2} - x$
##### c. Distinct from the electric field formula which involves $(1 - \cos\theta)$
## III. Equipotential Surfaces
### A. Characteristics
#### 1. Definition
##### a. A region or locus where the potential is the same everywhere
##### b. Can be surfaces, lines, or volumes (e.g., inside a conductor)
#### 2. Relation to Work and Field
##### a. Electric field lines are always perpendicular to equipotential surfaces
##### b. Work done in moving a charge between any two points on an equipotential surface is zero
## IV. Potential of Spheres (Conducting and Non-Conducting)
### A. Group 1: Hollow/Solid Conducting & Hollow Non-Conducting (Uniform)
#### 1. Properties
##### a. Charge resides on the surface (for conductors) or acts as a shell
##### b. Electric field inside is zero; therefore, potential is constant inside
#### 2. Formulas
##### a. Outside ($x > R$): Acts as a point charge at center, $V = KQ/x$
##### b. Surface ($x = R$): $V = KQ/R$
##### c. Inside ($x < R$): Equals surface potential, $V = KQ/R$
### B. Group 2: Solid Non-Conducting Sphere (Uniform Volume Charge)
#### 1. Properties
##### a. Charge is distributed uniformly throughout the volume
##### b. Electric field is not zero inside, so potential varies
#### 2. Formulas. Outside and Surface: Same as Group 1 ($KQ/x$ and $KQ/R$)
##### b. Inside ($x < R$): $V = \frac{KQ}{2R} (3R^2 - x^2)$
##### c. Center ($x = 0$): Potential is 1.5 times the surface potential ($V_{center} = 1.5 V_{surface}$)
### C. Connection of Spheres
#### 1. Charge Flow
##### a. Connecting two charged conducting spheres with a wire equalizes their potential
##### b. Ratio of final charges: $Q_1/Q_2 = R_1/R_2$
#### 2. Combining Drops
##### a. When $n$ drops combine, charge is conserved ($Q_{big} = nq$) and volume is conserved ($R_{big} = n^{1/3}r$)
##### b. New potential: $V_{big} = n^{2/3} V_{small}$
## V. Self Energy of Charge Distributions
### A. Concept
#### 1. Definition
##### a. Energy stored in the electric field created by the body itself
##### b. It represents the work done to assemble the charge distribution
### B. Formulas
#### 1. Hollow/Conducting Sphere
##### a. Energy is stored outside the sphere (from surface to infinity)
##### b. Formula: $U = \frac{KQ^2}{2R}$
#### 2. Solid Non-Conducting Sphere
##### a. Energy is stored both inside and outside
##### b. Formula: $U = \frac{3}{5} \frac{KQ^2}{R}$
## VI. Electric Dipole in Potential Terms
### A. Potential due to Dipole
#### 1. General Point
##### a. At distance $r$ and angle $\alpha$, $V = \frac{KP \cos \alpha}{r^2}$
#### 2. Equatorial Plane
##### a. When $\alpha = 90^\circ$, potential is zero everywhere on the plane
### B. Potential Energy in External Field
#### 1. Formula
##### a. $U = -\vec{P} \cdot \vec{E} = -PE \cos \theta$
#### 2. Work Done
##### a. Change in potential energy equals negative work done by the conservative field
##### b. Work done by external agent to rotate dipole: $\Delta U = U_f - U_i$
## VII. Capacitance and Capacitors
### A. General Principles
#### 1. Definition
##### a. Any two conductors placed nearby form a capacitor; it stores charge and energy
##### b. Net charge on a capacitor is zero (plates have $+Q$ and $-Q$)
#### 2. Capacitance ($C$)
##### a. Defined as $Q/V$; depends on geometry, not on charge or voltage supplied
### B. Calculation Method (4 Steps)1. Process
##### a. Step 1: Assume $+Q$ and $-Q$ on plates
##### b. Step 2: Find Electric Field ($E$) between plates
##### c. Step 3: Calculate Potential Difference ($V = \int E \cdot dr$)
##### d. Step 4: Calculate Ratio $C = Q/V$
### C. Standard Geometries
#### 1. Parallel Plate Capacitor
##### a. Formula: $C = \frac{\epsilon_0 A}{d}$
#### 2. Spherical Capacitor
##### a. Two concentric shells: $C = \frac{4\pi\epsilon_0 R_1 R_2}{R_2 - R_1}$
##### b. Isolated Sphere (second plate at infinity): $C = 4\pi\epsilon_0 R$
#### 3. Cylindrical Capacitor
##### a. Formula: $C = \frac{2\pi\epsilon_0 L}{\ln(R_2/R_1)}$
## VIII. Mechanics and Energy of Capacitors
### A. Force Between Plates1. Mechanism
##### a. Positive plate attracts negative plate; force is due to field of one plate acting on charge of the other
#### 2. Formula
##### a. $F = \frac{Q^2}{2 A \epsilon_0}$ or $F = \frac{1}{2}QE$
##### b. The force is independent of the separation distance $d$
### B. Energy Stored
#### 1. Formulas
##### a. $U = \frac{Q^2}{2C} = \frac{1}{2}CV^2 = \frac{1}{2}QV$
#### 2. Energy Density
##### a. Energy per unit volume in an electric field: $u = \frac{1}{2} \epsilon_0 E^2$
##### b. Applicable generally to any electric field
## IX. Capacitor Circuits and Combinations
### A. Series Combination
#### 1. Characteristics
##### a. Charge ($Q$) is the same on all capacitors
##### b. Voltage divides inversely to capacitance ($V \propto 1/C$)
#### 2. Equivalent Capacitance
##### a. Formula: $\frac{1}{C_{eq}} = \frac{1}{C_1} + \frac{1}{C_2} + \dots$
### B. Parallel Combination
#### 1. Characteristics
##### a. Potential difference ($V$) is same across all capacitors
##### b. Charge distributes in proportion to capacitance ($Q \propto C$)
#### 2. Equivalent Capacitance
##### a. Formula: $C_{eq} = C_1 + C_2 + \dots$
### C. Analysis Techniques
#### 1. Kirchhoff's Law
##### a. Can be applied to capacitor loops: sum of potential changes is zero
##### b. Crossing battery $-$ to $+$ is gain ($E$), capacitor $+$ to $-$ is drop ($Q/C$)
#### 2. Plate Problems. Multiple parallel plates can be analyzed by numbering surfaces and identifying connections to form equivalent circuits
#### 3. Redistribution of Charge
##### a. When charged capacitors are connected, charge flows until common potential is reached
##### b. Energy is usually lost (dissipated as heat) during this process
## X. Dielectrics in Capacitors
### A. Properties
#### 1. Dielectric Constant ($K$)
##### a. Insulating material that reduces the effective electric field inside it to $E_{net} = E_0/K$ 76, 77.b. $K$ is always $\ge 1$
#### 2. Induced Charge
##### a. Polarization creates induced charge on the dielectric surface: $Q_{induced} = Q(1 - 1/K)$
### B. Capacitance with Dielectrics
#### 1. Full Filla. Capacitance increases by factor $K$: $C' = KC$ 79.2. Partial Filla. Slab of thickness $t$ in separation $d$: $C = \frac{\epsilon_0 A}{(d-t) + t/K}$ 80, 81.b. Can be modeled as capacitors in series (air part + dielectric part)
### C. Effect of Insertion Conditions
#### 1. Battery Connected
##### a. Voltage $V$ remains constant
##### b. Capacitance becomes $KC$, Charge becomes $KQ$, Energy becomes $KU$
#### 2. Battery Disconnected
##### a. Charge $Q$ remains constant (isolated)
##### b. Capacitance becomes $KC$, Voltage drops to $V/K$, Energy drops to $U/K$
### D. Force on Dielectric Slab
#### 1. Mechanism
##### a. Fringe field attracts the dielectric slab into the capacitor
#### 2. Formula
##### a. Force $F = \frac{\epsilon_0 b V^2 (K-1)}{2d}$
##### b. If frictionless, the slab oscillates with time period $T = 4 \sqrt{\frac{Lmd}{2\epsilon_0 b V^2 (K-1)}}$ (corrected factor 4 outside root)
##XI. Earthing
### A. Concept
#### 1. Earth acts as a large neutral conductor with zero potential
#### 2. Connecting a conductor to earth forces its potential to zero
### B. Calculation
#### 1. Assume charge $q_e$ flows from earth to the body
#### 2. Calculate net potential at the body's surface (due to own charge + external charges) and set to zero to solve for $q_e$
