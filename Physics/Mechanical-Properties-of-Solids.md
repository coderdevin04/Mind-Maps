---
markmap:
  colorFreezeLevel: 3
---

# Mechanical-Properties-of-Solids

## I. Introduction to Rigid and Real Bodies
### A. Concept of a Perfectly Rigid Body
#### Definition of Rigidity
##### a. A body is perfectly rigid if the separation between any two particles remains constant regardless of the external force applied
##### b. Ideally, the shape, size, and dimensions remain fixed
#### Reality of Rigidity
##### a. In the real world, no perfectly rigid body exists; all bodies deform to some extent under force
##### b. Rigid body dynamics is an idealization used in rotation mechanics to simplify particle motion
### B. Concept of Elastic Bodies
#### Definition of Elasticity
##### a. Elasticity is not about the ease of deformation, but the tendency of a material to regain its original configuration after the removal of deforming forces
##### b. It involves getting back to the original structure (length, shape, volume)
#### Comparison of Materials
##### a. Steel is considered more elastic than rubber because it has a higher tendency to regain its shape and requires more force to deform, contradicting common intuition regarding flexibility
## II. Mechanism of Deformation: Stress and Strain
### A. The Cause-Effect Relationship
#### Sequence of Events
##### a. When an external (deforming) force is applied, the configuration (shape/bond length) changes first
##### b. This change in configuration is defined as Strain
##### c. The deformation causes an internal restoring force to develop within the material to resist change
##### d. This internal restoring force leads to Stress
#### Correct Statement of Causality
##### a. Strain is the fundamental cause that leads to Stress ($Strain \rightarrow Stress$)
### B. Stress
#### Definition and Formula
##### a. Stress is defined as the internal restoring force developed per unit area ($F_{restoring}/Area$)
##### b. At equilibrium, the restoring force equals the external applied force, allowing calculation via $F_{ext}/A$
#### Physical Properties
##### a. Unit: Newton per meter square ($N/m^2$) or Pascal ($Pa$)
##### b. Dimensions: $ML^{-1}T^{-2}$
##### c. Nature: It is a tensor of rank 2, though often treated as a scalar in basic physics contexts; unlike pressure, stress can be tangential
### C. Types of Stress
#### Normal Stress
##### a. Occurs when the force acts perpendicular to the surface
##### b. Includes Longitudinal Stress (Tensile or Compressive) and Volumetric Stress
#### Shear (Tangential) Stress
##### a. Occurs when the force acts tangentially to the surface, tending to change the shape
##### b. Formula involves the tangential component of force divided by the area
### D. Strain
#### Definition
##### a. Strain is the ratio of change in configuration to the original configuration
##### b. It represents the extent of deformation
#### Physical Properties
##### a. It is a unitless and dimensionless quantity as it is a ratio
#### Types of Strain
##### a. Longitudinal Strain: Ratio of change in length to original length ($\Delta L / L_0$)
##### b. Volumetric Strain: Ratio of change in volume to original volume ($\Delta V / V$)
##### c. Shear Strain: The angle ($\theta$) by which a body bends or distorts, calculated as arc length divided by radius/length ($x/L$)
## III. Hooke’s Law and Stress-Strain Curve
### A. Experimental Setup
#### Methodology
##### a. A wire is suspended with a scale and weights are added to apply force
##### b. Measurements include radius (via Vernier caliper/Screw gauge), original length, and extension for various loads
### B. The Stress-Strain Graph
#### Region 1
  - Proportional Limit (Hooke’s Region)
##### a. From the origin to point A, the graph is linear
##### b. Stress is directly proportional to Strain ($Stress \propto Strain$)
##### c. This linear behavior defines Hooke's Law
#### Region 2
  - Elastic Limit (Yield Point)
##### a. Between the proportional limit and point B, the graph is curved but still elastic
##### b. If the load is removed in this region, the body regains 100% of its original shape
##### c. Point B is called the Yield Point
#### Region 3
  - Plastic Region
##### a. Beyond point B, if the load is removed, the body does not return to its original configuration
##### b. A "Permanent Set" (permanent deformation) remains even when Stress is zero
#### Region 4
  - Ultimate Stress and Fracture
