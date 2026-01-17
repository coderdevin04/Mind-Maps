---
markmap:
  colorFreezeLevel: 3
---

# Kinematics1d

#### Here is an ultra-detailed, multi-level hierarchical outline of Motion in a Straight Line based on the provided sources.
## I. FUNDAMENTAL CONCEPTS OF MOTION
### A. Rest and Motion Definitions
#### Rest
##### a. Defined as when a particle's position does not vary with respect to time and the observer
##### b. Represented mathematically as $x =$ constant (e.g., $x=3$ or $x=-10$)
#### Motion
##### a. Defined as when a position varies with respect to time and the observer
##### b. Represented mathematically as $x$ being a function of time (e.g., $x = 3t^2 + t + 4$)
#### Relativity of Rest and Motion
##### a. Both rest and motion are relative terms dependent on the observer's frame of reference
##### b. An object can be at rest relative to one observer (e.g., a passenger inside a car) while in motion relative to another (e.g., someone outside looking at the car)
##### c. Even the Earth, which appears at rest to us, is in motion relative to the Sun
### B. Distance
#### Definition and Nature
##### a. It is the total path traveled by the body
##### b. It is a scalar quantity, has magnitude but no specific direction, and requires summing the total path length
#### Properties
##### a. Distance can never be negative; it is either zero (if the body never moves) or positive
##### b. Distance never decreases with time; it either remains constant (if stopped) or increases
### C. Displacement
#### Definition and Nature
##### a. It is the shortest path from the initial point to the final point
##### b. It is a vector quantity, possessing both magnitude and direction
##### c. Defined mathematically as the change in position ($\Delta x$)
#### Properties
##### a. Can be positive, negative, or zero
##### b. A negative sign indicates direction (e.g., moving in the negative x-direction)
##### c. Magnitude can increase or decrease (e.g., returning to the starting point decreases displacement magnitude to zero)
### D. Calculation Examples
#### Circular Motion
##### a. Distance on a full circle is $2\pi r$; displacement is $0$
##### b. Distance on an arc is $r \cdot \theta$; displacement magnitude is $2r \sin(\theta/2)$
#### Geometric Paths
##### a. For a path involving perpendicular turns (e.g., North then East), displacement is found using the Pythagorean theorem
##### b. "Vertically up" refers to the axis perpendicular to the North-South-East-West plane
## II. SPEED AND VELOCITY
### A. Speed
#### Instantaneous Speed
##### a. Defined as the rate of change of distance with respect to time
##### b. It is the magnitude of instantaneous velocity
##### c. Can increase or decrease continuously
#### Average Speed
##### a. Defined as Total Distance divided by Total Time
##### b. Unlike instantaneous speed, average speed for a moving body never decreases because total distance cannot decrease
##### c. Formula for equal time intervals ($t_1=t_2$): $v_{avg} = (v_1 + v_2)/2$
##### d. Formula for equal distance intervals ($x_1=x_2$): $v_{avg} = (2v_1v_2) / (v_1 + v_2)$
### B. Velocity
#### Instantaneous Velocity
##### a. Defined as the rate of change of position or displacement with respect to time
##### b. Mathematically expressed as $v = dx/dt$ (differentiation of position)
##### c. Can be positive, negative, or zero, where the sign indicates direction
#### Average Velocity
##### a. Defined as Total Displacement divided by Total Time
##### b. Can be zero if the particle returns to its starting point
### C. Mathematical Analysis of Velocity
#### Differentiation ($x \to v$)
##### a. If $x$ is a function of time (e.g., $t^2 - 6t + 4$), differentiate to find velocity ($v = 2t - 6$)
##### b. To find turning points (where direction changes), set $v = 0$
#### Integration ($v \to x$)
##### a. If velocity is given as a function of time, integrate $\int v \, dt$ to find displacement
##### b. Requires limits of integration (initial to final time) to find specific displacement
## III. ACCELERATION
### A. Definition and Nature
#### Basics
##### a. Rate of change of velocity with respect to time
##### b. Vector quantity; implies speeding up or slowing down (retardation)
#### Calculus Formulas
##### a. Time-dependent: $a = dv/dt$ (differentiating velocity with respect to time)
##### b. Position-dependent: $a = v \cdot (dv/dx)$ (chain rule application for functions of $x$)
### B. Types of Acceleration
#### Average Acceleration
##### a. Defined as Change in Velocity divided by Time Interval ($\Delta v / \Delta t$)
##### b. Requires vector subtraction ($v_{final} - v_{initial}$), paying attention to direction
#### Instantaneous Acceleration
##### a. Acceleration at a specific moment in time, found via differentiation
##### b. Can be zero even if velocity is not zero (e.g., constant maximum velocity)
### C. Specific Scenarios
#### Circular Motion (Uniform Speed)
##### a. Even with constant speed, direction changes, so velocity changes
##### b. Average acceleration requires vector subtraction: $|\vec{v}_f - \vec{v}_i| / t$
##### c. Change in velocity magnitude for angle $\theta$: $2v \sin(\theta/2)$
## IV. GRAPHICAL ANALYSIS
### A. Interpretation Principles
#### Slope (Differentiation)
##### a. Slope of Position-Time ($x-t$) graph = Velocity
##### b. Slope of Velocity-Time ($v-t$) graph = Acceleration
##### c. Positive slope implies positive quantity; negative slope implies negative quantity
#### Area (Integration)
##### a. Area under Acceleration-Time ($a-t$) graph = Change in Velocity
##### b. Area under Velocity-Time ($v-t$) graph = Displacement (Change in Position)
##### c. For Distance from $v-t$ graph: Sum of absolute values of areas (upper + lower)
##### d. For Displacement from $v-t$ graph: Upper area minus lower area
### B. Reading Specific Graphs
  - $v-t$ Graphs
