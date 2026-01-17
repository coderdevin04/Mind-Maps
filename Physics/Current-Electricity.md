---
markmap:
  colorFreezeLevel: 3
---

# Current-Electricity

## I. Introduction and Fundamental Concepts
### A. Electric Current
#### Definition
  - Current is defined as the rate of flow of charge, expressed mathematically as $I = dq/dt$
#### Nature of Quantity
##### a.  It is a scalar quantity because it does not follow vector laws of addition, despite having a direction
##### b.  The unit is Ampere (Coulomb per second), and it is considered a fundamental quantity
#### Calculation Methods
##### a.  Differentiation: If charge is a function of time ($q=t^2$), find current by differentiating ($dq/dt$) to get instantaneous current
##### b.  Integration: To find total charge from current, integrate current with respect to time ($\int I dt$), which represents the area under an $I-t$ graph
##### c.  Average Current: Defined as total charge divided by total time ($I_{avg} = \Delta q / \Delta t$)
### B. Current Density ($J$)
#### Definition
  - Current flowing per unit area, where the area is perpendicular to the current flow ($J = I/A$)
#### Calculation
##### a.  If current density is non-uniform, current is calculated via integration or dot product: $I = \int \vec{J} \cdot d\vec{A}$
##### b.  It relates to the microscopic form of Ohm's Law: $\vec{J} = \sigma \vec{E}$, where $\sigma$ is conductivity
## II. Microscopic Model of Current
### A. Mechanism of Conduction
#### Carrier Density ($n$)
  - Defined as the number of free electrons per unit volume, which is material-dependent
#### Motion of Electrons
##### a.  Without a battery, electrons move randomly with an average velocity of zero
##### b.  With a battery, an electric field is set up, causing electrons to drift towards the positive terminal while colliding with the lattice
### B. Drift Velocity ($v_d$)
#### Definition
  - The average speed with which electrons drift toward the positive terminal of the battery
#### Formula
  - $v_d = \frac{eE}{m} \tau$
##### a.  $e$: Charge on an electron
##### b.  $E$: Electric field
##### c.  $m$: Mass of an electron (constant)
##### d.  $\tau$: Relaxation time
#### Relaxation Time ($\tau$)
  - The average time between successive collisions of electrons
##### a.  Temperature dependence: Increasing temperature increases collision frequency, thereby decreasing $\tau$
### C. Mobility ($\mu$)
#### Definition
  - Drift velocity attained per unit electric field ($\mu = v_d / E$)
#### Relationship to Mass
  - Heavier particles (like holes in semiconductors) have lower mobility compared to lighter particles (electrons)
#### Formula
  - Substituting drift velocity yields $\mu = \frac{e\tau}{m}$
### D. Relation between Current and Drift Velocity
#### Formula
  - $I = n e A v_d$ (Mnemonics: "NAIVED" or "VEENA")
#### Derivation of Ohm's Law
  - Substituting $v_d$ leads to $I = \frac{n e^2 \tau A}{m} \frac{V}{L}$, which rearranges to $V = I (\frac{mL}{n e^2 \tau A})$
## III. Resistance and Resistivity
### A. Resistance ($R$)
#### Definition
  - The property of a material to oppose the flow of current
#### Macroscopic Formula
  - $R = \rho \frac{L}{A}$
##### a.  Directly proportional to length ($L$)
##### b.  Inversely proportional to the area of cross-section ($A$)
#### Microscopic Formula
  - $R = \frac{m}{n e^2 \tau} \frac{L}{A}$
#### Ohm's Law
  - At constant temperature, $V \propto I$, making Resistance the slope of a $V-I$ graph
##### a.  The slope of an $I-V$ graph represents Conductance ($G = 1/R$)
### B. Resistivity ($\rho$)
#### Formula
  - $\rho = \frac{m}{n e^2 \tau}$
#### Properties
##### a.  Independent of the dimensions (length and area) of the conductor
##### b.  Depends on the nature of the material (via carrier density $n$) and temperature (via relaxation time $\tau$)
### C. Temperature Dependence
#### Conductors
##### a.  Formula: $R = R_0 (1 + \alpha \Delta T)$, where $\alpha$ is the thermal coefficient of resistance
##### b.  Behavior: As temperature rises, collisions increase, $\tau$ decreases, and Resistance increases
#### Semiconductors
##### a.  Behavior: As temperature rises, carrier density ($n$) increases significantly, dominating the decrease in $\tau$, causing Resistance to fall
##### b.  Graph: Resistance vs. Temperature is a curve sloping downwards
### D. Color Coding of Resistors
#### Method
  - Uses bands on resistors to determine value and tolerance
##### a.  First two bands: Significant figures/digits
##### b.  Third band: Multiplier ($10^x$)
##### c.  Fourth band: Tolerance (Gold $\pm 5\%$, Silver $\pm 10\%$, No Color $\pm 20\%$)
#### Mnemonic
  - "BB ROY of Great Britain has Very Good Wife" (Black, Brown, Red, Orange, Yellow, Green, Blue, Violet, Grey, White)
