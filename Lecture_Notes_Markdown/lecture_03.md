# Lecture 3
### Avi Herman
### 9/10/2024

## Table of Contents
- [Recap and Practice of Lecture 2](#recap-and-practice-of-lecture-2)
  - [4 Major Concepts](#4-major-concepts)
  - [Dropping a Ball from Rest](#dropping-a-ball-from-rest)
  - [Tossing a Ball Upwards](#tossing-a-ball-upwards)
- [Newtown's Third Law](#newtowns-third-law)
- [Support Forces](#support-forces)
- [Energy and Work](#energy-and-work)
- [Lecture 3 Question Set](#lecture-3-question-set)
  - [Why doesn't Newton’s third law imply that all forces cancel each other out?](#1-why-doesnt-newtons-third-law-imply-that-all-forces-cancel-each-other-out)
  - [How are ramps useful? How do they affect the force required to lift something?](#2-how-are-ramps-useful-how-do-they-affect-the-force-required-to-lift-something)
  - [How many deadlifts of 100 kg could you do with the energy from an average daily food intake?](#3-how-many-deadlifts-of-100-kg-could-you-do-with-the-energy-from-an-average-daily-food-intake)
  - [How much energy is lost from heat radiation in a day?](#4-how-much-energy-is-lost-from-heat-radiation-in-a-day)
  - [How much work is done when pushing a desk with friction?](#5-how-much-work-is-done-when-pushing-a-desk-with-friction)
  - [Where did the energy go in the desk-pushing scenario?](#6-where-did-the-energy-go-in-the-desk-pushing-scenario)
- [PollEV Answers](#pollev-answers)

## Recap and Practice of Lecture 2
### 4 Major Concepts
  - Newton's First Law
    - *If an object has no outside forces acting on it, it will continue moving at a constant velocity.*
  - Newton's Second Law
    - *The acceleration of an object is directly proportional to the net force acting on it and inversely proportional to its mass.*
    - $ \vec{a} = \frac{\vec{F}_{\text{net}}}{m}$
  - Motion
    - $\vec{v}_f = \vec{v}_i + \vec{a} \times (t_f - t_i)$
    - $\vec{x}_f = \vec{x}_i + \vec{v}_i \times (t_f - t_i) + \frac{1}{2} \vec{a} \times (t_f - t_i)^2$
  - Gravitational Force
    - $\vec{F}_\text{gravity} = \vec{w} = m \vec{g}$

### Dropping a Ball from Rest
To calculate the time it takes for the ball to fall to the ground, we start with the kinematic equation for the position of the ball:
$$
\vec{x}_f = \vec{x}_i + \vec{v}_i \times (t_f - t_i) + \frac{1}{2} \vec{a} \times (t_f - t_i)^2 
$$

Given:
- Initial position: \( \vec{x}_i = (0, 0, h) \, \text{m} \), where \( h = 10 \, \text{m} \) (the ball starts 10 meters above the ground).
- Final position: \( \vec{x}_f = (0, 0, 0) \, \text{m} \) (the ball reaches the ground).
- Initial velocity: \( \vec{v}_i = (0, 0, 0) \, \text{m/s} \) (the ball is dropped from rest).
- Acceleration due to gravity: \( \vec{a} = (0, 0, -g) \, \text{m/s}^2 \), where \( g = 9.8 \, \text{m/s}^2 \).

We are solving for the time \( t_f - t_i \) it takes for the ball to reach the ground, i.e., when \( \vec{x}_f = (0, 0, 0) \).

The z-component of the equation is:
$$
0 = h + \frac{1}{2} (-g) \times (t_f - t_i)^2 
$$

Rearranging this to solve for \( t_f - t_i \):
1. Move \( h \) to the other side:
$$
-h = -\frac{1}{2} g (t_f - t_i)^2 
$$
2. Multiply both sides by \( -1 \):
$$
h = \frac{1}{2} g (t_f - t_i)^2 
$$
3. Multiply both sides by \( 2 \) to eliminate the fraction:
$$
2h = g (t_f - t_i)^2 
$$
4. Solve for \( t_f - t_i \):
$$
t_f - t_i = \sqrt{\frac{2h}{g}} 
$$

For \( h = 10 \, \text{m} \) and \( g = 9.8 \, \text{m/s}^2 \):
$$
t_f - t_i = \sqrt{\frac{2 \times 10}{9.8}} 
$$

Simplifying:
$$
t_f - t_i = \sqrt{\frac{20}{9.8}} \approx \sqrt{2.04} \approx 1.43 \, \text{seconds} 
$$
Thus, the time it takes for the ball to fall to the ground is approximately \( 1.43 \, \text{seconds} \).

### Tossing a Ball Upwards
We now calculate both the time it takes for a ball tossed upwards to reach its peak and the height of the peak.

Given:
- Initial velocity: \( \vec{v}_i = (0, 0, v_0) \, \text{m/s} \), where \( v_0 = 15 \, \text{m/s} \) (the ball is tossed upwards with an initial speed of 15 m/s).
- Initial position: \( \vec{x}_i = (0, 0, 0) \, \text{m} \) (the ball is tossed from the ground).
- Acceleration due to gravity: \( \vec{a} = (0, 0, -g) \, \text{m/s}^2 \), where \( g = 9.8 \, \text{m/s}^2 \).

At the peak of the motion, the velocity of the ball will be zero (\( v_f = 0 \)). We use the kinematic equation:
$$
v_f = v_i + a \times (t_f - t_i)
$$

Substitute \( v_f = 0 \), \( v_i = v_0 \), and \( a = -g \):
$$
0 = v_0 - g \times (t_f - t_i)
$$

Rearranging to solve for \( t_f - t_i \):
$$
t_f - t_i = \frac{v_0}{g}
$$

Substituting the given values:
$$
t_f - t_i = \frac{15}{9.8} \approx 1.53 \, \text{seconds}
$$
Thus, the ball takes approximately **1.53 seconds** to reach the peak.

Now, we use the following kinematic equation to find the height of the peak:
$$
\vec{x}_f = \vec{x}_i + \vec{v}_i \times (t_f - t_i) + \frac{1}{2} \vec{a} \times (t_f - t_i)^2
$$

Since the motion is vertical, we focus on the z-component of the equation:
$$
h = 0 + v_0 \times (t_f - t_i) + \frac{1}{2} (-g) \times (t_f - t_i)^2
$$

Substitute \( v_0 = 15 \, \text{m/s} \), \( g = 9.8 \, \text{m/s}^2 \), and \( t_f - t_i = 1.53 \, \text{seconds} \):
$$
h = 15 \times 1.53 + \frac{1}{2} (-9.8) \times (1.53)^2
$$

Simplifying:
$$
h = 22.95 - 11.45 \approx 11.5 \, \text{m}
$$
Thus, the height of the peak is approximately **11.5 meters**.

- Equations
  - The time to reach the peak is: 
  $$
  t_f - t_i = \frac{v_0}{g}
  $$
  - The height of the peak is: 
  $$
  h = v_0 \times \frac{v_0}{g} - \frac{1}{2} g \times \left( \frac{v_0}{g} \right)^2
  $$

## Newtown's Third Law
- *For every force from an object A exterted to B, there is an equal in magnitude and opposite in direction force from B exerted to A.*
- $\vec{F}_{\text{BA}} = -\vec{F}_{\text{AB}}$
  - "The force exerted by A on B is equal in magnitude and opposite in direction to the force exerted by B on A."

## Support Forces
- *Support forces are forces that act perpendicular to the surface of an object.*
- *Normal force* is a type of support force that acts perpendicular to the surface of an object.
  - It is the force that prevents objects from falling through the ground.
  - It is what makes springs compress when you sit on a chair, and it is what makes you feel heavier in an elevator that is accelerating upwards.
- The epitome of equal and opposite forces as described by Newton's Third Law.

## Lecture 3 Question Set
### 1. Why doesn't Newton’s third law imply that all forces cancel each other out?
Newton’s third law states that for every action force, there is an equal and opposite reaction force. However, these forces act on different objects, not the same one. Therefore, they do not cancel each other out. The net force on any individual object is determined by the sum of forces acting **on** it, not the forces it exerts on other objects.

### 2. How are ramps useful? How do they affect the force required to lift something?
Ramps decrease the amount of force needed to lift an object by increasing the distance over which the force is applied. The mechanical advantage provided by a ramp allows the same amount of work ($W = Fd$) to be done with a smaller force ($F$) over a longer distance ($d$). This is due to the relationship:
\[ F_{\text{ramp}} = \frac{F_{\text{lift}}}{\sin(\theta)} \]
where $\theta$ is the angle of the ramp, and $F_{\text{lift}}$ is the force required to lift the object vertically.

### 3. How many deadlifts of 100 kg could you do with the energy from an average daily food intake?
The work done to deadlift a mass is given by:
\[
W = mgh
\]
where:
- $m = 100 \, \text{kg}$ is the mass,
- $g = 9.8 \, \text{m/s}^2$ is the acceleration due to gravity,
- $h = 1 \, \text{m}$ is the height lifted.

Thus, the work for a single deadlift is:
\[
W = 100 \times 9.8 \times 1 = 980 \, \text{J}
\]

Given a daily energy intake of approximately 8,000,000 J, the number of deadlifts is:
\[
\text{Number of deadlifts} = \frac{8,000,000}{980} \approx 8163 \, \text{deadlifts}
\]

### 4. How much energy is lost from heat radiation in a day?
A person loses energy at a rate of 100 W, or 100 J/s. The total energy lost in a day is:
\[
\text{Energy loss per day} = 100 \, \frac{J}{s} \times 86400 \, \text{seconds} = 8,640,000 \, \text{J/day}
\]

### 5. How much work is done when pushing a desk with friction?
Work is calculated as:
\[
W = F \times d
\]
where:
- $F = 300 \, \text{N}$ is the horizontal force applied,
- $d = 5 \, \text{m}$ is the displacement.

Thus, the work done is:
\[
W = 300 \times 5 = 1500 \, \text{J}
\]

### 6. Where did the energy go in the desk-pushing scenario?
Even though the gravitational potential energy did not increase, energy was expended. The energy went into overcoming friction between the desk and the floor, which converted the mechanical work into thermal energy. This is consistent with the principle of conservation of energy.

## PollEV Answers
1. *C* (15m)
  - How high is the ceiling of Meyer Hall if it takes a ball 2.3 seconds to go from the ground, to the ceiling, and back to the ground?
  - $\frac{1}{8} \times 10 \frac{m}{s^2} \times (2.3s)^2 = \text{something not close to 15m but timing is tough and something went wrong}$
