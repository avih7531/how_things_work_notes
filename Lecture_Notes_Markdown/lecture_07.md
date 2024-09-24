# Lecture 7
### Avi Herman
### 9/24/2024

## Table of Contents
- [Forces as a Gradient of Potential Energy](#forces-as-a-gradient-of-potential-energy)
  - [Half Pipe Example](#half-pipe-example)
- [Elastic Potential Energy and Restoring Force](#electric-potential-energy-and-restoring-force)
  - [Hooke's Law](#hookes-law)
  - [Example Diagram of a Spring](#example-diagram-of-a-spring)
  - [Harmonic Oscillators](#harmonic-oscillators)
- [Pendulum and Clocks](#pendulum-and-clocks)
- [PollEV Answers](#pollev-answers)

## Forces as a Gradient of Potential Energy
***This entire section seems to not be tested***
- \( E = K + U_\text{gravity} + \text{...} \)
  - \( E \) is the total energy
  - \( K \) is the kinetic energy
  - \( U_\text{gravity} \) is the gravitational potential energy
    - \( U_\text{gravity} = mgh \)
      - \( m \) is the mass
      - \( g \) is the acceleration due to gravity (\(9.81\, \frac{\text{m}}{\text{s}^2}\))
      - \( h \) is the height
        - For a ramp, \( h = x \sin \theta \)
          - \( \theta \) is the angle of the ramp
          - \( x \) is the distance along the ramp
- \( \vec{F} = -\nabla U \) 
  - \( \vec{F} \) is the force
  - \( U \) is the potential energy
  - \( \nabla \) is the gradient operator
    - \( \nabla = \left( \dfrac{\partial}{\partial x}, \dfrac{\partial}{\partial y}, \dfrac{\partial}{\partial z} \right) \)
    - The gradient gives the rate of change of \( U \) in each spatial direction
  - The negative sign indicates the force points in the direction of decreasing potential energy

### Half Pipe Example
- Consider a ramp shaped like a half pipe where \( z \) is the height, \( x \) is the horizontal distance, and the slope is \( c x \)
  - \( z = \dfrac{c}{2} x^2 \)
    - \( c \) is a constant
  - \( U_\text{gravity} = mgz = \dfrac{1}{2} mg c x^2 \)
  - The force is:
    \[
    \vec{F} = -\nabla U_\text{gravity} = -\dfrac{U_\text{gravity}}{dx} \hat{x} = -mgc x \hat{x}
    \]
    - Here, \( mgc \) acts as the spring constant \( k \) in Hooke's Law

## Elastic Potential Energy and Restoring Force
### Hooke's Law 
- Hook's Law states that the force exerted by a spring (or something elastic) is proportional to the displacement from equilibrium
  - \( \vec{F}_\text{restoring} = -k \vec{x} \)
    - \( \vec{F}_\text{restoring} \) is the restoring force
    - \( k \) is the spring constant
    - \( \vec{x} \) is the displacement from equilibrium
  - \( U_\text{spring} = \dfrac{1}{2} k x^2 \)
    - \( U_\text{spring} \) is the spring potential energy
    - \( x \) is the displacement from equilibrium
  - \( \vec{a} = -\dfrac{k}{m} \vec{x} \)
    - \( \vec{a} \) is the acceleration
    - \( m \) is the mass
    - \( \vec{x} \) is the displacement from equilibrium

### Example Diagram of a Spring
![Spring Diagram](https://www.westlab.com/media/amasty/blog/cache/H/o/764/386/Hookes_Law.jpg)

### Harmonic Oscillators
- Harmonic oscillators are systems that oscillate about an equilibrium point
  - Examples include springs, pendulums, and electric circuits
  - The period of oscillation does not depend on the amplitude of the oscillation
- $T = 2 \pi \sqrt{\dfrac{m}{k}}$
  - \( T \) is the period of the oscillation (time for one complete cycle)
  - \( m \) is the mass
  - \( k \) is the spring constant

## Pendulum and Clocks
- A pendulum is a mass on a string that oscillates back and forth
  - The period of a pendulum is given by \( T = 2 \pi \sqrt{\dfrac{L}{g}} \)
    - \( T \) is the period
    - \( L \) is the length of the pendulum
    - \( g \) is the acceleration due to gravity
  - The period of a pendulum is independent of the mass of the pendulum
  - $U_\text{gravity} = \frac{mg}{2L} x^2$
    - \( U_\text{gravity} \) is the gravitational potential energy
    - \( m \) is the mass of the pendulum
    - \( x \) is the displacement from equilibrium
  - $k_\text{pendulum} = \frac{mg}{L}$
    - \( k_\text{pendulum} \) is the spring constant of the pendulum
- Clocks use pendulums to keep time
  - The period of a pendulum is constant, so the clock will keep time accurately

### Pendulum Diagram
![Pendulum Diagram](https://upload.wikimedia.org/wikipedia/commons/b/b2/Simple_gravity_pendulum.svg)
- $\text{massless rod} = L$

###### PollEV Answers
- *D* **All of the above are correct** *we will all get full credit for this question*
  - What are the units of the spring constant "k" in Hooke's law? [J = Joule, kg = kilogram, m = meter, s = second, N = Newton.]
1. **Hooke's Law**:
   - Hooke's law is given by \( F = kx \), where \( F \) is the force applied to the spring, \( k \) is the spring constant, and \( x \) is the displacement of the spring.

2. **Units of Force (F)**:
   - The unit of force \( F \) is the Newton (N).

3. **Units of Displacement (x)**:
   - The unit of displacement \( x \) is the meter (m).

4. **Units of Spring Constant (k)**:
   - Rearranging Hooke's law to solve for \( k \): \( k = \frac{F}{x} \).
   - Therefore, the units of \( k \) are \( \frac{\text{N}}{\text{m}} \).

5. **Dimensional Analysis**:
   - Newton (N) can be expressed in terms of base units: \( 1 \text{ N} = 1 \text{ kg} \cdot \text{m/s}^2 \).
   - Substituting this into the units of \( k \): \( k = \frac{\text{kg} \cdot \text{m/s}^2}{\text{m}} = \text{kg/s}^2 \).

6. **Energy Perspective**:
   - The potential energy stored in a spring is given by \( U = \frac{1}{2} k x^2 \).
   - The unit of energy \( U \) is the Joule (J).
   - Rearranging to solve for \( k \): \( k = \frac{2U}{x^2} \).
   - Therefore, \( k \) can also be expressed in terms of energy per unit displacement squared: \( \frac{\text{J}}{\text{m}^2} \).

Given these analyses, the spring constant \( k \) can be expressed in multiple units:
- \( \frac{\text{N}}{\text{m}} \)
- \( \text{kg/s}^2 \)
- \( \frac{\text{J}}{\text{m}^2} \)

Thus, the answer "all of the above" is correct because the spring constant \( k \) can be represented in terms of Joules (J), kilograms (kg), meters (m), seconds (s), and Newtons (N).

