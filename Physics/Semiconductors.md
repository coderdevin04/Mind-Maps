---
markmap:
  colorFreezeLevel: 3
---

# Semiconductors

## I. Classification of Materials and Energy Band Theory
### A. Classification based on Conductivity
#### 1. Conductors (Metals)
##### a. Electrical current passes easily when a potential difference is applied
##### b. In energy band theory, the Conduction Band (CB) and Valence Band (VB) overlap
##### c. Electrons are simultaneously bonded and free for conduction
#### 2. Insulators
##### a. Materials that do not conduct electricity
##### b. Large energy gap ($E_g$) between VB and CB, approximately 3 eV or more
##### c. High lattice energy causes them to melt rather than conduct when energy is supplied
#### 3. Semiconductors
##### a. Materials with conductivity between conductors and insulators
##### b. Moderate band gap energy (around 1 eV; e.g., Si ~1.1 eV, Ge ~0.7 eV)
##### c. Electrons can jump from VB to CB upon receiving thermal energy
### B. Energy Band Structure
#### 1. Formation of Bands
##### a. In isolated atoms, shells have fixed discrete energies
##### b. When atoms bond in a crystal lattice, valence shell energies fluctuate, forming a range or "band" of energies
#### 2. Band Definitions
##### a. Valence Band (VB): The lower energy band containing bonded valence electrons
  - i. The highest energy level in the VB is denoted by $E_v$
  - ii. At absolute zero or without excitation, all valence electrons reside here
##### b. Conduction Band (CB): The higher energy band
  - i. The lowest energy level in the CB is denoted by $E_c$
  - ii. Conduction is possible only when electrons exist in this band
#### 3. Band Gap ($E_g$)
##### a. Defined as the energy difference between the minimum of the CB and the maximum of the VB ($E_g = E_c - E_v$)
##### b. Also known as the forbidden energy gap where no electron states exist
##### c. This value is material-dependent
## II. Intrinsic Semiconductors
### A. Characteristics
#### 1. Purity
##### a. Elemental or pure forms of semiconductors (e.g., Silicon, Germanium) without impurities
#### 2. Conduction Mechanism
##### a. At room temperature, some electrons gain thermal energy and jump from VB to CB
##### b. This jump creates a free electron in the CB and a vacancy (hole) in the VB
#### 3. Carrier Concentration
##### a. The number of free electrons ($n_e$) equals the number of holes ($n_h$)
##### b. There are no majority charge carriers; both carriers exist in equal amounts
##### c. Mass Action Law applies: $n_i^2 = n_e \times n_h$, where $n_i$ is the intrinsic carrier concentration
### B. Concept of Holes
#### 1. Definition
##### a. Holes are vacant sites in the valence band created when an electron leaves
##### b. They act as virtual positive charge carriers
#### 2. Movement
##### a. Holes move in the direction of the electric field (effective positive charge behavior)
##### b. Movement occurs via the "hopping" of bonded electrons into the vacant spot
#### 3. Physical Properties
##### a. Effective mass of a hole is considered greater than that of an electron
##### b. Mobility of holes is less than that of free electrons because their motion involves sequential bond breaking/hopping
## III. Extrinsic Semiconductors (Doping)
### A. Process of Doping
#### 1. Definition
##### a. Adding external impurities to intrinsic semiconductors to increase conductivity
#### 2. Purpose
##### a. To create majority charge carriers and reduce temperature dependence of conductivity
### B. N-Type Semiconductors
#### 1. Doping Element
##### a. Formed by doping Group 14 (Silicon) with Group 15 (Pentavalent) elements like Phosphorus
#### 2. Structure and Carriers
##### a. Pentavalent atoms have 5 valence electrons: 4 form bonds with Silicon, the 5th is loosely bound
##### b. Small energy is required to detach the 5th electron, making it free for conduction
##### c. Majority carriers are electrons; minority carriers are holes
#### 3. Band Diagram
##### a. Creates a "Donor Level" energy state slightly below the Conduction Band
##### b. Electrons can easily jump from the donor level to the CB
#### 4. Electrical Nature
##### a. The material remains electrically neutral (total protons = total electrons)
### B. P-Type Semiconductors
#### 1. Doping Element
##### a. Formed by doping Group 14 with Group 13 (Trivalent) elements like Boron
#### 2. Structure and Carriers
##### a. Trivalent atoms have 3 valence electrons: forms 3 bonds, leaving one vacancy (hole) in the lattice
##### b. The impurity atom accepts an electron to fill the hole, acting as an "Acceptor"
##### c. Majority carriers are holes; minority carriers are electrons
#### 3. Band Diagram
##### a. Creates an "Acceptor Level" energy state slightly above the Valence Band
##### b. Electrons from the VB can easily jump to the acceptor level, creating holes in the VB
## IV. PN Junction Diode
### A. Formation
#### 1. Junction Creation
##### a. Formed by joining P-type and N-type semiconductor materials
#### 2. Diffusion Process
##### a. Electrons from N-side diffuse to P-side; Holes from P-side diffuse to N-side due to concentration gradient
##### b. This constitutes the diffusion current (from P to N)
#### 3. Depletion Region
##### a. As carriers diffuse, immobile ions (negative acceptors in P-side, positive donors in N-side) are exposed near the junction
##### b. An internal electric field develops from N-side (positive) to P-side (negative)
##### c. This region, devoid of free charge carriers, is called the Depletion Region
#### 4. Barrier Potential
##### a. The electric field creates a potential difference that opposes further diffusion of majority carriers
##### b. Typical values: ~0.7V for Silicon, ~0.3V for Germanium
### B. Biasing Modes
#### 1. Forward Bias
##### a. Connection: P-side connected to Higher Potential (Positive), N-side to Lower Potential (Negative)
##### b. Mechanism: External field opposes the internal barrier field.
  - i. Holes and electrons are pushed towards the junction
  - ii. Depletion width decreases; Barrier potential decreases
