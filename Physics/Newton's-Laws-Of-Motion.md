---
markmap:
  colorFreezeLevel: 3
---

# Newton's-Laws-Of-Motion

#### Here is an ultra-detailed, multi-level hierarchical outline of Newton's Laws of Motion, Friction, and Circular Motion based on the provided source transcript.
## I. Fundamentals of Force and Motion
### A. Definition and Nature of Force
#### Basic Definition
  - Force is defined as a push or a pull that has the capability to change the state of a body
#### Effects of Force
##### a. It can start a body that is at rest or stop a body that is in motion
##### b. It can change the direction of a moving body (e.g., turning a linear path)
#### Concept of State (Inertia)
##### a. Inertia of Rest: A body at rest desires to stay at rest unless acted upon
##### b. Inertia of Motion: A moving body tends to continue moving in its current state
##### c. Inertia of Direction: A body moving in a specific direction resists changes to that direction
### B. Linear Momentum ($p$)
#### Mathematical Definition
  - Momentum is the product of mass and velocity ($p = m \times v$)
#### Vector Nature
##### a. Velocity is a vector quantity, so momentum must be treated as a vector, often using $\hat{i}$ and $\hat{j}$ notation
##### b. Two bodies with the same mass and speed can have different momenta if their directions of travel differ
##### c. When calculating changes in momentum, direction must be accounted for (e.g., resolving components using $\sin\theta$ and $\cos\theta$)
## II. Newton’s Laws of Motion
### A. Newton’s First Law (Law of Inertia)
#### Statement
  - A body’s state will not change unless a net external, unbalanced force acts upon it
#### Implication
  - If a body is at rest, it remains at rest; if moving, it continues moving in the same direction
### B. Newton’s Second Law
#### Fundamental Formula
  - Net external force is equal to the rate of change of momentum ($F_{ext} = \frac{dp}{dt}$)
#### Derivation for Constant Mass
##### a. Force is strictly defined as $\frac{d(mv)}{dt}$
##### b. For systems with constant mass, this simplifies to $F = m \frac{dv}{dt}$ or $F = ma$
#### Graphical Interpretation
##### a. If momentum ($p$) is given as a function of time, Force is obtained by differentiating $p$ with respect to time
##### b. Force is the slope of the Momentum-Time ($p-t$) graph
### C. Newton’s Third Law
#### Statement
  - For every action, there is an equal and opposite reaction
#### Key Characteristics
##### a. Action and reaction forces always act on different bodies
##### b. Example: Hitting a wall with 10N results in the wall applying 10N back on the hand
## III. Impulse and Impulse-Momentum Theorem
### A. Concept of Impulse ($J$)
#### Definition
  - Impulse is defined as the change in momentum of a body
#### Calculation Methods
##### a. Finite Difference: $J = \Delta p = p_{final} - p_{initial}$
##### b. Integral Form: For variable forces, Impulse $J = \int_{t_1}^{t_2} F \, dt$
### B. Impulse-Momentum Theorem
#### Statement
  - The integral of force over time equals the change in momentum: $\int F \, dt = p_f - p_i$
#### Application (Area Under Curve)
##### a. The area under a Force-Time ($F-t$) graph represents the change in momentum (Impulse)
##### b. For geometric shapes (e.g., semicircles or ellipses in $F-t$ plots), the area formula (like $\frac{\pi ab}{2}$) yields the impulse directly
#### Directionality
##### a. If force acts parallel to motion, momentum increases (add the impulse area)
##### b. If force acts anti-parallel (opposite), momentum decreases (subtract the impulse area)
### C. Applications and Problem Types
#### Elastic Collisions
  - A ball hitting a wall elasticly rebounds with the same speed; the change in momentum is $2mv$ (final minus initial vector)
#### Flow of Particles
  - If $n$ balls hit a surface per second, the average force is the change in momentum per ball multiplied by $n$ ($F = 2nmv$)
## IV. Free Body Diagrams (FBD) and Forces
### A. Rules for Drawing FBDs
#### Body Isolation
  - Separate the body from its surroundings to analyze forces acting on it
#### Weight ($mg$)
  - Always acts vertically downwards towards the center of the Earth
