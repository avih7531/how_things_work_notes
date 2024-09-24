# Test 1
### Avi Herman
### 10/1/2024

## Table of Contents
- [Vectors & Scalars](#vectors--scalars)
- [Units](#units)
- [Newton's Laws of Motion](#newtons-laws-of-motion)
  - [Newton's First Law of Motion](#newtons-first-law-of-motion)
  - [Newton's Second Law of Motion](#newtons-second-law-of-motion)
  - [Newton's Third Law of Motion](#newtons-third-law-of-motion)
- [Gravitational Force](#gravitational-force)
- [Ramps](#ramps)
  - [Ramp Anatomy](#ramp-anatomy)
  - [Gravitational Force on an Inclined Plane](#gravitational-force-on-an-inclined-plane)
- [Work](#work)
- [Rotational Motion](#rotational-motion)
  - [Units of Motion](#units-of-motion)
  - [Rules](#rules)
  - [Right Hand Rule](#right-hand-rule)
  - [Angular Velocity](#angular-velocity)
  - [Torque](#torque)
    - [Diagram of Torque](#diagram-of-torque)
- [Friction](#friction)
- [Wheels](#wheels)
  - [Diagram of Forces on a Wheel](#diagram-of-forces-on-a-wheel)
  - [Angular Velocity of a Wheel](#angular-velocity-of-a-wheel)
- [Work + Power](#work--power)
- [Kinetic Energy](#kinetic-energy)
  - [Formulas for Kinetic Energy](#formulas-for-kinetic-energy)
- [Momentum and Impulse](#momentum-and-impulse)
  - [Momentum](#momentum)
  - [Impulse](#impulse)
- [Elastic Potential Energy and Restoring Force](#elastic-potential-energy-and-restoring-force)
  - [Hooke's Law](#hookes-law)
  - [Example Diagram of a Spring](#example-diagram-of-a-spring)
  - [Harmonic Oscillators](#harmonic-oscillators)
- [Pendulum and Clocks](#pendulum-and-clocks)
  - [Pendulum Diagram](#pendulum-diagram)
- [Notes](#notes)

## Vectors & Scalars
- Scaler  
  - A quantity that has magnitude only
- Vectors are quantities that have both *magnitude* and *direction*
  - Magnitude
    - The size of the vector
    - Examples: $1$, $2$, $3$, $4$
  - Direction
    - The direction the vector is pointing
    - Examples: North, South, East, West
  - Examples: Velocity, force, displacement
  - Position vector
    - A vector that points from the origin to a point in space
    - Example: home is $\langle 0, 0 \rangle$, lecture hall is $\langle -1, 3 \rangle$, and coffee shop is $\langle 2, 2 \rangle$
      - The noted as $\vec{V}$ from home to lecture hall is **$X$ mph north**
       - $\hat{V}$ = **north**
       - $|\vec{V}|$ = **$X$**
      - To go from the lecture hall to the coffee shop, you would go **$X$ MPH east**
       - To get the vector length, you would use the Pythagorean theorem (where vector length is the hypotenuse)
         - $\sqrt{(x_2-x_1)^2 + (y_2-y_1)^2}$
         - $\sqrt{(2-(-1))^2 + (2-3)^2}$ = 
         - $\sqrt{3^2 + (-1)^2}$ =
         - $\sqrt{9 + 1}$ = 
         - **$\sqrt{10}$**
       - To get the vector displacement, you would subtract the two vectors
         - $\langle x_2, y_2 \rangle - \langle x_1, y_1 \rangle = \langle x_2-x_1, y_2-y_1 \rangle$
         - $2-(-1) = 3$ and $2-3 = -1$ and thus the vector displacement is **$\langle 3, -1 \rangle$**

## Units
- Dimensionless numbers
  - Numbers that have no units
      - Examples: $1$, $2$, $3$, $4$
  - Dimensional numbers
    - Numbers that have units
      - Examples: $100W$, $10kg$, $25V$
  - Examples: The temperature in a room, the mass of an object
- Dimensional Scalers
  - Dimensionless number **x** unit
    - Examples: $1m$, $2kg$, $3s$, $300,000m/s$

| Thing to Measure    | Unit                                          |
|---------------------|-----------------------------------------------|
| Length              | Meters ($m$)                                  |
| Area                | Square meters ($m^2$)                         |
| Volume              | Cubic meters ($m^3$)                          |
| Time                | Seconds ($s$)                                 |
| Angle               | Radians ($rad$), $1$ degree = $\pi/180$ radians |
| Mass                | Kilograms ($kg$)                              |
| Speed               | Meters per second ($m/s$)                     |
| Force               | Newtons ($kg \cdot m/s^2$)                    |
| Temperature         | Fahrenheit ($F$), Celsius ($C$), Kelvin ($K$) |


## Newton's Laws of Motion
### Newton's First Law of Motion
- **An object subject to no external forces moves at a constant velocity.**
- Equation of predicting an object at constant velocity: $\vec{x}_f = \vec{x}_i + \vec{v} \cdot (t_f - t_i)$
  - $\vec{x}_f$ is the final position ($m$)
  - $\vec{x}_i$ is the initial position ($m$)
  - $\vec{v}$ is the velocity ($\frac{m}{s}$)
  - $t_f$ is the final time ($s$)
  - $t_i$ is the initial time ($s$)
- Example of finding the final position of an object at constant velocity:
  - What is $\vec{x}_f$ if $\vec{x}_i = (-4, 6, -8)$, $\vec{v} = (2, \frac{-4}{3}, 2)$, $t_f = 3$, and $t_i = 0$?
    - $\vec{x}_f = \vec{x}_i + \vec{v} \cdot (t_f - t_i)$
    - $\vec{x}_f = (-4, 6, -8) + (2, \frac{-4}{3}, 2) \cdot (3)$
    - $\vec{x}_f = (-4, 6, -8) + (6, -4, 6)$
    - $\vec{x}_f = (2, 2, -2)$

### Newton's Second Law of Motion
- **The acceleration that an object experiences is equal to the net force exerted on it divided by the object's mass.**
- Equation of predicting the acceleration of an object: $\vec{a} = \frac{\vec{F}_{\text{net}}}{m}$
  - $\vec{a}$ is the acceleration ($\frac{m}{s^2}$)
  - $\vec{F}_{\text{net}}$ is the net force ($N \cdot m$ *Newton meters*)
  - $m$ is the mass of the object ($kg$)
- Equation of predicting an object's final velocity: $\vec{v}_f = \vec{v}_i + \vec{a} \cdot (t_f - t_i)$
  - $\vec{v}_f$ is the final velocity ($\frac{m}{s}$)
  - $\vec{v}_i$ is the initial velocity ($\frac{m}{s}$)
  - $\vec{a}$ is the acceleration ($\frac{m}{s^2}$)
  - $t_f$ is the final time ($s$)
  - $t_i$ is the initial time ($s$)
- Equation for finding the average velocity of an object: $\vec{v}_{\text{avg}} = \frac{\vec{v}_i + \vec{v}_f}{2}$
  - $\vec{v}_{\text{avg}}$ is the average velocity ($\frac{m}{s}$)
  - $\vec{v}_i$ is the initial velocity ($\frac{m}{s}$)
  - $\vec{v}_f$ is the final velocity ($\frac{m}{s}$)
- By integrating the average velocity over the time interval, we get the equation for the final position:
  $\vec{x}_f = \vec{x}_i + \vec{v}_i \cdot (t_f - t_i) + \frac{1}{2} \vec{a} \cdot (t_f - t_i)^2$
  - $\vec{x}_f$ is the final position
  - $\vec{x}_i$ is the initial position
  - $\vec{v}_i$ is the initial velocity
  - $\vec{a}$ is the acceleration
  - $t_f$ is the final time
  - $t_i$ is the initial time

### Newton's Third Law of Motion
- *For every force from an object A exterted to B, there is an equal in magnitude and opposite in direction force from B exerted to A.*
- $\vec{F}_{\text{BA}} = -\vec{F}_{\text{AB}}$
  - "The force exerted by A on B is equal in magnitude and opposite in direction to the force exerted by B on A."


## Gravitational Force
| Force            | Symbol       | Description                                                                 | Direction                                      |
|------------------|--------------|-----------------------------------------------------------------------------|------------------------------------------------|
| Gravitational    | $\vec{F}_g$ or $\vec{w}$ = $\vec{\text{weight}}$ | The force of attraction between two masses. $\vec{F}_g = (0, 0, -9.81 \frac{m}{s^2})$                                | Towards the center of the Earth (downwards)    |
| Frictional       | $\vec{F}_f$  | The force that opposes the motion of an object.                             | Opposite to the direction of motion            |
| Normal           | $\vec{F}_N$  | The support force exerted by a surface perpendicular to the object.         | Perpendicular to the surface (upwards)         |
| Drag             | $\vec{F}_d$  | The force that opposes the motion of an object through a fluid.             | Opposite to the direction of motion            |
- The *equivelence principle* states that the force of gravity is equivalent to the force of acceleration. This is why objects in free fall experience weightlessness.
- When dropping an object from a height, the object will accelerate downwards at a rate of $-9.81 \frac{m}{s^2}$.
  - Putting that into a formula gives us $\vec{x}_f = \vec{x}_i + \vec{v}_i \cdot (t_f - t_i) + \frac{1}{2} \vec{a} \cdot (t_f - t_i)^2$
    - $\vec{X}_i = (0, 0, h)$
    - $\vec{v}_i = (0, 0, 0)$
    - $\vec{a} = \vec{g} = (0, 0, -9.81 \frac{m}{s^2})$
  - Rearranging, $h = \frac{1}{2} \cdot -9.81 \cdot t^2$

## Ramps
### Ramp Anatomy
- Ramps are a simple machine that allow us to lift heavy objects with less force.
```
         *  |
        **  |
       ***  |
      ****  | 
     *****  | 
    ******  | 
   *******  |  height
  ********  |  ^
 *********  |  |
*θ********  |  |

base -->
```
Here, we can find the angle $\theta$ using the relationship:

$$\tan(\theta) = \frac{\text{height}}{\text{base}}$$

By the Pythagorean theorem, the length of the ramp (hypotenuse) can be calculated if the height and base are known:

$$\text{length} = \sqrt{\text{height}^2 + \text{base}^2}$$

### Gravitational Force on an Inclined Plane

When an object is placed on an inclined plane, the gravitational force acting on it can be resolved into two components:

1. **Parallel Component ($F_{\parallel}$)**: This component acts parallel to the surface of the inclined plane and causes the object to slide down.
2. **Perpendicular Component ($F_{\perp}$)**: This component acts perpendicular to the surface of the inclined plane and is responsible for the normal force.
![Inclined Plane Diagram](https://stickmanphysics.com/wp-content/uploads/2020/10/Incline-Plane.jpg)

The gravitational force ($F_g$) acting on the object can be expressed as:

$$F_g = m \cdot g = F_w$$ 

where:
- $m$ is the mass of the object
- $g$ is the acceleration due to gravity ($9.8 \text{m/s}^2$)

The parallel and perpendicular components can be calculated using the angle of the incline ($\theta$):

$$F_{\parallel} = F_g \cdot \sin(\theta) = m \cdot g \cdot \sin(\theta)$$

$$F_{\perp} = F_g \cdot \cos(\theta) = m \cdot g \cdot \cos(\theta)$$

### Forces at Work on an Inclined Plane
| Symbol       | Name                   | Description                                                                 | Calculation Formula |
|--------------|------------------------|-----------------------------------------------------------------------------|---------------------|
| $F_w$        | Weight                 | The gravitational force acting on the object.                               | $F_w = m \cdot g$   |
| $F_{\perp}$  | Perpendicular Component | The component of the gravitational force acting perpendicular to the surface of the inclined plane. | $F_{\perp} = F_w \cdot \cos(\theta)$ |
| $F_N$        | Normal Force           | The force exerted by the inclined plane on the object, equal in magnitude and opposite in direction to $F_{\perp}$. | $F_N = -F_{\perp}$   |
| $F_{\parallel}$ | Parallel Component    | The component of the gravitational force acting parallel to the surface of the inclined plane, causing the object to slide down. | $F_{\parallel} = F_w \cdot \sin(\theta)$ |

## Work
*Work* is the transfer of energy from one object to another
The *Work-Energy Principle* state the work done on an object is equal to the force applied to the object times the distance the object moves in the direction of the force
$$\text{Work} = \vec{\text{F}} \times \vec{\Delta x} = \vec{F} \cdot (\vec{x}_f - \vec{x}_i)$$
$\text{Note that } \vec{F} = \vec{F_{\parallel}} + \vec{F_{\perp}}$
- You only do work if the displacement is a non-zero component of the force

## Rotational Motion
### Units of Motion
| **Translational Motion** | **Rotational Motion** |
|--------------------------|-----------------------|
| **Position**: $\vec{x}$ (m) | **Angle**: $\vec{\theta}$ (rad) |
| **Velocity**: $\vec{v}$ ($\frac{m}{s}$) | **Angular Velocity**: $\vec{\omega}$ ($\frac{\text{rad}}{\text{s}}$) |
| **Acceleration**: $\vec{a}$  ($\frac{m}{s^2}$) | **Angular Acceleration**: $\vec{\alpha}$  ($\frac{\text{rad}}{s^2}$)|
| **Force**: $\vec{F}$ (N) | **Torque**: $\vec{\tau}$ (Nm) |
| **Mass**: $m$ (kg) | **Rotational Mass/Moment of Inertia**: $I$ (kg m$^2$) |

### Rules
| **Translational Motion**                     | **Rotational Motion**                              |
|----------------------------------------------|----------------------------------------------------|
| No outside forces means constant $\vec{v}$   | No outside torques means constant $\vec{\omega}$   |
| $\vec{a} = \frac{\vec{\text{Fnet}}}{m}$      | $\vec{\alpha} = \frac{\vec{\tau}_{\text{net}}}{I}$ |
| $\vec{F}_{\text{BA}} = -\vec{F}_{\text{AB}}$ | $\vec{\tau}_{\text{BA}} = -\vec{\tau}_{\text{AB}}$ |

### Right Hand Rule
- The right hand rule is used to determine the direction of the angular momentum vector $(\vec{\omega})$.
1. **Identify the Rotation Axis**: Determine the axis around which the object is rotating.
2. **Curl Your Fingers**: Point the fingers of your right hand in the direction of the rotation (the direction in which the object is moving).
3. **Thumb Direction**: Extend your thumb perpendicular to your fingers. The direction your thumb points is the direction of the angular momentum vector $(\vec{\omega})$.
- Example
  - If a wheel is rotating counterclockwise when viewed from above, you would:
  - Point your fingers in the direction of the rotation (counterclockwise).
  - Your thumb will point upwards, indicating that the angular momentum vector $(\vec{\omega})$ is directed upwards.
- Trick
  - Clockwise = away from you
  - Counterclockwise = towards you

### Angular Velocity
*Angular velocity* is the rate of change of angular displacement with respect to time.
- $\vec{\omega} = \frac{\vec{\theta}_f - \vec{\theta}_i}{t_f - t_i}$

### Torque
- Torque is the rotational equivalent of force.
- $\vec{\alpha} = \frac{\vec{\tau}_{\text{net}}}{I}$
  - Units of $\vec{\tau}$ are Nm
  - Units of $\vec{\alpha}$ are $\frac{\text{rad}}{s^2}$
- $I$ rotational mass measures $\text{mass} \times \text{distance}^2$
  - Units of $I$ are kg m$^2$
- $\tau = |\vec{\tau}| = \vec{r} \times \vec{F}_\perp$
  - $\vec{r}$ is the distance from the axis of rotation
  - $\vec{F}$ is the force applied
#### Diagram of Torque
![Torque Diagram](https://lh3.googleusercontent.com/proxy/fOcdDRBrIp5G8LjbYsXORZzam1YwKKHVTKIzpPaU75jFemEVpSrsEDwBht649q1Du5qPChdNMA5DhSIat_sfle9aaX3yFrfWAmrIxZuRVu9XP2i_IpcjyGVYAIyHhHF2)
- Note $\vec{F} = \vec{F}_\perp$

## Friction
- Friction is a force that opposes motion.
  - Static friction prevents motion
  - Sliding friction slows motion
- $\vec{F}_{\text{sliding friction}} = \mu_{\text{sliding friction}} \cdot \vec{F}_{\text{support}}$
  - $\mu$ is the coefficient of friction
  - $\vec{F}_{\text{support}}$ is the support force
- $\hat{F}_{\text{sliding friction}} = -\hat{v}$ if $\vec{v} > 0$
  - $\hat{v}$ is the velocity of the object
- $F_{\text{static friction}} = F_{\text{push}}$ if $F_{\text{push}} < \mu_{\text{static friction}} \cdot F_{\text{support}}$
  - $F_{\text{push}}$ is the force applied to the object
  - $\mu_{\text{static friction}}$ is the coefficient of static friction
  - $F_{\text{support}}$ is the support force

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

## Notes
- Please refer to the [equation sheet](https://brightspace.nyu.edu/d2l/le/lessons/397843/topics/10770622) for what equations you will have for the exam
- I have left out *Forces as a Gradient of Potential Energy* as it seems like it will not be tested
