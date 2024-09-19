# Lecture 6
### Avi Herman
### 9/19/2024

## Table of Contents
- [Wheels](#wheels)
  - [Diagram of Forces on a Wheel](#diagram-of-forces-on-a-wheel)
  - [Angular Velocity of a Wheel](#angular-velocity-of-a-wheel)
- [Work + Power](#work--power)
- [Kinetic Energy](#kinetic-energy)
  - [Formulas for Kinetic Energy](#formulas-for-kinetic-energy)
- [Momentum and Impulse](#momentum-and-impulse)
  - [Momentum](#momentum)
  - [Impulse](#impulse)
- [PollEV Answers](#pollev-answers)

## Wheels
- Wheels are a type of simple machine which are used to reduce friction and make it easier to move objects.
- $\vec{v}_{\text{ground}}$ must be $0$ which means that the wheel is not slipping (because wheels *roll*) and so $\vec{v}_{\text{contact point}} = \vec{v}_{\text{ground}}$.
  - No work down by frictional forces from the ground to the wheel.
- $\vec{v}_{\text{top}} = \vec{v}_{\text{contact point}}$

### Diagram of Forces on a Wheel
![Diagram of Forces on a Wheel](https://www.researchgate.net/publication/282517347/figure/fig3/AS:669953812344839@1536740844428/Scheme-of-forces-acting-on-rotating-wheel.png)
### Angular Velocity of a Wheel
- Use right hand rule to determine the direction of the angular velocity vector.
  - $\vec{\omega} = \frac{\vec{v}_{\text{contact point}}}{r}$ where $r$ is the radius of the wheel.

## Work + Power
- Translational Motion
  - $\text{work} = W = \vec{F} \cdot \vec{\Delta x} = F_{\parallel} \Delta x$
    - $W$ is the work done by a force.
    - $\vec{F}$ is the force applied.
    - $\vec{\Delta x}$ is the displacement of the object.
    - $F_{\parallel}$ is the component of the force parallel to the displacement.
  - $\text{power} = \vec{F} \cdot \vec{v} = \frac{W}{\Delta t}$
    - $\text{power}$ is the rate at which work is done.
    - $\vec{F}$ is the force applied.
    - $\vec{v}$ is the velocity of the object.
    - $W$ is the work done by a force.
    - $\Delta t$ is the time interval.
- Rotational Motion
  - $\text{work} = W = \vec{\tau} \cdot \vec{\Delta \theta} = \vec{\tau} \cdot (\vec{\theta_f} - \vec{\theta_i})$
    - $W$ is the work done by a torque.
    - $\vec{\tau}$ is the torque applied.
    - $\vec{\Delta \theta}$ is the angular displacement of the object.
    - $\vec{\theta_f}$ is the final angle of the object.
    - $\vec{\theta_i}$ is the initial angle of the object.
  - $\text{power} = \vec{\tau} \cdot \vec{\omega} = \frac{W}{\Delta t}$
    - $\text{power}$ is the rate at which work is done.
    - $\vec{\tau}$ is the torque applied.
    - $\vec{\omega}$ is the angular velocity of the object.
    - $W$ is the work done by a torque.
    - $\Delta t$ is the time interval.

## Kinetic Energy
- Kinetic energy is the energy of motion.
  - This means that the total energy of a system is constant.
### Formulas for Kinetic Energy
- $K = \frac{1}{2} m v^2$ for translational motion.
- $K = \frac{1}{2} I \omega^2$ for rotational motion.
- Total energy is *conserved*
  - $u = mgh$
    - $u$ is the potential energy of an object.
    - $m$ is the mass of the object.
    - $g$ is the acceleration due to gravity ($-9.8 \frac{m}{s^2}$).
    - $h$ is the height of the object.
  - $\text{total energy} = K + u + heat + \text{...}$

## Momentum and Impulse
### Momentum
- Momentum is the product of mass and velocity.
  - Refers to the quantity of motion an object has.
- Translational Motion
  - $\vec{p} = m \vec{v}$ 
    - $\vec{p}$ is the momentum of an object ($kg \frac{m}{s}$).
    - $m$ is the mass of the object.
    - $\vec{v}$ is the velocity of the object.
  - If no forces are applied, momentum is conserved.
- Rotational Motion
  - $\vec{L} = I \vec{\omega}$
    - $\vec{L}$ is the angular momentum of an object ($kg \frac{m^2}{s}$).
    - $I$ is the moment of inertia of the object.
    - $\vec{\omega}$ is the angular velocity of the object
  - No $\vec{\tau}$ means $\vec{L}$ is constant.
### Impulse
- Impulse is the change in momentum. 
  - Quantifies the overall effect of a force on an object across a time interval.
- Translational Motion
  - $\Delta \vec{p} = \vec{p_f} - \vec{p_i} = \vec{F} \cdot \Delta t$
    - $\Delta \vec{p}$ is the change in momentum.
    - $\vec{F}$ is the force applied.
    - $\Delta t$ is the time interval.
- Rotational Motion
  - $\Delta \vec{L} = \vec{L_f} - \vec{L_i} = \vec{\tau} \cdot \Delta t$
    - $\Delta \vec{L}$ is the change in angular momentum.
    - $\vec{\tau}$ is the torque applied.
    - $\Delta t$ is the time interval.




###### PollEV Answers
- *A* (+v, 0, -v)
  - What is the velocity vector of right middle point of a wheel's rim?
- *C* ($50 \frac{m}{s}$)
  - A roller coaster car drops from rest at a height of $150 m$ along a complicated track. Ignoring friction, what is the velocity of the car $25 m$ above the ground?
  
    - To determine the speed of the roller coaster car at 25 meters above the ground, we can use the principle of **conservation of mechanical energy**. This principle states that in the absence of non-conservative forces (like friction), the total mechanical energy (potential + kinetic) of an object remains constant.

**Given:**
- **Initial Height (\( h_i \))**: 150 meters
- **Final Height (\( h_f \))**: 25 meters
- **Initial Speed (\( v_i \))**: 0 m/s (since it starts from rest)
- **Acceleration due to Gravity (\( g \))**: 9.8 m/s²

**Steps:**

1. **Calculate the Change in Height (\( \Delta h \))**:
   \[
   \Delta h = h_i - h_f = 150\, \text{m} - 25\, \text{m} = 125\, \text{m}
   \]

2. **Apply Conservation of Energy**:
   \[
   \text{Potential Energy Initial} + \text{Kinetic Energy Initial} = \text{Potential Energy Final} + \text{Kinetic Energy Final}
   \]
   \[
   mgh_i + \frac{1}{2}mv_i^2 = mgh_f + \frac{1}{2}mv^2
   \]
   Since the car starts from rest (\( v_i = 0 \)), the equation simplifies to:
   \[
   mgh_i = mgh_f + \frac{1}{2}mv^2
   \]
   The mass (\( m \)) cancels out:
   \[
   gh_i = gh_f + \frac{1}{2}v^2
   \]

3. **Solve for Final Speed (\( v \))**:
   \[
   gh_i - gh_f = \frac{1}{2}v^2
   \]
   \[
   v^2 = 2g(h_i - h_f) = 2 \times 9.8\, \text{m/s}² \times 125\, \text{m} = 2450\, \text{m}²/\text{s}²
   \]
   \[
   v = \sqrt{2450\, \text{m}²/\text{s}²} \approx 49.5\, \text{m/s}
   \]

**Final Answer:**
The roller coaster car would be moving at approximately **49.5 meters per second** when it is 25 meters above the ground.
