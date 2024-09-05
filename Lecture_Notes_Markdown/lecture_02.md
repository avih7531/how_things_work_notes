# Lecture 2
### Avi Herman
### 9/5/2024

## Table of Contents
1. [Newton's First Law of Motion](#newtons-first-law-of-motion)
2. [Newton's Second Law of Motion](#newtons-second-law-of-motion)
3. [Gravitational Force](#gravitational-force)
4. [PollEV Answers](#pollev-answers)

## Newton's First Law of Motion
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

## Newton's Second Law of Motion
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
- Thus, the equation of finding the final position of an object is $\vec{x}_f = \vec{x}_i + \vec{v}_i \cdot (t_f - t_i) + \frac{1}{2} \vec{a} \cdot (t_f - t_i)^2$
- In three-dimensional motion, we often need to consider the motion in each direction separately. For example, the motion in the z direction can be described similarly to the motion in the x and y directions. The equation for the final velocity in the z direction is:
  - $\vec{v}_zf = \vec{v}_i + \vec{a} \cdot (t_f - t_i)$
    - $\vec{v}_zf$ is the final velocity in the z direction ($\frac{m}{s}$)
    - $\vec{v}_i$ is the initial velocity ($\frac{m}{s}$)
    - $\vec{a}$ is the acceleration ($\frac{m}{s^2}$)
    - $t_f$ is the final time ($s$)
    - $t_i$ is the initial time ($s$)
  - ***This is less important than the other two equations in this section.***
- Equation for finding the average velocity of an object: $\vec{v}_{\text{avg}} = \frac{\vec{v}_i + \vec{v}_f}{2}$
  - $\vec{v}_{\text{avg}}$ is the average velocity ($\frac{m}{s}$)
  - $\vec{v}_i$ is the initial velocity ($\frac{m}{s}$)
  - $\vec{v}_f$ is the final velocity ($\frac{m}{s}$)
- To find the final position of an object, we can use the average velocity and the time interval. The average velocity can be expressed as:
  $\vec{v}_{\text{avg}} = \vec{v}_i + \frac{\vec{a} \cdot (t_f - t_i)}{2}$
- By integrating the average velocity over the time interval, we get the equation for the final position:
  $\vec{x}_f = \vec{x}_i + \vec{v}_i \cdot (t_f - t_i) + \frac{1}{2} \vec{a} \cdot (t_f - t_i)^2$
  - $\vec{x}_f$ is the final position
  - $\vec{x}_i$ is the initial position
  - $\vec{v}_i$ is the initial velocity
  - $\vec{a}$ is the acceleration
  - $t_f$ is the final time
  - $t_i$ is the initial time
- ***We will not be tested on derivation. To derive these equations you need calculus. Rather I include each step to show the steps in derivation***

## Gravitational Force
| Force            | Symbol       | Description                                                                 | Direction                                      |
|------------------|--------------|-----------------------------------------------------------------------------|------------------------------------------------|
| Gravitational    | $\vec{F}_g$ or $\vec{w}$ = $\vec{\text{weight}}$ | The force of attraction between two masses. $\vec{F}_g = (0, 0, -9.8 \frac{m}{s^2})$                                | Towards the center of the Earth (downwards)    |
| Frictional       | $\vec{F}_f$  | The force that opposes the motion of an object.                             | Opposite to the direction of motion            |
| Normal           | $\vec{F}_N$  | The support force exerted by a surface perpendicular to the object.         | Perpendicular to the surface (upwards)         |
| Drag             | $\vec{F}_d$  | The force that opposes the motion of an object through a fluid.             | Opposite to the direction of motion            |
- The *equivelence principle* states that the force of gravity is equivalent to the force of acceleration. This is why objects in free fall experience weightlessness.
- When dropping an object from a height, the object will accelerate downwards at a rate of $9.8 \frac{m}{s^2}$.
  - Putting that into a formula gives us $\vec{x}_f = \vec{x}_i + \vec{v}_i \cdot (t_f - t_i) + \frac{1}{2} \vec{a} \cdot (t_f - t_i)^2$
    - $\vec{X}_i = (0, 0, h)$
    - $\vec{v}_i = (0, 0, 0)$
    - $\vec{a} = \vec{g} = (0, 0, -9.8 \frac{m}{s^2})$
  - Rearranging, $h = \frac{1}{2} \cdot 9.8 \cdot t^2$
  - And $\frac{2h}{g} = t_f-t_i $
- Example: If an object is dropped from a height of 100 meters, how long will it take to hit the ground?
  - $t_f = \sqrt{\frac{2 \cdot 100}{9.8}} \approx 4.52 s$

###### PollEV Answers
1. *D* (2, 2, -2)
 - What is $\vec{x}_f$ if $\vec{x}_i = (-4, 6, -8)$, $\vec{v} = (2, \frac{-4}{3}, 2)$, $t_f = 3$, and $t_i = 0$?

