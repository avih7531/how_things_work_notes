# Lecture 4
### Avi Herman
### 9/12/2024

## Table of Contents
- [Ramps](#ramps)
  - [Ramp Anatomy](#ramp-anatomy)
  - [Gravitational Force on an Inclined Plane](#gravitational-force-on-an-inclined-plane)
- [Energy and Work](#energy-and-work)
  - [Types of Energy](#types-of-energy)
  - [Work](#work)
- [PollEV Answers](#pollev-answers)

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

## Energy and Work
### Types of Energy
- Two types of energy
  - **Kinetic Energy**: Energy of motion
    - Translational motion
      - Sliding, rolling, etc.
    - Rotational motion
      - Spinning, rotating, etc.
    - Heat
      - Heat is the vibration of atoms and molecules
  - **Potential Energy**: Energy of forces between objects
    - Gravitational potential energy
      - Energy due to the position of an object in a gravitational field
    - Elastic potential energy
      - Energy stored in objects that can be stretched or compressed
    - Chemical potential energy
      - Energy stored in the bonds between atoms and molecules
    - Electromagnetic potential energy
      - Energy stored in electric and magnetic fields

### Work
- **Work**: The transfer of energy from one object to another
- **Work-Energy Principle**: The work done on an object is equal to the force applied to the object times the distance the object moves in the direction of the force
$$\text{Work} = \vec{\text{F}} \times \vec{\Delta x} = \vec{F} \cdot (\vec{x}_f - \vec{x}_i)$$
$\text{Note that } \vec{F} = \vec{F_{\parallel}} + \vec{F_{\perp}}$
- You only do work if the displacement is a non-zero component of the force

###### PollEV Answers
1. *A* (The minimal amount of work required is independent of the angle θ of the ramp)
  - How does the work required to lift a block of stone onto the top of pyramid of Giza depend on the angle θ of the ramp?

The work done \( W \) is given by the formula:

\[ W = F \cdot d \cdot \cos(\theta) \]

where:
- \( F \) is the force applied,
- \( d \) is the displacement,
- \( \theta \) is the angle between the force and the direction of displacement.

When lifting the block vertically, the force required is equal to the weight of the block \( (mg) \), and the displacement is the height \( h \) of the pyramid. Therefore, the work done is:

\[ W = m \cdot g \cdot h \]

This calculation shows that the work depends only on the mass of the block, the gravitational acceleration, and the height of the pyramid, not on the angle of the ramp. The angle θ affects the path taken and the force distribution along the ramp but does not change the total work required to achieve the vertical displacement.

2. *D* (30,000,000 J)
  - How much higher is the gravitational potential energy of a stone block with mass of 20,000 kg on the top of the Great Pyramid (height = 150 m) than on the ground?
\[ \Delta U = m \cdot g \cdot h \]

where:
- \( m \) is the mass (20,000 kg)
- \( g \) is the acceleration due to gravity (9.8 m/s²)
- \( h \) is the height (150 m)

Step-by-step calculation:
1. Multiply the mass by the acceleration due to gravity:
\[ 20,000 \, \text{kg} \times 9.8 \, \text{m/s}^2 = 196,000 \, \text{N} \]

2. Multiply the result by the height:
\[ 196,000 \, \text{N} \times 150 \, \text{m} = 29,400,000 \, \text{J} \]

So, the gravitational potential energy difference is:
\[ 29,400,000 \, \text{J} \]

Therefore, the gravitational potential energy of the stone block on top of the Great Pyramid is 29,400,000 J higher than on the ground.