##### a. The maximum stress the material can withstand is the Ultimate Stress (Tensile Strength)
##### b. The point where the material breaks is the Fracture Point
### C. Material Behavior Based on Graph
#### Ductile vs. Brittle
##### a. Ductile/Malleable: Large gap between the Ultimate Stress point and Fracture point (large "necking" region), allowing the material to be drawn into wires
##### b. Brittle: Small gap between Ultimate Stress and Fracture point; material breaks shortly after reaching maximum strength (e.g., glass)
#### Elasticity Comparison
##### a. The slope of the Stress vs. Strain graph represents the Modulus of Elasticity
##### b. A steeper slope indicates higher elasticity (e.g., Slope of 2 > Slope of 1 implies Material 2 is more elastic)
## IV. Moduli of Elasticity
### A. Young’s Modulus ($Y$)
#### Definition
##### a. Ratio of Longitudinal Stress to Longitudinal Strain
#### Formula
##### a. $Y = \frac{F/A}{\Delta L/L} = \frac{FL}{A\Delta L}$
### B. Bulk Modulus ($B$)
#### Definition
##### a. Ratio of Volumetric Stress to Volumetric Strain
#### Formula
##### a. $B = -\frac{P}{\Delta V/V}$ or $-\frac{PV}{\Delta V}$
##### b. The negative sign is often added for compression (where $\Delta V$ is negative) to keep the modulus positive, but is not needed for expansion
#### Compressibility ($k$)
##### a. Defined as the reciprocal of Bulk Modulus ($k = 1/B$)
### C. Shear Modulus ($G$ or $\eta$)
#### Definition
##### a. Ratio of Shear Stress to Shear Strain
#### Formula
##### a. $G = \frac{F/A}{\theta} = \frac{F}{A\theta}$
### D. Poisson’s Ratio ($\sigma$)
#### Concept
##### a. When a body is elongated longitudinally, it compresses laterally (radius decreases)
#### Formula
##### a. Ratio of Lateral Strain to Longitudinal Strain
##### b. $\sigma = -\frac{\Delta r/r}{\Delta L/L}$
##### c. The negative sign ensures the ratio is positive, as one strain is usually negative while the other is positive
## V. Applications and Derived Concepts
### A. Spring Analogy for Rods
#### Equivalent Spring Constant
##### a. A rod under tension behaves like a spring with restoring force $F = (YA/L)\Delta L$
##### b. The equivalent spring constant is $k = \frac{YA}{L}$
#### Combination of Rods
##### a. Parallel: If rods share the load and extension is same or constrained, $k_{eq} = k_1 + k_2$
##### b. Series: If rods are connected end-to-end (load is same), $1/k_{eq} = 1/k_1 + 1/k_2$
#### Time Period of Oscillation
##### a. For a mass attached to a rod: $T = 2\pi\sqrt{\frac{m}{k_{eq}}} = 2\pi\sqrt{\frac{mL}{YA}}$
### B. Energy Density
#### Definition
##### a. Potential energy stored per unit volume in a stretched wire
#### Formulas
##### a. $u = \frac{1}{2} \times \text{Stress} \times \text{Strain}$
##### b. $u = \frac{1}{2} Y (\text{Strain})^2$
##### c. $u = \frac{\text{(Stress)}^2}{2Y}$
## VI. Analysis of Elongation in Rods
### A. Elongation due to External Force
#### Massless Rod
##### a. Direct formula: $\Delta L = \frac{FL}{AY}$
#### Varying Force or Tension
##### a. If force varies along the rod (e.g., due to acceleration or distributed mass), use integration: $\Delta L = \int \frac{T(x)dx}{AY}$
##### b. Alternatively, use the Average Force method: $\Delta L = \frac{F_{avg}L}{AY}$, where $F_{avg}$ is the average of forces at the two ends
### B. Elongation due to Self-Weight
#### Setup
##### a. A rod of mass $M$ and length $L$ hanging vertically
#### Calculation
##### a. Tension varies with height ($T(x) = \frac{M}{L}xg$)
##### b. Total elongation is derived as $\Delta L = \frac{MgL}{2AY}$
##### c. This is equivalent to applying the force at the center of mass or taking the average force ($Mg/2$)
### C. Elongation in Rotating Rods
#### Scenario
##### a. A rod or wire rotating in a horizontal plane (e.g., space station)
#### Stress Calculation
##### a. Tension is provided by centripetal force ($T = m\omega^2 r$)
##### b. Breaking condition: Stress = Breaking Stress when $\frac{T}{A} = \sigma_{breaking}$
### D. Stress on an Oblique Section
#### Resolution of Forces
##### a. On a plane cut at an angle $\theta$, the applied force $F$ has components
##### b. Normal force component: $F \cos\theta$
##### c. Tangential force component: $F \sin\theta$
#### Area Correction
##### a. The area of the oblique section is $A' = A / \cos\theta$
#### Stress Formulas
##### a. Normal Stress: $\sigma_n = \frac{F \cos^2\theta}{A}$
##### b. Shear Stress: $\sigma_t = \frac{F \sin\theta \cos\theta}{A}$