### B. Contact Forces
#### Normal Reaction ($N$)
##### a. A "Push" force that acts perpendicular to the contact surface
##### b. It always pushes the body away from the surface
#### Tension ($T$)
##### a. A "Pull" force acting along a string/rope
##### b. It always acts away from the body (pulling it)
##### c. Constraints: In a massless, inextensible string, tension is uniform throughout
#### Spring Force ($F_s$)
##### a. Acts as a restoring force; direction opposes elongation or compression
##### b. Magnitude is given by Hooke's Law: $F = -kx$ (where $k$ is the spring constant)
### C. Pulley Systems
#### Ideal Pulley
  - Assumed to be massless and frictionless
#### Net Force
  - The net force on a massless pulley is always zero, even if it is accelerating ($F_{up} = F_{down}$)
## V. Equilibrium of Concurrent Forces
### A. Definition of Equilibrium
#### State
  - A body is in equilibrium if it is at rest or moving with constant velocity
#### Condition
  - The net external force on the body is zero ($\Sigma F = 0$)
### B. Problem-Solving Strategy
#### Resolution
  - Draw the FBD and resolve all forces along $X$ and $Y$ axes
#### Equation Setup
  - Set $\Sigma F_x = 0$ and $\Sigma F_y = 0$
#### Geometry Usage
  - Use geometric relations (like triangles for string lengths and radii) to find unknown angles
### C. Specific Equilibrium Cases
#### Lami’s Theorem/Sine Rule
  - Can be applied for three concurrent forces in equilibrium (implied in tension problems)
#### Weighing Machine Problems
  - A weighing machine measures the Normal Reaction ($N$), not the actual weight ($mg$)
#### Spring Balance
  - Measures the Tension ($T$) in the connection
## VI. Dynamics: Motion and Acceleration
### A. Newton’s Second Law Equations
#### Direction of Motion
  - Identify the direction of acceleration
#### Equation Formulation
  - "Driving Force" minus "Opposing Force" equals Mass times Acceleration ($F_{driving} - F_{opposing} = ma$)
### B. Connected Bodies
#### Internal Forces
  - When analyzing a whole system, internal forces (like tension between connected blocks) cancel out
#### System Acceleration
  - $a_{sys} = \frac{\text{Net External Driving Force}}{\text{Total Mass}}$
### C. Special Motion Cases
#### Rope with Mass
##### a. Tension varies along the length of a massive rope
##### b. To find tension at a midpoint, divide the rope into two blocks of mass $m/2$ and analyze
#### Motion on a Wedge
##### a. A block sliding down a smooth wedge has acceleration $a = g\sin\theta$ along the incline
##### b. Groove Constraint: If a block moves in a groove at an angle $\alpha$ on a wedge of angle $\theta$, the acceleration is the component of the wedge acceleration along the groove ($a = g\sin\theta \cos\alpha$)
#### Cutting Problems
##### a. Strings: Tension becomes zero immediately upon cutting
##### b. Springs: Spring force does not change instantaneously; it remains $kx$ just after the cut
##### c. Result: Analyze forces immediately after the cut to find instantaneous accelerations
## VII. Constraint Motion
### A. String Constraint
#### Principle
  - The length of an inextensible string remains constant
#### Velocity Relation
  - The component of velocity along the length of the string must be equal for connected points
#### Power Method
##### a. Since tension is an internal force, the net power delivered by tension is zero ($\Sigma \vec{T} \cdot \vec{v} = 0$)
##### b. This scalar equation ($T v \cos\theta$) often simplifies complex multi-pulley problems
### B. Wedge (Normal) Constraint
#### Principle
  - Rigid bodies in contact must maintain contact without penetrating or separating
#### Velocity Relation
  - Velocities of contact points along the common normal must be equal
#### Formula
  - $v_1 \sin\theta = v_2 \cos\theta$ (or similar based on geometry) prevents separation
## VIII. Friction
### A. Nature of Friction
#### Definition
  - A contact force that opposes relative slipping or the tendency of slipping between surfaces
#### Direction
  - Acts opposite to the relative motion (or impending motion) of the contact points, not necessarily opposite to the body's global motion
### B. Types of Friction
#### Static Friction ($f_s$)
##### a. Acts when there is no relative motion (tendency only)
##### b. Self-Adjusting: Its value ranges from $0$ to a maximum limiting value ($f_{s,max}$)
##### c. Limiting Friction: $f_{s,max} = \mu_s N$. This is the specific value required to start motion; below this, friction equals the applied force
#### Kinetic Friction ($f_k$)
##### a. Acts when there is relative slipping
##### b. Constant Value: $f_k = \mu_k N$. It does not adjust with applied force
### C. Angle of Repose
#### Definition
  - The angle of an inclined plane at which a block just begins to slide
