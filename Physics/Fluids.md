---
markmap:
  colorFreezeLevel: 3
---

# Solids-Fluids

## I. Fluid Statics
### A. Fundamental Concepts of Fluids
#### 1. Nature of Fluids
##### a. Fluids are materials that possess the property to flow, encompassing both liquids and gases
##### b. Liquids maintain a fixed size (volume) but have no fixed shape, adapting to the container
##### c. Ideal liquids are considered incompressible and non-viscous during standard analysis
#### 2. Thrust and Pressure
##### a. Thrust is the perpendicular force exerted by a liquid on the walls of its container due to molecular collisions
##### b. Pressure is defined as the thrust exerted per unit area ($P = F/A$)
##### c. Pressure is a scalar quantity with the SI unit of Pascal (N/m²)
#### 3. Density and Specific Gravity
##### a. Density ($\rho$) is the ratio of mass to volume; the density of water is $1000 \text{ kg/m}^3$ or $1 \text{ g/cm}^3$
##### b. Relative density is the ratio of a material's density to the density of a reference substance, typically water
##### c. Specific gravity is the relative density with respect to water at $4^\circ\text{C}$
### B. Pressure Distribution and Variation
#### 1. Variation with Depth
##### a. In a static fluid, pressure increases linearly with depth: $P = P_0 + \rho gh$
##### b. Absolute pressure is the total pressure at a point, while gauge pressure ($\rho gh$) is the pressure relative to atmospheric pressure
##### c. According to the hydrostatic paradox, pressure at the same horizontal level in a continuous, stationary liquid is identical regardless of the container's shape
#### 2. Pressure in Accelerating and Rotating Frames
##### a. In a vertically accelerating lift, the effective gravity becomes $g \pm a$, altering the pressure gradient to $\rho(g \pm a)h$
##### b. For a container with horizontal acceleration $a$, the liquid surface tilts at an angle $\theta$, where $\tan \theta = a/g$
##### c. In a rotating container, pressure increases with distance from the axis, and the surface takes a parabolic shape defined by $y = \omega^2x^2/2g$
#### 3. Measurement Devices
##### a. A barometer measures atmospheric pressure by balancing it against a column of liquid, usually mercury
##### b. A manometer is used to measure the pressure of a gas inside a bulb relative to atmospheric pressure
##### c. Atmospheric pressure ($1\text{ atm}$) is approximately $10^5 \text{ Pa}$, equivalent to a $76\text{ cm}$ mercury column
### C. Pascal's Law and Archimedes' Principle
#### 1. Pascal's Law Applications
##### a. Pressure applied to an enclosed incompressible fluid is transmitted undiminished to every portion of the fluid
##### b. Hydraulic lifts use this principle to multiply force by applying a small force over a small area to generate a large force over a larger area
##### c. This law also governs the operation of hydraulic brakes and jacks
#### 2. Archimedes' Principlea. Any object submerged in a fluid experiences an upward buoyant force (upthrust) equal to the weight of the fluid displaced
##### b. The buoyant force is calculated as $F_B = \rho_{\text{fluid}} V_{\text{displaced}} g$
##### c. The centre of buoyancy is the point of application for this force, located at the geometric centre of the displaced volume
#### 3. Principles of Flotation
##### a. An object sinks if its density is greater than the fluid's density and floats if it is less
##### b. For a floating body, the fraction of the volume submerged is the ratio of the object's density to the fluid's density ($\sigma/\rho$)
##### c. Apparent weight is the weight measured in a fluid, equal to the actual weight minus the buoyant force
## II. Fluid Dynamics
### A. Fluid Flow Characteristics
#### 1. Flow Classifications
##### a. Streamline (laminar) flow is steady and smooth, where every particle following a path behaves exactly like the preceding particle
##### b. Turbulent flow is irregular, chaotic, and involves significant energy losses
##### c. The transition from laminar to turbulent flow is determined by the Reynolds number
#### 2. Flow Measurement and Rates
##### a. Volume flow rate ($Q$) is the volume of liquid passing through a cross-section per unit time, given by $Q = Av$
##### b. Mass flow rate is the mass passing per unit time, calculated as $\rho Av$
##### c. Typical units for flow rate include $\text{m}^3/\text{s}$ or litres per minute
#### 3. Equation of Continuity
##### a. Based on the conservation of mass, the mass entering a pipe must equal the mass leaving it during steady flow
##### b. For incompressible fluids, $A_1v_1 = A_2v_2$, meaning velocity is inversely proportional to the cross-sectional area
##### c. In cases of variable density (e.g., mixing hot and cold water), the full form $\rho_1A_1v_1 = \rho_2A_2v_2$ must be used
### B. Energy in Fluid Systems (Bernoulli's Theorem)
#### 1. Bernoulli’s Equation Components
##### a. Pressure energy per unit volume is represented by the pressure $P$
##### b. Kinetic energy per unit volume is $\frac{1}{2}\rho v^2$ 
##### c. Potential energy per unit volume is $\rho gh$
#### 2. Energy Conservation Principle
##### a. For an ideal fluid in steady, non-viscous flow, the sum $P + \frac{1}{2}\rho v^2 + \rho gh$ is constant along a streamline
##### b. In a horizontal pipe where $\rho gh$ is constant, an increase in fluid velocity leads to a decrease in pressure
##### c. Bernoulli's theorem fails for turbulent flow due to energy dissipation
#### 3. Dynamic Lift and Applications
##### a. The lift on an aeroplane wing occurs because air moves faster over the curved top surface, creating lower pressure than beneath the wing
##### b. The Magnus effect explains the curved path of a spinning ball due to pressure differences between its sides
##### c. Venturi meters and Pitot tubes utilize pressure differences to measure fluid flow speed
### C. Efflux and Discharge
#### 1. Torricelli’s Law
##### a. The speed of efflux $v$ from a small hole at a depth $h$ below the free surface is $v = \sqrt{2gh}$
##### b. If the hole area is comparable to the tank area, the speed is modified by the factor $\sqrt{1/(1 - a^2/A^2)}$
##### c. This law is effectively a direct application of Bernoulli’s energy conservation
#### 2. Range and Emptying Time
##### a. The horizontal range of the fluid jet is maximised when the hole is placed at half the height of the liquid column ($h = H/2$)
##### b. Holes at depths $h$ and $H-h$ from the top surface will produce the same horizontal range
##### c. The time required to completely empty a tank of height $H$ through a small hole of area $a$ is $(A/a) \sqrt{2H/g}$
#### 3. Thrust Force
##### a. A tank experiences a recoil (thrust) force due to the ejection of fluid, calculated as $F = \rho av^2 = 2\rho agh$
##### b. This is an application of Newton's second law for systems with variable mass
##### c. This thrust can cause pipes or containers to move if not properly secured
## III. Viscosity and Surface Tension
### A. Viscosity
#### 1. Newton’s Law of Viscosity
##### a. Viscosity is the internal friction between layers of a fluid in relative motion
##### b. The viscous force is $F = \eta A (dv/dy)$, where $\eta$ is the coefficient of viscosity
##### c. Viscosity in liquids decreases with increasing temperature, whereas it increases in gases
#### 2. Stokes' Law and Terminal Velocity
##### a. Stokes' law states the viscous drag on a sphere of radius $r$ moving at speed $v$ is $6\pi\eta rv$
##### b. Terminal velocity is the constant speed achieved when the gravitational force is balanced by the sum of buoyancy and viscous drag
##### c. Terminal velocity is given by $v_t = \frac{2r^2g(\sigma - \rho)}{9\eta}$
#### 3. Flow Regimes and Reynolds Number
##### a. The transition from laminar to turbulent flow is predicted by the Reynolds number $R_e = \rho vd/\eta$
##### b. Flow is typically laminar if $R_e < 1000$ and turbulent if $R_e > 2000$
##### c. The region between $1000$ and $2000$ is considered an unstable buffer zone
### B. Surface Tension
#### 1. Molecular Basis and Force
##### a. Surface tension ($T$ or $S$) arises because surface molecules have fewer neighbouring bonds than interior molecules, resulting in extra energy
##### b. The surface acts like a stretched elastic membrane tending to minimise its surface area
##### c. The force of surface tension is defined as force per unit length ($T = F/L$)
#### 2. Surface Energy
##### a. Work must be done to increase the surface area of a liquid, stored as surface energy ($U = T \Delta A$)
##### b. When small droplets merge into a larger one, surface area decreases, and energy is released
##### c. Breaking a large drop into smaller ones requires energy input to create the new surface area
#### 3. Excess Pressure and Capillarity
##### a. Pressure on the concave side of a curved surface is always higher than on the convex side
##### b. Excess pressure is $2T/R$ for a liquid drop and $4T/R$ for a soap bubble (due to two surfaces)
##### c. Capillary rise occurs when a narrow tube is dipped in a liquid, with the height given by $h = \frac{2T \cos \theta}{\rho gr}$
## IV. Mechanical Properties of Solids (Elasticity)
### A. Stress and Strain Fundamentals
#### 1. Definitions
##### a. Elasticity is the property by which a body regains its original shape and size after the removal of deforming forces
##### b. Stress is the restoring force per unit area developed within the body
##### c. Strain is the fractional change in the dimensions of the body (length, volume, or shape)
#### 2. Hooke’s Law
##### a. Within the proportional limit, stress is directly proportional to strain
##### b. The ratio of stress to strain is called the Modulus of Elasticity
##### c. Brittle materials have a small plastic region, whereas ductile materials have a large plastic region before fracture
#### 3. The Stress-Strain Curve
##### a. The proportional limit (A) is the point where the linear relationship ends
##### b. The yield point (B) marks the elastic limit beyond which permanent deformation (permanent set) occurs
##### c. The fracture point (D) is where the material eventually breaks under excessive stress
### B. Elastic Moduli
#### 1. Young’s Modulus ($Y$)
##### a. Relates longitudinal stress to longitudinal strain in solids like wires and rods
##### b. A rod under tension can be treated as a spring with a spring constant $k = YA/L$
##### c. The elastic potential energy stored in a stretched wire is $\frac{1}{2} k \Delta L^2$ or $\frac{1}{2} \times \text{stress} \times \text{strain} \times \text{volume}$
#### 2. Bulk Modulus ($B$)
##### a. Relates volume stress (pressure change) to volume strain
##### b. Compressibility is defined as the reciprocal of the bulk modulus ($1/B$)
##### c. Pressure increase $dP$ causes a volume decrease $dV$, governed by $B = -dP / (dV/V)$
#### 3. Shear Modulus ($\eta$)
##### a. Relates shear stress to shear strain, measuring resistance to change in shape 185, 186.
##### b. Shear strain is typically expressed as the angle of deformation $\phi$
##### c. This modulus describes the sliding of parallel layers of a solid block
