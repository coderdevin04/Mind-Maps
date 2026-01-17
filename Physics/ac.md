---
markmap:
  colorFreezeLevel: 3
---

# AC

## I. Fundamentals of Alternating Current (AC) vs. Direct Current (DC)
### A. Characteristics of Direct Current (DC)
#### Definition and Flow
##### a. DC is defined as current where both magnitude and direction remain constant
##### b. It does not change with time, similar to current from a battery
##### c. It maintains a constant value, such as 2 Amperes or 10 Amperes continuously
### B. Characteristics of Alternating Current (AC)
#### Core Definition
##### a. AC is defined by variations in both magnitude and direction
##### b. The magnitude changes continuously with time, while direction reverses periodically 2, 3.c. For a current to be AC, the direction must alternate (positive and negative values) at regular intervals
#### Waveforms and Representation
##### a. Sinusoidal AC: The standard form used in the syllabus is $I = I_0 \sin(\omega t)$
##### b. Non-Sinusoidal Forms:
  - i. Sawtooth Wave: Resembles the sharp teeth of a saw (or "grandfather’s teeth"), with linear inclines and sharp drops
  - ii. Square/Pulse Waves: Current stays positive for a duration, then negative, commonly seen in electronics
##### c. Superimposed DC and AC:
  - i. An equation like $I = 2 + \sin(\omega t)$ represents a mixture of DC and AC
  - ii. This shifts the graph vertically, meaning the current may pulsate but not necessarily reverse direction if the DC offset is large enough
### C. Syllabus Scope
#### Focus on Sinusoidal Functions
##### a. The curriculum primarily focuses on sinusoidal functions where amplitude ($I_0$) is considered constant
##### b. Complex waves (like square waves) are typically analyzed in higher studies or specific contexts like rectifiers
## II. Mathematical Metrics of Alternating Current
### A. Average Value ($I_{avg}$)
#### Physical Definition
##### a. $I_{avg}$ is defined as the equivalent constant DC that would transfer the same amount of charge in the same circuit over the same time interval
##### b. Mathematically derived from the area under the Current vs. Time graph, which represents total charge
#### Calculation Formula
##### a. The general formula is $I_{avg} = \frac{\int_{t_1}^{t_2} I \, dt}{t_2 - t_1}$
##### b. It represents the total charge divided by the total time interval
#### Values for Sinusoidal Current ($I = I_0 \sin \omega t$)
##### a. Full Cycle: The average value over a complete cycle ($0$ to $T$) is zero because the positive and negative areas cancel out
##### b. Half Cycle:
  - i. Calculated by integrating from $0$ to $T/2$
  - ii. The result is $I_{avg} = \frac{2I_0}{\pi}$ for the positive half-cycle