##### c. Current: Majority carriers cross the junction, resulting in significant current (mA range)
##### d. Circuit Model: Replaced by a battery ($V_{knee}$) and resistance ($R_f$) or a short wire if ideal
#### 2. Reverse Bias
##### a. Connection: P-side connected to Lower Potential, N-side to Higher Potential
##### b. Mechanism: External field supports the internal barrier field.
  - i. Carriers are pulled away from the junction
  - ii. Depletion width increases; Barrier potential increases
##### c. Current: Negligible "Leakage" or "Reverse Saturation Current" due to minority carriers (micro/nano-amperes)
##### d. Circuit Model: Acts as an Open Circuit (infinite resistance) in ideal cases
### C. I-V Characteristics
#### 1. Forward Characteristics
##### a. Current is negligible until applied voltage exceeds Knee Voltage
##### b. Beyond Knee Voltage, current increases exponentially, then linearly
#### 2. Reverse Characteristics
##### a. Small constant saturation current initially
##### b. Breakdown: At a critical "Breakdown Voltage," current increases sharply
  - i. Zener Breakdown: High electric field breaks bonds directly
  - ii. Avalanche Breakdown: Accelerated minority carriers collide with atoms, releasing more carriers
## V. Applications of Diodes
### A. Rectifiers (AC to DC Conversion)
#### 1. Function
##### a. Converts alternating current (AC) to direct current (DC)
#### 2. Half-Wave Rectifier
##### a. Uses a single diode
##### b. Conducts only during the positive half-cycle of AC input
##### c. Output frequency equals input frequency
#### 3. Full-Wave Rectifier (Center Tap)
##### a. Uses two diodes and a center-tapped transformer
##### b. Diodes conduct alternately during positive and negative half-cycles
##### c. Output frequency is double the input frequency
#### 4. Filter Circuits
##### a. Capacitors are used to smooth the pulsating DC output by absorbing AC components and blocking DC
### B. Zener Diode
#### 1. Function
##### a. Heavily doped diode designed to operate in the breakdown region
##### b. Primarily used as a Voltage Regulator
#### 2. Operation
##### a. Forward Bias: Acts like a normal diode
##### b. Reverse Bias ($V < V_z$): Acts as an open circuit
##### c. Reverse Bias ($V > V_z$): Voltage across the diode remains constant ($V_z$) regardless of current fluctuations
##### d. Behaves like a battery of voltage $V_z$ opposing the source
### C. Optoelectronic Devices
#### 1. Light Emitting Diode (LED)
##### a. Operates in Forward Bias
##### b. Recombination of electrons and holes at the junction releases energy
##### c. Energy is released as photons (visible light) if the band gap corresponds to the visible spectrum
#### 2. Photodiode
##### a. Operates in Reverse Bias
##### b. Used for detecting light signals
##### c. Incident light breaks bonds, creating electron-hole pairs, which increases the reverse saturation current
#### 3. Solar Cell
##### a. Operates with no external biasing
##### b. Converts solar energy into electrical energy
##### c. Light incident on the depletion region creates e-h pairs which are separated by the internal electric field, creating a potential difference
## VI. Digital Electronics and Logic Gates
### A. Binary System
#### 1. Representation
##### a. Inputs and outputs are represented as voltage levels: High (5V) = 1, Low (0V) = 0
##### b. $N$ inputs result in $2^n$ possible combinations
### B. Basic Logic Gates
#### 1. OR Gate
##### a. Logic: Output is 1 if any input is 1 ($Y = A + B$)
##### b. Truth Table: 0+0=0, 0+1=1, 1+0=1, 1+1=1
#### 2. AND Gate
##### a. Logic: Output is 1 only if both inputs are 1 ($Y = A \cdot B$)
##### b. Truth Table: 0.0=0, 0.1=0, 1.0=0, 1.1=1
#### 3. NOT Gate (Inverter)
##### a. Logic: Inverts the input ($Y = \bar{A}$)
##### b. Truth Table: 0->1, 1->0
### C. Universal Gates
#### 1. NAND Gate
##### a. Combination of AND + NOT ($Y = \overline{A \cdot B}$)
##### b. Can be used to construct all other basic gates
#### 2. NOR Gate
##### a. Combination of OR + NOT ($Y = \overline{A + B}$)
### D. Exclusive Gates
#### 1. XOR (Exclusive OR)
##### a. Logic: Output is 1 only if inputs are different ($Y = A\bar{B} + \bar{A}B$)
##### b. Truth Table: 0,0->0; 0,1->1; 1,0->1; 1,1->0
#### 2. XNOR (Exclusive NOR)
##### a. Logic: Output is 1 only if inputs are same ($Y = A\bar{B} + \bar{A}B$ whole bar or $AB + \bar{A}\bar{B}$)
##### b. Truth Table: 0,0->1; 0,1->0; 1,0->0; 1,1->1
### E. Boolean Algebra and De Morgan’s Theorems
#### 1. De Morgan’s Laws
##### a. "Break the line, change the sign"
##### b. $\overline{A + B} = \bar{A} \cdot \bar{B}$
##### c. $\overline{A \cdot B} = \bar{A} + \bar{B}$
#### 2. Useful Identities
##### a. $A + 1 = 1$
##### b. $A + A = A$
##### c. $A \cdot A = A$
##### d. $A + \bar{A} = 1$
##### e. $A \cdot \bar{A} = 0$