#### Relation
  - At this angle, $mg\sin\theta = \mu mg\cos\theta$, leading to $\mu = \tan\theta$
### D. Two-Block Systems
#### Analysis Strategy
##### a. Calculate maximum static friction ($f_{max}$) for all rough surfaces
##### b. Assume the blocks move together with common acceleration and check if the required friction exceeds $f_{max}$
##### c. If required friction > limiting friction, slipping occurs; calculate accelerations separately using kinetic friction
## IX. Circular Motion Kinematics
### A. Angular Variables
#### Angular Displacement ($\theta$)
  - The angle traversed by the radius vector
#### Angular Velocity ($\omega$)
  - Rate of change of angular displacement ($\omega = d\theta/dt$)
#### Angular Acceleration ($\alpha$)
  - Rate of change of angular velocity ($\alpha = d\omega/dt$)
### B. Linear-Angular Relations
#### Velocity
  - $v = r\omega$ (scalar) or $\vec{v} = \vec{\omega} \times \vec{r}$ (vector)
#### Tangential Acceleration ($a_t$)
  - $a_t = r\alpha$ or $\vec{a}_t = \vec{\alpha} \times \vec{r}$. It is responsible for changing the speed
### C. Classification of Circular Motion
#### Uniform Circular Motion (UCM)
##### a. Speed ($v$) and $\omega$ are constant
##### b. $\alpha = 0$ and $a_t = 0$
##### c. Only Centripetal Acceleration exists
#### Non-Uniform Circular Motion
##### a. Speed changes (speeds up or slows down)
##### b. Both Tangential ($a_t$) and Centripetal ($a_c$) accelerations are present
##### c. Net acceleration is the vector sum: $a_{net} = \sqrt{a_t^2 + a_c^2}$
## X. Circular Motion Dynamics
### A. Centripetal Force/Acceleration ($a_c$)
#### Role
  - Responsible for changing the direction of velocity
#### Formula
  - $a_c = \frac{v^2}{r} = r\omega^2$
#### Direction
  - Always acts towards the center of the circular path
### B. Banking of Roads (Dynamics)
#### Mechanism
  - To prevent skidding at high speeds, tracks are banked (angled) so the Normal reaction contributes to centripetal force
#### Force Resolution
##### a. Resolve Normal ($N$) and Friction ($f$) along horizontal (radial) and vertical axes
##### b. Horizontal components provide $mv^2/r$; Vertical components balance $mg$
#### Velocity Formula
##### a. Max Speed (prevents outward skid): $v_{max} = \sqrt{rg \left(\frac{\mu + \tan\theta}{1 - \mu\tan\theta}\right)}$
##### b. Optimum Speed (no friction): $v_{opt} = \sqrt{rg \tan\theta}$
### C. Vertical Circular Motion Concepts
#### Resolution Rule
  - Resolve forces into Tangential (for speed change) and Normal (for direction change) components
#### Convex vs. Concave Bridges
##### a. At the top of a convex bridge, $mg - N = mv^2/r$, so Normal reaction is lower ($N < mg$)
##### b. At the bottom of a dip (concave), $N - mg = mv^2/r$, so Normal reaction is higher ($N > mg$)
  - XI. Non-Inertial Frames and Pseudo Force
### A. Concept of Pseudo Force
#### Definition
  - A fictitious force introduced to apply Newton's Laws from within an accelerating (non-inertial) frame
#### Formula
  - $\vec{F}{pseudo} = -m{body} \vec{a}_{frame}$
#### Direction
  - Always opposite to the acceleration of the observer/frame
### B. Applications
#### Elevator Problems
##### a. If an elevator accelerates upward ($a$), effective gravity increases ($g_{eff} = g + a$)
##### b. If accelerating downward, effective gravity decreases ($g_{eff} = g - a$)
#### Centrifugal Force
##### a. A specific pseudo force experienced in a rotating frame (which is accelerating towards the center)
##### b. Formula: $F_{centrifugal} = m \omega^2 r$ or $mv^2/r$, acting radially outward
#### Pendulum in Accelerating Car
##### a. The equilibrium angle $\theta$ is found where horizontal pseudo force balances tension component
##### b. $\tan\theta = a/g$
#### Accelerating Wedge
  - To prevent a block from sliding down a smooth wedge, the wedge must accelerate such that the pseudo force balances the gravity component: $a = g\tan\theta$