##### c. Squared Functions: The average of $\sin^2\theta$ or $\cos^2\theta$ over a complete cycle is $1/2$
### B. Root Mean Square Value ($I_{rms}$)
#### Motivation and Definition
##### a. Since the average value over a full cycle is zero, it cannot be used to calculate power or heat; thus, RMS is used
##### b. $I_{rms}$ is the equivalent DC that produces the same amount of heat (energy) in a resistor over the same time period
##### c. It acts as the "Effective Value" of the current
#### Mathematical Derivation
##### a. The process follows the name: Square the function $\to$ take the Mean $\to$ take the Square Root
##### b. Formula: $I_{rms} = \sqrt{\frac{\int I^2 \, dt}{\int dt}}$
#### Standard Results
##### a. For a sinusoidal current $I = I_0 \sin(\omega t)$, $I_{rms} = \frac{I_0}{\sqrt{2}}$
##### b. Household ratings (e.g., 220V) always refer to RMS values unless specified otherwise
## III. AC Circuit Components and Behavior
### A. Pure Resistive Circuit (R-Circuit)
#### Phase Relationship
##### a. Voltage and current oscillate in the same phase
##### b. There is no phase difference ($\phi = 0$); when voltage is maximum, current is maximum
#### Formulas
##### a. Peak current is defined as $I_0 = \frac{V_0}{R}$
##### b. The phasor diagram shows current ($I$) and voltage ($V_R$) vectors overlapping
### B. Pure Inductive Circuit (L-Circuit)
#### Role of Inductor
##### a. An inductor opposes changes in current, described metaphorically as "ghamandi" (arrogant/stubborn)
##### b. It stores energy in the form of a magnetic field
#### Phase Relationship
##### a. Voltage leads the current by $\pi/2$ (90 degrees), or current lags voltage by $\pi/2$
##### b. Mnemonic: "IPL" (Inductor Potential Leads) implies voltage is ahead
#### Inductive Reactance ($X_L$)
##### a. This is the resistance offered by the inductor in an AC circuit
##### b. Formula: $X_L = \omega L = 2\pi f L$
##### c. Dependence: $X_L$ is directly proportional to frequency ($f$); higher frequency means higher opposition
### C. Pure Capacitive Circuit (C-Circuit)
#### Role of Capacitor
##### a. Acts as an open circuit for DC (blocks DC) but allows AC to pass
##### b. Described metaphorically as "bhukkad" (greedy/eager), allowing current to establish before voltage peaks
#### Phase Relationship
##### a. Current leads the voltage by $\pi/2$, or voltage lags current by $\pi/2$
#### Capacitive Reactance ($X_C$)a. The resistance offered by a capacitor in an AC circuit
##### b. Formula: $X_C = \frac{1}{\omega C} = \frac{1}{2\pi f C}$
##### c. Dependence: $X_C$ is inversely proportional to frequency; at very high frequencies, it acts like a short circuit (low resistance)
## IV. Series LCR Circuits
### A. Phasor Diagrams and Voltage
#### Vector Addition
##### a. Voltages across R, L, and C cannot be added algebraically; they must be added vectorially (phasors)
##### b. Current ($I$) is the reference vector as it is common in series
#### Voltage Relations
##### a. $V_R$ is in phase with $I$
##### b. $V_L$ leads $I$ by $90^\circ$ and $V_C$ lags $I$ by $90^\circ$
##### c. Net Voltage: $V_{net} = \sqrt{V_R^2 + (V_L - V_C)^2}$
### B. Impedance ($Z$)
#### Definition
##### a. Impedance is the net effective resistance offered by the combination of R, L, and C
#### Calculation
##### a. Derived from the impedance triangle: $Z = \sqrt{R^2 + (X_L - X_C)^2}$
##### b. Peak current is determined by $I_0 = \frac{V_0}{Z}$
### C. Phase Difference ($\phi$)
#### Determination
##### a. Represents the angle by which net voltage leads or lags the current
##### b. Formula: $\tan \phi = \frac{V_L - V_C}{V_R} = \frac{X_L - X_C}{R}$
#### Leading vs. Lagging
##### a. If $V_L > V_C$ ($X_L > X_C$), the circuit is inductive, and voltage leads
##### b. If $V_C > V_L$ ($X_C > X_L$), the circuit is capacitive, and current leads
## V. Resonance in AC Circuits
### A. Resonance Condition
#### Requirement
##### a. Resonance occurs when the Inductive Reactance equals Capacitive Reactance ($X_L = X_C$)
##### b. This implies the voltages across the inductor and capacitor cancel each other out ($V_L = V_C$)
#### Resonant Frequency ($\omega_r$)
##### a. Derived from $\omega L = \frac{1}{\omega C}$
##### b. Formula: $\omega_r = \frac{1}{\sqrt{LC}}$ or $f_r = \frac{1}{2\pi \sqrt{LC}}$
### B. Circuit Characteristics at Resonance
#### Impedance and Current
##### a. Impedance is minimal and purely resistive ($Z_{min} = R$)
##### b. Current is maximal ($I_{max} = \frac{V}{R}$)
##### c. The phase difference between voltage and current is zero ($\phi = 0$)
#### Voltage Amplification
##### a. Although net voltage across L and C is zero, individual voltages across them can be very high
##### b. The total source voltage appears entirely across the resistor
### C. Quality Factor (Q-Factor) and Bandwidth
#### Sharpness of Resonance
##### a. Q-factor determines the sharpness of the current peak at resonance; higher Q means sharper resonance
##### b. It relates to "selectivity" in radio tuning (distinguishing between frequencies)
#### Formulas
##### a. Q-Factor formula: $Q = \frac{1}{R} \sqrt{\frac{L}{C}}$ or $\frac{\omega_r L}{R}$
##### b. Bandwidth: The range of frequencies where power is at least half the maximum ($I \geq I_{max}/\sqrt{2}$)
##### c. A narrower bandwidth implies higher selectivity
## VI. Power in AC Circuits
### A. Power Formula
#### General Expression
##### a. Power is not simply $V \times I$ due to phase differences
##### b. Average Power: $P = V_{rms} I_{rms} \cos \phi$
#### Power Factor ($\cos \phi$)
##### a. It is the factor that dictates how much power is actually consumed
##### b. Calculated from the impedance triangle: $\cos \phi = \frac{R}{Z}$
##### c. Range: $0$ to $1$ (or $0$ to $-1$ strictly speaking of cosine, but magnitude acts as the factor)
### B. Wattless Current
#### Definition
##### a. The component of current ($I_{rms} \sin \phi$) that is perpendicular to the voltage phasor
##### b. This component consumes zero average power over a cycle
#### Application
##### a. Pure inductors and capacitors have $\phi = 90^\circ$, making $\cos \phi = 0$, thus consuming zero average power
## VII. Analogies and Advanced Concepts
### A. Mechanical Analogy (Damped Oscillations)
#### Comparison to Spring-Mass System
##### a. The LCR circuit equation is analogous to the differential equation of a damped mechanical oscillator
##### b. Inductance ($L$) behaves like Mass ($m$) (inertia)
##### c. Resistance ($R$) behaves like the Damping Constant ($b$) (friction) 52.d. Capacitance ($1/C$) behaves like the Spring Constant ($k$) (stiffness)
#### Equation Matching
##### a. Damped mechanical equation: $\frac{d^2x}{dt^2} + \frac{b}{m}\frac{dx}{dt} + \frac{k}{m}x = 0$
##### b. LCR charge equation: $\frac{d^2q}{dt^2} + \frac{R}{L}\frac{dq}{dt} + \frac{1}{LC}q = 0$
##### c. The charge ($q$) decays exponentially, similar to amplitude in damped oscillations: $q \propto e^{-Rt/2L}$
### B. Parallel AC Circuits
#### Analysis Method
##### a. Voltage is common across parallel branches
##### b. Currents divide and must be added vectorially (phasors) or using Kirchhoff's Current Law (KCL) accounting for phase
## VIII. Transformers and Choke Coils
### A. Transformers
#### Working Principle
##### a. Operates on the principle of Mutual Induction
##### b. Works only with AC; DC input yields zero output because magnetic flux must change to induce EMF
#### Construction and Types
##### a. Consists of Primary ($N_p$) and Secondary ($N_s$) coils wound on a soft iron core
##### b. Step-Up: Increases voltage ($N_s > N_p$), decreases current
##### c. Step-Down: Decreases voltage ($N_s < N_p$), increases current
#### Transformation Ratio
##### a. $\frac{V_s}{V_p} = \frac{N_s}{N_p}$
##### b. For 100% efficiency (Ideal): $\frac{I_p}{I_s} = \frac{N_s}{N_p}$ (Inverse relation between voltage and current)
### B. Energy Losses in Transformers
#### Flux Leakage
##### a. Not all magnetic flux from the primary links to the secondary due to air gaps
#### Copper Loss (Joule Heating)
##### a. Heat dissipation due to resistance of the copper windings ($I^2R$)
##### b. Minimized by using thick wires for high current coils
#### Eddy Current Loss
##### a. Circulating currents induced in the bulk iron core generate heat
##### b. Minimized by using a laminated core (thin sheets) to break the current paths
#### Hysteresis Loss
##### a. Energy lost due to repeated magnetization and demagnetization of the core
##### b. Minimized by using soft iron cores with thin hysteresis loops
### C. Choke Coil
#### Function
##### a. Used to control current in an AC circuit without significant power loss
##### b. Ideally has high inductance and negligible resistance
#### Mechanism
##### a. It is essentially an R-L circuit where $X_L$ is large (limiting current) but $R$ is small (limiting power dissipation)