## IV. Circuit Analysis Techniques
### A. Combinations of Resistors
#### Series Combination
##### a.  Condition: Current is the same through all resistors
##### b.  Voltage Divider: Voltage splits proportionally to resistance ($V_1 = V \frac{R_1}{R_1 + R_2}$)
#### Parallel Combination
##### a.  Condition: Potential difference is the same across all resistors
##### b.  Current Divider: Current splits inversely proportional to resistance ($I_1 = I \frac{R_2}{R_1 + R_2}$)
#### Stretching Wires
  - If a wire is stretched to $n$ times its length, the new resistance becomes $n^2$ times the original resistance ($R_{new} = n^2 R_{old}$) due to area reduction
### B. Kirchhoff’s Laws
#### Kirchhoff's Current Law (KCL)
##### a.  Principle: Conservation of Charge
##### b.  Rule: The algebraic sum of currents at any junction is zero ($\sum I_{in} = \sum I_{out}$)
#### Kirchhoff's Voltage Law (KVL)
##### a.  Principle: Conservation of Energy
##### b.  Rule: The net voltage drop across any closed loop is zero
##### c.  Sign Convention: traversing opposite to current is $+IR$, traversing with current is $-IR$; leaving battery positive is $+E$
### C. Special Circuit Techniques
#### Nodal Analysis
  - Assigning 0V to a reference node (usually battery negative) and writing KCL equations for unknown nodes
#### Symmetry Rules
##### a.  Folding Symmetry (Along the line of inputs): Potentials are equal at symmetric points; overlapping nodes can be connected
##### b.  Mirror Symmetry (Perpendicular to line of inputs): Current entering a branch mirrors the current leaving the symmetric branch
#### Wheatstone Bridge
##### a.  Balanced Condition: $R_1/R_2 = R_3/R_4$
##### b.  Result: No current flows through the central galvanometer/resistor, allowing it to be removed for calculation
##### c.  Unbalanced Bridge: Must use Nodal analysis or KVL to solve
## V. Cells and Batteries
### A. Fundamental Parameters
#### Electromotive Force (EMF, $\mathcal{E}$)
  - The potential difference across a battery in an open circuit (when no current flows)
#### Internal Resistance ($r$)
  - Resistance within the cell due to electrodes and electrolyte
#### Terminal Voltage ($V$)
##### a.  Discharging: $V = \mathcal{E} - Ir$ (Voltage is less than EMF)
##### b.  Charging: $V = \mathcal{E} + Ir$ (Voltage is greater than EMF)
### B. Grouping of Cells
#### Series Grouping
##### a.  Net EMF: $\mathcal{E}_{eq} = \mathcal{E}_1 + \mathcal{E}_2$ (if supporting)
##### b.  Net Resistance: $r_{eq} = r_1 + r_2$
#### Parallel Grouping
##### a.  Formula: $\frac{\mathcal{E}{eq}}{r{eq}} = \frac{\mathcal{E}_1}{r_1} + \frac{\mathcal{E}_2}{r_2}$
##### b.  For $n$ identical cells: $\mathcal{E}{eq} = \mathcal{E}$, $r{eq} = r/n$
#### Condition for Maximum Power
  - In a mixed grouping, current is maximum when external resistance ($R$) equals net internal resistance ($R_{int}$)
## VI. Measuring Instruments
### A. Meter Bridge
#### Working Principle
  - Based on a balanced Wheatstone Bridge
#### Structure
  - Uses a 1-meter wire, hence the name
#### Formula
  - At the null point (no current in galvanometer), $\frac{R}{S} = \frac{L}{100-L}$
#### End Corrections
  - Accounts for extra length/resistance at the binding screws (added to lengths $L_1$ and $L_2$)
### B. Potentiometer
#### Function
  - Replaces a voltmeter to measure EMF precisely because it draws no current at the null point (infinite resistance ideally)
#### Potential Gradient ($k$)
  - Voltage drop per unit length of the wire ($V/L$)
#### Working Principle
##### a.  Primary circuit sets up a potential gradient
##### b.  Secondary circuit EMF is compared against the potential drop on the wire length
##### c.  Null Point Condition: Voltage across wire length equals the secondary EMF ($kL = \mathcal{E}$)
## VII. Heating Effects and Power
### A. Formulas
#### Power ($P$)
  - Rate of doing work, $P = VI = I^2R = V^2/R$
#### Heat Energy ($H$)
  - $H = I^2Rt$ (Joule Heating)
### B. Rated Devices (Bulbs)
#### Ratings
  - Bulbs have a rated Power ($P_{rated}$) and Voltage ($V_{rated}$)
#### Calculating Resistance
  - The filament resistance is constant and calculated as $R = \frac{V_{rated}^2}{P_{rated}}$
#### Actual Power
  - The power consumed in a circuit depends on applied voltage, calculated as $P_{actual} = I_{circuit}^2 R$
### C. Brightness of Bulbs
#### Rule
  - Brightness depends on the actual power consumed in the circuit, not just the rated power
#### Series Connection
##### a.  Current is constant ($P \propto R$).
##### b.  Bulb with lower rated power (higher resistance) glows brighter
#### Parallel Connection (House Wiring)
##### a.  Voltage is constant ($P \propto 1/R$).
##### b.  Bulb with higher rated power (lower resistance) glows brighter