##### a. To find acceleration at a point: Calculate $\tan(\theta)$ (slope) at that time
##### b. To find average speed: Calculate total area (distance) divided by total time
  - $v-x$ Graphs (Phase Space)
##### a. To find acceleration from $v$ vs $x$: Use $a = v \cdot \text{slope}$ ($a = v \cdot dv/dx$)
##### b. Acceleration is the product of the velocity coordinate and the slope of the graph at that point
#### Prohibited Graphs
##### a. Graphs showing two velocities or two positions at the same time are impossible (vertical lines)
##### b. Distance-time graphs can never decrease (slope cannot be negative)
##### c. Speed-time graphs cannot be negative
##### d. Note: A particle can have two velocities at the same position (e.g., passing a point, going and coming back), so loops in $v-x$ are possible
### C. Graph Conversion
  - $a-t$ from $v-t$
##### a. If $v-t$ slope is constant positive $\to$ $a$ is constant positive
##### b. If $v-t$ slope is zero $\to$ $a$ is zero
  - $x-t$ from $v-t$
##### a. If $v$ is increasing linearly $\to$ $x-t$ is parabolic with increasing slope
##### b. If $v$ is constant $\to$ $x-t$ is linear
##### c. If $v$ is negative and magnitude increasing $\to$ $x-t$ slope is negative and steepening
## V. KINEMATIC EQUATIONS (CONSTANT ACCELERATION)
### A. The Equations
#### Vector Equations
##### a. $v = u + at$ (Velocity-Time relation)
##### b. $s = ut + \frac{1}{2}at^2$ (Displacement-Time relation)
#### Note
  - $s$ stands for Displacement, not Distance. It requires vector signs
#### Scalar/Dot Product Equation
##### a. $v^2 - u^2 = 2as$ (Velocity-Displacement relation)
##### b. Derived from dot product, where angle between $a$ and $s$ matters ($\cos \theta$)
#### Displacement in $n^{th}$ Second
##### a. Formula: $s_n = u + \frac{a}{2}(2n - 1)$
##### b. This formula is dimensionally correct despite appearance (implied time factor of 1 second)
### B. Application and Sign Convention
#### Directionality
##### a. Positive and negative signs indicate direction (e.g., right/up is $+$, left/down is $-$)
##### b. Acceleration and velocity in opposite directions cause retardation (slowing down)
#### Common Pitfalls
##### a. Using distance instead of displacement in $s = ut + \frac{1}{2}at^2$ when a body reverses direction (leads to wrong answers)
##### b. Assuming retardation always means negative acceleration; it actually means acceleration opposite to velocity
## VI. MOTION UNDER GRAVITY
### A. Characteristics
#### Constant Acceleration
##### a. Gravity acts as a constant acceleration ($g \approx 9.8 \, m/s^2$) downwards
##### b. Sign is always negative ($-g$) if upward direction is positive, regardless of whether the body is moving up or down
#### Air Resistance
##### a. Generally neglected unless specified
##### b. If included (e.g., Drag force $\propto v^2$), acceleration becomes variable, requiring integration rather than standard kinematic equations
### B. Vertical Projection (Thrown Upward)
#### Top Point
##### a. Velocity becomes zero momentarily
##### b. Acceleration is still $-g$ (it is not zero)
#### Calculations
##### a. Time to max height (Time of Ascent): $u/g$
##### b. Total Time of Flight (return to same level): $2u/g$
##### c. Maximum Height ($H_{max}$): $u^2 / 2g$
#### Using Displacement Equation
##### a. When calculating time to return to ground from a height, set displacement $s = -H$ (height of tower) rather than calculating ascent and descent separately
##### b. The quadratic equation $s = ut + \frac{1}{2}at^2$ automatically handles the direction changes
### C. Dropping from a Height
#### Initial Conditions
##### a. Dropped implies initial velocity $u = 0$
##### b. Displacement is $-H$ (downwards)
#### Key Formulas
##### a. Time to reach ground: $\sqrt{2H/g}$
##### b. Velocity upon impact: $\sqrt{2gH}$
## VII. VARIABLE ACCELERATION (NON-UNIFORM)
### A. Methods of Solution
#### Integration Approach
##### a. If $a$ depends on time ($f(t)$), integrate $dv = a \, dt$
##### b. If $a$ depends on position ($f(x)$), use $v \, dv/dx = a$ and integrate $v \, dv = a \, dx$
##### c. If $a$ depends on velocity ($f(v)$), rearrange to $dt = dv/a$ or $dx = v \, dv/a$ and integrate
#### Applications
##### a. Air drag problems where Force depends on velocity
##### b. Converting $v-x$ equations to find time or acceleration