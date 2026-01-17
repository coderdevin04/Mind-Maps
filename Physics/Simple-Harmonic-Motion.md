---
markmap:
  colorFreezeLevel: 3
---

# Simple-Harmonic-Motion

## I. Fundamental Concepts of Motion and Oscillations
### A. Classification of Motions
#### Repetitive and Periodic Motions
##### a. Repetitive motions occur when a particle repeats its motion after a particular interval of time, such as a planet orbiting a star or the rotation of the earth
##### b. These are also known as periodic motions, similar to periodic functions in mathematics (e.g., $f(x+t) = f(x)$), like sine and cosine functions
##### c. Uniform circular motion is a type of periodic motion where a body moves in a circle with a fixed time period ($T = 2\pi/\omega$), but it involves no "to and fro" movement
#### Oscillatory Motion
##### a. Oscillation is defined as "to and fro" motion where a particle moves back and forth about a point
##### b. In oscillation, the particle comes to rest momentarily at extreme positions and has maximum velocity at a mean position
##### c. The condition for general oscillation is that the restoring force must be proportional to $-x^n$, where $n$ is an odd integer ($1, 3, 5, \dots$)
#### Simple Harmonic Motion (SHM)
##### a. SHM is the simplest case of oscillation where $n=1$, meaning the restoring force is linearly proportional to displacement ($F = -kx$)
##### b. If the power $n$ were even (e.g., $n=2$), the force would not change direction when crossing the origin, preventing to-and-fro motion
##### c. The negative sign in $F = -kx$ indicates a restoring nature, always pulling the particle back toward the mean position where net force is zero
## II. Mathematical Description of Simple Harmonic Motion
### A. The Differential Equation of SHM
#### Derivation from Newton's Laws
##### a. Starting with $F = ma = -kx$, the equation becomes $m(d^2x/dt^2) + kx = 0$
##### b. This is rearranged to the standard differential equation: $d^2x/dt^2 + \omega^2x = 0$
##### c. The constant $\omega^2$ is chosen instead of a linear constant $C$ to avoid square roots in the final solution and to ease calculation
#### Solutions to the Differential Equation
##### a. The general solution for position is $x = A \sin(\omega t + \phi)$, which satisfies the differential equation
##### b. Other functions, such as exponential complex functions ($x = A e^{i\omega t}$), can also mathematically represent SHM, but sinusoidal functions are preferred for phasor correlation
##### c. In the equation $x = A \sin(\omega t + \phi)$, $A$ represents the amplitude (maximum displacement), and the sine function bounds the motion between $+A$ and $-A$
### B. Kinematics of SHM
#### Displacement and Phase
##### a. The term $\phi$ is the initial phase constant, determined by the particle's position and direction at $t=0$
##### b. For a particle starting at the mean position, $\phi=0$; for a particle starting at the extreme position, $\phi = \pi/2$, turning the sine function into a cosine function
##### c. The angular frequency $\omega$ relates to the time period by $\omega = 2\pi/T$
#### Velocity Analysis
##### a. Velocity as a function of time is derived by differentiating position: $v = dx/dt = A\omega \cos(\omega t + \phi)$
##### b. Velocity as a function of position is given by $v = \omega\sqrt{A^2 - x^2}$, derived using the identity $\sin^2\theta + \cos^2\theta = 1$
##### c. The maximum velocity ($V_{max}$) occurs at the mean position ($x=0$) and is equal to $A\omega$
#### Acceleration Analysis
##### a. Acceleration is the derivative of velocity: $a = dv/dt = -\omega^2 A \sin(\omega t + \phi)$
##### b. Expressed as a function of position, acceleration is $a = -\omega^2 x$
##### c. Maximum acceleration occurs at the extreme positions ($x = \pm A$) and has a magnitude of $\omega^2 A$
### C. Graphical Representations
#### Position and Time Graphs
##### a. The graph of displacement versus time is sinusoidal (sine or cosine depending on phase)
##### b. The graph indicates the particle is at mean positions at $t=0, T/2, T$ (if $\phi=0$) and extremes at $T/4, 3T/4$
##### c. The acceleration-time graph is a negative sine wave (shifted by phase $\pi$ relative to displacement)
#### Phase Space and Inter-variable Graphs
##### a. The graph of velocity versus displacement ($v$ vs $x$) forms an ellipse based on the equation $v^2/(A\omega)^2 + x^2/A^2 = 1$
##### b. The graph of acceleration versus displacement ($a$ vs $x$) is a straight line with a negative slope equal to $-\omega^2$ passing through the origin
##### c. The slope of the $a$ vs $x$ graph can be used to calculate the time period (e.g., slope = $-\tan(45^\circ) = -1 \implies \omega^2 = 1$)
## III. Energy in Simple Harmonic Motion
### A. Kinetic and Potential Energy Formulas
#### Kinetic Energy ($K$)
##### a. As a function of time: $K = \frac{1}{2}m A^2 \omega^2 \cos^2(\omega t + \phi)$
##### b. As a function of position: $K = \frac{1}{2}m\omega^2(A^2 - x^2)$
##### c. Kinetic energy is maximum at the mean position and zero at the extreme positions
#### Potential Energy ($U$)
##### a. As a function of time: $U = \frac{1}{2}m\omega^2 A^2 \sin^2(\omega t + \phi)$
##### b. As a function of position: $U = \frac{1}{2}m\omega^2 x^2$ (similar to spring potential energy $\frac{1}{2}kx^2$)
##### c. Potential energy is minimum at the mean position and maximum at the extreme positions
#### Total Mechanical Energy ($E$)
##### a. Total energy is the sum of kinetic and potential energy: $E = K + U$
##### b. Summing the time-dependent or position-dependent equations results in a constant value: $E = \frac{1}{2}m\omega^2 A^2$
##### c. This proves that the total energy in an ideal SHM system is conserved and constant over time
### B. Energy Graphs
#### Variation with Position
##### a. The graph of Potential Energy vs. $x$ is a parabola opening upward centered at the mean position
##### b. The graph of Kinetic Energy vs. $x$ is an inverted parabola, zero at $\pm A$ and maximum at $x=0$
##### c. The graph of Total Energy vs. $x$ is a straight horizontal line, indicating constancy
#### Variation with Time
##### a. Both Kinetic and Potential Energy graphs vary sinusoidally with time but are always positive (involving $\sin^2$ or $\cos^2$ terms)
##### b. The frequency of oscillation of kinetic and potential energy is double the frequency of the particle's displacement oscillation
##### c. The Total Energy vs. time graph remains a straight horizontal line
## IV. The Phasor Method
### A. Concept and Definition
#### Relationship to Circular Motion
##### a. A phasor is a rotating vector whose projection on an axis (specifically the y-axis in this context) represents the position of a particle in SHM
##### b. For a particle performing uniform circular motion with radius $A$ and speed $A\omega$, its shadow performs SHM on the diameter
##### c. The angular velocity of the rotating vector corresponds to the angular frequency $\omega$ of the SHM
### B. Application and Problem Solving
#### Visualization of Motion
##### a. At $t=0$, the angle the vector makes with the horizontal is the initial phase $\phi$
##### b. After time $t$, the vector rotates by an angle $\omega t$, making the total angle $\omega t + \phi$
##### c. The projection $y = A \sin(\omega t + \phi)$ matches the SHM equation exactly
#### Solving for Time and Phase
##### a. Phasors simplify calculating the time taken to travel between points (e.g., from extreme to $A/2$) by finding the angle rotated
##### b. It helps determine the phase difference between two oscillating particles by comparing their angular positions on the circle
##### c. Velocity in SHM corresponds to the projection of the tangential velocity ($A\omega$) of the circular motion particle
## V. The Simple Pendulum
### A. Theoretical Derivation
#### Linear SHM Approximation
##### a. The restoring force is the component of gravity perpendicular to the string: $F_{restoring} = -mg \sin\theta$
##### b. For small angles, $\sin\theta \approx \theta \approx x/l$, making the force proportional to displacement: $F = -(mg/l)x$
##### c. Comparing to $F = -m\omega^2 x$, we derive $\omega = \sqrt{g/l}$
#### Torque Method
##### a. The restoring torque is $\tau = -mg(l \sin\theta)$, which for small angles becomes $\tau \approx -mgl\theta$
##### b. Using $\tau = I\alpha = I \omega^2 \theta$ with $I = ml^2$, the result is consistent: $\omega^2 = g/l$
##### c. The formula $T = 2\pi\sqrt{l/g}$ is only valid for small angles; large angles result in non-SHM oscillation
### B. Factors Influencing Time Period
#### Independence of Mass
##### a. The time period depends on length ($l$) and gravity ($g$) but is independent of the mass of the bob
##### b. A heavy bob and a light bob with the same string length will have the same time period
##### c. The length $l$ is measured from the point of suspension to the center of mass of the bob
#### Variation in Effective Gravity ($g_{eff}$)
##### a. In an accelerating lift moving up, $g_{eff} = g + a$, decreasing the time period
##### b. In a lift accelerating down, $g_{eff} = g - a$; if in free fall ($a=g$), $T \to \infty$ (no oscillation)
##### c. For a pendulum in a car accelerating horizontally, the mean position shifts, and $g_{eff} = \sqrt{g^2 + a^2}$
##### d. On an inclined plane, the effective gravity perpendicular to the plane is used: $g_{eff} = g \cos\theta$
#### Variation due to External Fields
##### a. If a charged bob is placed in an electric field above a charged plate, the electric force adds to or subtracts from gravity
##### b. The effective acceleration becomes $g_{eff} = g \pm (qE/m)$, changing the time period
##### c. If the field is horizontal, $g_{eff}$ is the vector sum $\sqrt{g^2 + (qE/m)^2}$
### C. Physical Variations
#### Fluid Buoyancy Effects
##### a. When immersed in a liquid of density $\sigma$, the bob (density $\rho$) experiences a buoyant force
##### b. The effective gravity reduces to $g_{eff} = g(1 - \sigma/\rho)$
##### c. The new time period is $T = 2\pi\sqrt{l / g(1 - \sigma/\rho)}$
#### Thermal Expansion and Elasticity
##### a. Heating the wire increases length ($l' = l(1 + \alpha \Delta T)$), increasing the time period (Time Loss)
##### b. Fractional change in time period is $\Delta T/T = \frac{1}{2} \alpha \Delta \theta$
##### c. If elasticity is considered (Young's modulus $Y$), the weight extends the wire, leading to a modified time period $T = T_{orig}(1 + mg/2AY)$
#### Variable Mass Systems
##### a. If a hollow sphere filled with water acts as a bob and leaks, the center of mass first shifts down, then returns to the center
##### b. The time period first increases (as effective length increases) and then decreases back to the original value when empty
##### c. This highlights that $l$ is the distance to the center of mass, not just the geometric center
## VI. The Torsional Pendulum
### A. Mechanics of Torsion
#### Restoring Torque
##### a. When a body suspended by a wire is twisted by an angle $\theta$, the wire exerts a restoring torque $\tau = -C\theta$
##### b. $C$ is the torsional constant of the wire, depending on the material's modulus of rigidity and geometry
##### c. The motion is SHM because torque is directly proportional to $-\theta$
#### Time Period Formula
##### a. Using the rotational analogue of Newton's law, $\tau = I\alpha$, we get $-C\theta = I(-d^2\theta/dt^2)$
##### b. This leads to $\omega = \sqrt{C/I}$, where $I$ is the moment of inertia about the axis of rotation
##### c. The time period is $T = 2\pi\sqrt{I/C}$
### B. Specific Examples
#### Geometric Shapes
##### a. For a disc suspended at its center, $I = MR^2/2$, leading to $T = 2\pi\sqrt{MR^2/2C}$
##### b. For a rod suspended at its center, $I = ML^2/12$
##### c. For a rod system formed in a V-shape, the moment of inertia must be calculated using the axis of rotation (vertical), often involving $\sin^2\theta$ components ($I = \frac{1}{3}ML^2 \sin^2\theta$)
## VII. The Compound (Physical) Pendulum
### A. Definition and General Formula
#### Concept
##### a. A compound pendulum is any rigid body (not a point mass) oscillating about a pivot point
##### b. The restoring torque is provided by gravity acting at the center of mass: $\tau = -mgd \sin\theta \approx -mgd\theta$
##### c. Here, $d$ is the distance from the pivot to the center of mass
#### Derivation
##### a. The equation of motion is $-mgd\theta = I \alpha$, where $I$ is the moment of inertia about the hinge
##### b. This yields $\omega = \sqrt{mgd/I}$
##### c. The time period is $T = 2\pi\sqrt{I_{hinge}/mgd}$
### B. Key Properties
#### Calculation of Moment of Inertia
##### a. The parallel axis theorem ($I_{hinge} = I_{CM} + md^2$) is frequently required to find $I$ about the pivot
##### b. For a disc pivoted at the rim, $I = 3/2 MR^2$ and $d=R$
##### c. For a semi-circular disc, one must use the correct center of mass distance ($4R/3\pi$)
#### Minimum Time Period
##### a. The time period varies with the distance $d$ from the center of mass
##### b. If pivoted at the center of mass ($d=0$), the time period is infinite (no restoring torque)
##### c. The time period is minimum when $d = k$ (radius of gyration), resulting in $T_{min} = 2\pi\sqrt{2k/g}$ (or $2\pi\sqrt{2r/g}$ for a ring)
#### Equivalent Simple Pendulum
##### a. The equivalent length of a physical pendulum is the length of a simple pendulum that would have the same time period
##### b. It is calculated by equating $2\pi\sqrt{L_{eq}/g} = 2\pi\sqrt{I/mgd}$
##### c. For a rod pivoted at the end, the equivalent length is $2L/3$
## VIII. Spring-Block Systems
### A. Standard Configurations
#### Horizontal and Vertical Setups
##### a. The time period for a spring block system is $T = 2\pi\sqrt{m/k}$
##### b. This formula is independent of gravity and orientation
##### c. In a vertical setup, gravity extends the spring to a new equilibrium position ($x_0 = mg/k$), but oscillation occurs around this new mean position with the same time period
#### Effect of Constant Forces
##### a. A constant force (like gravity or a constant electric field) shifts the mean position but does not alter the time period
##### b. On an inclined plane, the mean position shifts by $mg \sin\theta / k$, but $T$ remains $2\pi\sqrt{m/k}$
##### c. In an accelerating frame (lift/car), the mean position changes based on pseudo-forces, but $T$ remains invariant
### B. Combinations and Modifications of Springs
#### Cutting Springs
##### a. The spring constant is inversely proportional to length ($k \propto 1/L$)
##### b. Cutting a spring into $n$ equal parts results in each part having a stiffness of $nk$
##### c. A spring cut in ratio $l_1:l_2$ will have constants $k_1 = k(1 + l_2/l_1)$ and $k_2 = k(1 + l_1/l_2)$
#### Series and Parallel Combinations
##### a. Parallel Combination: Springs are connected such that displacement is the same, or cutting one allows the other to maintain oscillation. $k_{eq} = k_1 + k_2$
##### b. Series Combination: Springs are connected end-to-end; forces are equal, displacements add. $1/k_{eq} = 1/k_1 + 1/k_2$
##### c. A block between two springs (one on left, one on right) is technically a parallel combination because displacing the block compresses one and extends the other, both assisting the return
#### Two-Block Systems
##### a. If two masses $m_1$ and $m_2$ are connected by a spring and oscillate freely, they oscillate about the center of mass
##### b. The system is equivalent to a single mass $\mu$ oscillating with spring constant $k$
##### c. The reduced mass is given by $\mu = \frac{m_1 m_2}{m_1 + m_2}$, and the time period is $T = 2\pi\sqrt{\mu/k}$
### C. Advanced Spring Analysis
#### Young's Modulus as a Spring
##### a. A metal rod with elasticity (Young's Modulus $Y$) behaves like a spring with constant $k = YA/L$
##### b. The time period for a mass attached to such a rod is $T = 2\pi\sqrt{mL/YA}$ 103.c. This relates solid mechanics directly to SHM
#### Pulley-Spring Constraint Method
##### a. For complex pulley systems, analyze tension relationships: assume tension $T_b$ at the block and find tension $T_s$ in the spring
##### b. The equivalent spring constant relative to the block is $k_{eq} = k (T_b/T_s)^2$ 105.c. This method simplifies problems where pulleys amplify or reduce the force/displacement on the spring
## IX. Miscellaneous and Coupled Oscillations
### A. Fluid Oscillations
#### U-Tube Oscillation
##### a. A liquid column of length $L$ in a U-tube, when depressed by $x$, rises by $x$ on the other side, creating a restoring level difference of $2x$
##### b. The restoring force is equivalent to the weight of the liquid column of height $2x$: $F = -(2x\rho g)A$
##### c. The motion is SHM with time period derived from $\omega^2 = 2\rho g A / m$ (where $m = \rho A L$)
### B. Electrostatic and Gravitational Oscillations
#### Charge along Axis of Ring
##### a. A charge $-q$ placed near a positive ring of charge oscillates along the axis
##### b. For small displacements $x \ll R$, the force is proportional to $x$ ($F \propto -x/R^3$), resulting in SHM
##### c. For large displacements, the motion is oscillatory but not simple harmonic
#### Dipole Oscillation
##### a. A charge placed between two fixed electric dipoles can undergo SHM if displaced slightly
##### b. The restoring force is derived by taking the difference of forces from both dipoles ($F \propto 1/(d-x)^3 - 1/(d+x)^3$)
##### c. Using binomial expansion for small $x$, the force becomes linear ($F \propto -x$), satisfying SHM conditions
### C. Periodic Composite Motions
#### Collisions and piecewise motion
##### a. A system may involve a particle moving at constant speed, colliding elastically, and then performing half an oscillation (e.g., a ball hitting a spring-block)
##### b. The total time period is the sum of the time for linear travel ($d/u$) and the partial time period of the SHM ($T/2$)
##### c. This requires breaking the motion into distinct phases and summing the time intervals