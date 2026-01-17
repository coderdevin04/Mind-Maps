---
markmap:
  colorFreezeLevel: 3
  
---

# EMI

## I. Introduction to Electromagnetic Induction and Magnetic Flux
### A. Overview of the Topic
#### 1. Examination Weightage
##### a. In JEE Mains, typically two questions appear, accounting for roughly eight marks
##### b. In JEE Advanced, at least one question is mandatory, though historically up to two have appeared
#### 2. Core Concept
##### a. The chapter deals with the relationship between magnetic fields and induced currents, historically defined by Faraday
##### b. The topic is meant to be studied thoroughly as a "final" revision before exams due to time constraints
### B. Magnetic Flux ($\Phi$)
#### 1. Mathematical Definition
##### a. Flux is defined as the dot product of the Magnetic Field vector ($B$) and Area vector ($A$)
##### b. The formula is expressed as $\Phi = B \cdot A = BA \cos \theta$, where $\theta$ is the angle between the magnetic field and the area vector (normal to the plane)
#### 2. Calculation Nuances
##### a. If the plane of the loop makes an angle (e.g., 30°) with the field, the angle $\theta$ used in the formula must be $90° - 30° = 60°$
##### b. Flux changes can occur if $B$ changes, $A$ changes, or the angle $\theta$ changes with time
## II. Faraday’s Laws and Lenz’s Law
### A. Faraday’s Law of Induction
#### 1. The Fundamental Principle
##### a. If magnetic flux through a closed conducting loop changes with time, an induced EMF is developed
##### b. The magnitude of EMF is equal to the rate of change of flux: $|EMF| = |d\Phi/dt|$
#### 2. Calculation of Induced Current
##### a. If the loop has resistance $R$, the induced current ($i$) is $EMF / R$
##### b. Calculating average EMF involves finding the total change in flux over total time: $\Delta \Phi / \Delta t$
### B. Lenz’s Law (Direction of Induced Current)
#### 1. Definition
##### a. The induced EMF or current always opposes the cause that produces it
##### b. This law is essential for determining the direction of the induced current, complementing Faraday’s magnitude calculation
#### 2. Application Examples
##### a. Current-Carrying Wire and Loop:
#### 1. If current in a nearby wire increases, the magnetic field through the loop increases; the loop induces current to create an opposing field (reduce flux)
#### 2. If current decreases, the loop induces current to support the decaying field (increase flux)
##### b. Moving Magnet:
#### 1. If a magnet’s North pole approaches a loop, the loop induces current to create a North pole facing the magnet to repel it
#### 2. If a magnet moves away, the loop creates an attractive pole to oppose the motion
#### 3. Mechanical Implications (Falling Magnet)
##### a. A magnet dropped through a conducting ring falls with acceleration $a < g$
##### b. The induced current creates a magnetic force that repels the approaching magnet, opposing gravity
## III. Motional Electromotive Force (EMF)
### A. Translational Motion (Moving Rod)
#### 1. Mechanism of Potential Difference
##### a. A conducting rod moving with velocity $v$ in a magnetic field $B$ experiences a magnetic force ($F_m = qvB$) on charge carriers
##### b. Positive and negative charges separate to opposite ends until the electric force ($qE$) balances the magnetic force ($qvB$)
#### 2. Formula and Circuit Equivalent
##### a. The induced EMF is $\epsilon = vBL$, where $L$ is the length of the rod
##### b. The moving rod acts as a battery with EMF $vBL$; the polarity is determined by the direction of the magnetic force on positive charges
#### 3. Energy Conservation
##### a. If current flows, a magnetic force ($F = ILB$) acts on the rod opposing its motion
##### b. Mechanical work done to maintain velocity against this force is converted into electrical energy (heat/light)
### B. Rotational Motion (Rotating Rod)
#### 1. Setup and Formula
##### a. A rod of length $L$ rotating with angular velocity $\omega$ in a magnetic field develops EMF between its center and rim
##### b. The EMF is derived as $\epsilon = \frac{1}{2} B \omega L^2$
#### 2. Analogy to Batteries
##### a. Small segments of the rod act as miniature batteries in series, summing up to the total EMF
##### b. Multiple rods (spokes) or a solid disc connected between the center and rim act as parallel batteries; the equivalent EMF remains $\frac{1}{2} B \omega L^2$ regardless of the number of spokes
## IV. Generators and Power
### A. AC Generator Mechanism
#### 1. Construction
##### a. A coil with $N$ turns and Area $A$ rotates with angular velocity $\omega$ in a magnetic field $B$
##### b. The flux varies as $\Phi = NBA \cos(\omega t)$ due to the changing angle
#### 2. Output Equations
##### a. Differentiating flux gives the induced EMF: $\epsilon = NBA\omega \sin(\omega t)$
##### b. This produces an alternating current (AC) behaving as a sine wave
### B. Power Generation
#### 1. Power Formulas
##### a. Instantaneous power is $P = \frac{\epsilon^2}{R} = \frac{(NBA\omega)^2}{R} \sin^2(\omega t)$
##### b. Average power is half the peak power: $P_{avg} = \frac{(NBA\omega)^2}{2R}$
#### 2. Scaling Relationships
##### a. If the same wire is used to make a loop with half the number of turns ($N \to N/2$), the loop radius/side doubles, causing the Area to quadruple ($A \to 4A$)
##### b. Since Power $\propto N^2 A^2$, the new power becomes 4 times the original ($P' = 4P_0$)
## V. Induced Electric Field and Eddy Currents
### A. Induced Electric Field
#### 1. Origin
##### a. A changing magnetic field produces an electric field, even in the absence of a conductor
##### b. This field is non-conservative (unlike electrostatic fields) and exerts force on charges ($F = qE$)
#### 2. Calculation Formula ($\oint E \cdot dl = -d\Phi/dt$)
##### a. Inside a Cylindrical Region ($r < R$): The electric field is directly proportional to distance ($E \propto r$), derived as $E = -\frac{r}{2} \frac{dB}{dt}$
##### b. Outside a Cylindrical Region ($r > R$): The electric field is inversely proportional to distance ($E \propto 1/r$), derived as $E = -\frac{R^2}{2r} \frac{dB}{dt}$
### B. Eddy Currents
#### 1. Phenomenon
##### a. Bulk conductors (like plates) moving in magnetic fields develop circulating currents (eddies) due to changing flux
##### b. These currents cause energy loss through heat and magnetic damping (braking effect)
#### 2. Mitigation
##### a. Slots or cuts are made in the conductor to interrupt the path of eddy currents, minimizing energy loss
## VI. Inductance
### A. Self-Inductance ($L$)
#### 1. Definition
##### a. The property of a coil to oppose changes in the current flowing through itself by inducing a "back EMF"
##### b. Defined by the relationship $\Phi = L I$
#### 2. Solenoid Inductance
##### a. For a solenoid of length $l$, radius $r$, and turn density $n$: $L = \mu_0 n^2 (\pi r^2 l) = \mu_0 n^2 V$
##### b. Inductance depends purely on geometry, not on the current
### B. Mutual Inductance ($M$)
#### 1. Definition
##### a. The property where a change in current in one coil induces an EMF in a neighboring coil
##### b. Defined by $\Phi_2 = M I_1$ (Flux in coil 2 due to current in coil 1)
#### 2. Reciprocity Theorem
##### a. The mutual inductance is the same regardless of which coil carries the current: $M_{12} = M_{21}$
##### b. Calculation strategy: Drive current in the geometry where magnetic field calculation is easier (e.g., solenoid or long wire) and calculate flux in the other
#### 3. Specific Geometries
##### a. Wire and Rectangular Loop: $M = \frac{\mu_0 b}{2\pi} \ln(1 + \frac{l}{a})$
##### b. Concentric Coils: $M = \frac{\mu_0 \pi R_{small}^2}{2 R_{large}}$
##### c. Solenoid inside Solenoid: $M = \mu_0 n_1 n_2 (\pi r_{small}^2) l$
## VII. LR Circuits (Inductor-Resistor)
### A. Kirchhoff’s Law for Inductors
#### 1. Potential Drop
##### a. Moving across an inductor in the direction of current involves a potential drop of $-L \frac{di}{dt}$
##### b. If current increases ($di/dt > 0$), the inductor acts as a battery opposing the current; if current decreases, it supports the current
### B. Transient States
#### 1. Growth of Current
##### a. When a switch is closed, current rises from 0 to max ($E/R$).
##### b. Equation: $I = \frac{E}{R} (1 - e^{-\frac{t}{\tau}})$, where $\tau = L/R$ is the time constant
##### c. At one time constant ($\tau$), current reaches ~63% of maximum
#### 2. Decay of Current
##### a. When battery is removed and loop closed, current decays.
##### b. Equation: $I = I_0 e^{-\frac{t}{\tau}}$
##### c. At one time constant ($\tau$), current drops to ~37% of maximum
### C. Energy in Inductors
#### 1. Stored Energy
##### a. Energy stored in the magnetic field of an inductor is $U = \frac{1}{2} L I^2$
##### b. Inductors absorb energy when current increases and release energy when current decreases
#### 2. Energy Density
##### a. Energy per unit volume in a magnetic field is $u = \frac{B^2}{2\mu_0}$
## VIII. LC Oscillations
### A. Mechanism
#### 1. Energy Exchange
##### a. A circuit containing an ideal inductor ($L$) and charged capacitor ($C$) oscillates energy between the electric field of the capacitor and magnetic field of the inductor
##### b. This is analogous to a mechanical spring-mass system ($mass \leftrightarrow inductance$, $spring constant \leftrightarrow 1/capacitance$)
### B. Mathematics of Oscillation
#### 1. Differential Equation
##### a. Applying Kirchhoff’s law leads to $\frac{d^2q}{dt^2} + \frac{1}{LC}q = 0$, which is a Simple Harmonic Motion (SHM) equation
##### b. The angular frequency is $\omega = \frac{1}{\sqrt{LC}}$, and time period is $T = 2\pi \sqrt{LC}$
#### 2. Current and Charge Relations
##### a. Maximum current is $I_0 = E_0 \sqrt{\frac{C}{L}}$ or $I_0 = \frac{q_{max}}{\sqrt{LC}}$
##### b. Phasor diagrams can be used to calculate time taken for charge/current to reach specific values (e.g., time to reach half charge is $T/6$)
