---
markmap:
  colorFreezeLevel: 3
---

# Gravitation

## I. Newton’s Law of Universal Gravitation and Basic Forces
### A. Fundamental Law for Point Masses
#### Force Formula and Definition
##### a.The force of attraction between two point masses $m_1$ and $m_2$ separated by a distance $r$ is proportional to the product of masses and inversely proportional to the square of the distance
##### b.The mathematical expression is $F = \frac{Gm_1m_2}{r^2}$, where $G$ is the Universal Gravitational Constant ($6.67 \times 10^{-11} \, \text{Nm}^2/\text{kg}^2$)
##### c.This formula is valid strictly for point masses; it describes an action-reaction pair where both masses exert equal and opposite forces on each other
#### Superposition Principle and System of Particles
##### a.For multiple masses (e.g., an equilateral triangle configuration), the net force on a specific mass is the vector sum of individual forces exerted by all other masses
##### b.In symmetrical setups (like a centroid mass in a triangle), forces may cancel out due to vector addition, leading to zero net force
##### c.Calculations often require breaking forces into components or using vector addition formulas like $\sqrt{F_1^2 + F_2^2 + 2F_1F_2 \cos \theta}$
#### Circular Motion under Mutual Attraction
##### a.If particles (e.g., 4 masses on a square) revolve under mutual attraction, the net gravitational force provides the necessary centripetal force
##### b.The net force is calculated by summing forces from adjacent and diagonal masses (e.g., $F_{net} = F\sqrt{2} + F/2$ for a square)
##### c.The angular velocity $\omega$ or speed $v$ is derived by equating $F_{net} = m\omega^2 r$ or $mv^2/r$, where $r$ is the radius of the circle (distance from center to mass)
### B. Force Calculation for Continuous Bodies
#### Rod and Point Mass System
##### a.To find the force between a rod of length $L$ and a point mass at distance $a$, one cannot simply use the center of mass distance
##### b.The correct method involves integrating small elements: selecting a small element $dx$ at distance $x$, where $dF = \frac{G(dm)m}{x^2}$
##### c.The linear mass density $\lambda = M/L$ is used to define $dm = \lambda dx$, and the integration runs from the near end ($a$) to the far end ($a+L$)
## II. Gravitational Field and Electrostatics Analogy
### A. The Electrostatics Analogy Strategy
#### Correspondence of Physical Quantities
##### a.Gravitation is taught by relating it to Electrostatics: Mass ($m$) replaces Charge ($q$), and Gravitational Constant ($G$) replaces Coulomb’s constant ($k$)
##### b.The constant $k = \frac{1}{4\pi\epsilon_0}$ in electrostatics corresponds to $G$; thus $\frac{1}{\epsilon_0}$ can be replaced by $4\pi G$ in derived formulas
##### c.Unlike charge, mass is always positive, meaning gravitational force is always attractive, and the field is always directed towards the mass
#### Field Definition
##### a.Gravitational field ($E_g$ or $I$) is defined as the force acting per unit mass placed at a point
##### b.Mathematically, $E_g = \lim_{m \to 0} \frac{F}{m}$, analogous to Electric Field $E = F/q$
##### c.For a point mass, the field is $E_g = \frac{GM}{r^2}$ directed towards the mass, similar to $E = \frac{kq}{r^2}$ for a point charge
### B. Fields of Continuous Geometries
#### Infinite Line Mass (Wire)
##### a.Analogous to the infinite line charge ($E = \frac{2k\lambda}{r}$), the gravitational field is $E_g = \frac{2G\lambda}{r}$, where $\lambda$ is mass per unit length
##### b.The field direction is perpendicular to the wire and towards it; for a semi-infinite or finite wire, components ($E_{\perp}, E_{\parallel}$) are calculated using angles $\theta_1$ and $\theta_2$
##### c.If a particle revolves around an infinite wire, its orbital velocity $v = \sqrt{2G\lambda}$ is independent of the orbital radius $r$
#### Ring and Disc
##### a.For a ring of mass $M$, the field on the axis is derived from the electric analog $E = \frac{kqx}{(r^2+x^2)^{3/2}}$, becoming $E_g = \frac{GMx}{(r^2+x^2)^{3/2}}$
##### b.The field is maximum at $x = R/\sqrt{2}$, consistent with electrostatic results
##### c.For a disc, the field formula uses the analogy of surface charge density $\sigma$; replacing $\frac{\sigma}{2\epsilon_0}$ with $2\pi G \sigma (1 - \cos\theta)$
#### Spherical Shells (Hollow Sphere)
##### a.Inside a hollow shell ($r < R$), the gravitational field is zero, similar to the electric field inside a charged conductor
##### b.On the surface, the field is maximum: $E_g = \frac{GM}{R^2}$
##### c.Outside the shell ($r > R$), the shell behaves as if the entire mass is concentrated at the center, yielding $E_g = \frac{GM}{r^2}$
#### Solid Sphere (Earth Model)
##### a.Outside the sphere ($r > R$), the field is $\frac{GM}{r^2}$, identical to a point mass
##### b.Inside the sphere ($r < R$), the field is directly proportional to distance $r$: $E_g = \frac{GMr}{R^3}$ (analogous to $\frac{kQr}{R^3}$ or $\frac{\rho r}{3\epsilon_0}$)
##### c.The field is zero at the center, increases linearly to the surface, and then decreases as $1/r^2$ outside, forming a specific graph profile
## III. Acceleration Due to Gravity ($g$) and its Variations
### A. Surface Gravity
#### Standard Value
##### a.On the surface of the Earth, acceleration due to gravity is $g_0 = \frac{GM}{R^2}$
##### b.The standard value is approximately $9.8 \, m/s^2$ or $\pi^2$
##### c.Calculations often assume Earth is a perfect sphere with uniform density unless specified otherwise
### B. Variation with Altitude (Height $h$)
#### General Formula
##### a.At a height $h$ above the surface, the gravity is $g' = \frac{GM}{(R+h)^2}$
##### b.This exact formula must be used when $h$ is large (comparable to Earth's radius $R$)
##### c.Using this formula involves calculating the ratio $(R/(R+h))^2$ relative to surface gravity
#### Approximation for Small Heights
##### a.If $h \ll R$, the binomial approximation is applied: $g' \approx g_0 (1 - \frac{2h}{R})$
##### b.This formula is valid for small heights (e.g., up to a few hundred km) and is used for percentage change calculations
##### c.For example, at a height of 32 km, the percentage decrease is approximately 1%
### C. Variation with Depth ($d$)
#### Depth Formula
##### a.At a depth $d$ below the surface, gravity is calculated as $g' = g_0 (1 - \frac{d}{R})$
##### b.This formula is exact and does not rely on the binomial approximation like the small-height formula
##### c.Gravity decreases linearly with depth, becoming zero at the Earth's center ($d=R$)
### D. Variation due to Rotation
#### Effect of Angular Velocity ($\omega$)
##### a.Earth's rotation introduces a centrifugal term that reduces the effective gravity, except at the poles
##### b.The formula at latitude $\theta$ is $g' = g - R\omega^2 \cos^2\theta$
##### c.Gravity is maximum at the poles ($\theta = 90^\circ$, correction is 0) and minimum at the equator ($\theta = 0^\circ$, correction is maximum)
## IV. Gravitational Potential and Potential Energy
### A. Gravitational Potential Energy ($U$)
#### Definition and Formula
##### a.Defined as the work done by an external agent to bring a system of masses from infinity to a separation $r$ without acceleration
##### b.For two masses, $U = -\frac{Gm_1m_2}{r}$; the negative sign indicates an attractive, bound system
##### c.This is derived by integrating the force over distance or by analogy to Electrostatics ($U = \frac{kq_1q_2}{r}$) with a sign change due to attractive mass
#### System of Multiple Masses
##### a.For a system of multiple particles (e.g., a triangle or square), the total potential energy is the sum of the potential energies of all unique pairs
##### b.For a square configuration of 4 masses, there are 4 side pairs and 2 diagonal pairs to sum: $4 \times (-\frac{GM^2}{L}) + 2 \times (-\frac{GM^2}{L\sqrt{2}})$
##### c.Self-Energy (Energy to assemble a continuous body) for a solid sphere is given by $U_{self} = -\frac{3}{5}\frac{GM^2}{R}$
### B. Gravitational Potential ($V$)
#### Concept and Point Mass
##### a.Potential is the potential energy per unit mass ($V = U/m$) or work done to bring a unit mass from infinity
##### b.For a point mass, $V = -\frac{GM}{r}$; it is a scalar quantity
##### c.Potential is always negative for gravitational systems involving finite masses
#### Potential of Spheres
##### a.Hollow Sphere: Potential is constant everywhere inside and equal to the surface potential ($-\frac{GM}{R}$); outside it is $-\frac{GM}{r}$
##### b.Solid Sphere (Inside): The potential inside is governed by the "Chudail" (witch) formula: $V_{in} = -\frac{GM}{2R^3}(3R^2 - r^2)$
##### c.Solid Sphere (Center): At the center ($r=0$), the potential is $-\frac{3}{2}\frac{GM}{R}$, which is 1.5 times the surface potential
## V. Motion in Gravitational Field
### A. Tunnel Problems (The "Thanos" Scenario)
#### Oscillation inside Earth
##### a.If a tunnel is dug through Earth (along diameter or chord) and a mass is dropped, it performs Simple Harmonic Motion (SHM)
##### b.The restoring force is proportional to distance from the center ($F \propto r$), similar to a spring
##### c.The time period of this oscillation is $T = 2\pi\sqrt{\frac{R}{g}}$, which is approximately 84 minutes
#### Velocity Calculation
##### a.To find velocity at the center or any point in the tunnel, Conservation of Mechanical Energy (COME) is used
##### b.Equation: $KE_i + PE_i = KE_f + PE_f$, utilizing the solid sphere potential formula for internal points
##### c.Velocity is maximum at the center of the Earth
### B. Projectile Motion and Escape
#### Escape Velocity ($v_e$)
##### a.The minimum velocity required to project a body from the surface so it escapes the gravitational field (reaches infinity with zero energy)
##### b.Derived by equating Surface Energy to Zero: $\frac{1}{2}mv_e^2 - \frac{GMm}{R} = 0$, yielding $v_e = \sqrt{\frac{2GM}{R}}$
##### c.For Earth, $v_e \approx 11.2 \, \text{km/s}$; it is independent of the mass of the projectile
#### Oblique Projection and Maximum Height
##### a.For particles projected at an angle or from a height, two conservation laws are used: Conservation of Energy and Conservation of Angular Momentum (about the center of Earth)
##### b.Conservation of Angular Momentum ($m v_1 r_1 \sin\theta_1 = m v_2 r_2 \sin\theta_2$) is necessary because gravity is a central force (torque is zero)
##### c.These combined equations allow solving for maximum height or velocity at specific points in the trajectory
## VI. Satellite Motion
### A. Orbital Dynamics
#### Orbital Velocity ($v_o$)
##### a.A satellite revolves because gravitational force provides the centripetal force: $\frac{GMm}{r^2} = \frac{mv_o^2}{r}$
##### b.The orbital speed is $v_o = \sqrt{\frac{GM}{r}}$, where $r$ is the distance from the center of Earth
##### c.Velocity is independent of the satellite's mass but depends on the orbital radius
#### Time Period ($T$)
##### a.Derived from $T = \frac{2\pi r}{v_o}$, resulting in $T = 2\pi \sqrt{\frac{r^3}{GM}}$
##### b.This confirms Kepler's Third Law: $T^2 \propto r^3$
##### c.For a satellite grazing the surface ($r \approx R$), $T \approx 84$ minutes ($2\pi\sqrt{R/g}$)
#### Satellite Energy Profile
##### a.Kinetic Energy (KE): $+\frac{GMm}{2r}$ (always positive)
##### b.Potential Energy (PE): $-\frac{GMm}{r}$ (negative)
##### c.Total Energy (TE): $-\frac{GMm}{2r}$ (negative, indicating a bound state)
##### d.Relationship: $|TE| = |KE| = \frac{1}{2}|PE|$
### B. Geostationary Satellites
#### Characteristics
##### a.A satellite that appears stationary relative to an observer on Earth
##### b.It must have the same time period as Earth's rotation (24 hours) and rotate in the equatorial plane
##### c.The orbital radius is approx 42,000 km, placing it at a height of ~36,000 km above the surface
## VII. Kepler’s Laws and Binary Systems
### A. Kepler's Laws of Planetary Motion
#### First Law (Law of Orbits)
##### a.All planets move in elliptical orbits with the Sun at one of the foci
#### Second Law (Law of Areas)
##### a.The line joining the planet to the Sun sweeps equal areas in equal intervals of time ($\frac{dA}{dt} = \text{constant}$)
##### b.This implies areal velocity is constant, which is a consequence of Conservation of Angular Momentum ($L$)
##### c.Speed is maximum at Perihelion (closest approach) and minimum at Aphelion (farthest point)
#### Third Law (Law of Periods)
##### a.The square of the time period is proportional to the cube of the semi-major axis: $T^2 \propto a^3$
##### b.For circular orbits, this simplifies to $T^2 \propto r^3$
### B. Binary Star Systems
#### Double Star Dynamics
##### a.Two stars of masses $m_1$ and $m_2$ rotate about their common center of mass due to mutual attraction
##### b.They share the same angular velocity $\omega$ and time period, but have different orbital radii $r_1$ and $r_2$ relative to the center of mass
#### Time Period Formula
##### a.The centripetal force on each is provided by their mutual gravity: $F = \frac{G m_1 m_2}{(r_1+r_2)^2}$
##### b.The combined time period formula is $T = 2\pi \sqrt{\frac{(r_1+r_2)^3}{G(m_1+m_2)}}$, where $(r_1+r_2)$ is the separation distance
##### c.This generalizes the standard Kepler law (where one mass is assumed stationary/massive) to a two-body system