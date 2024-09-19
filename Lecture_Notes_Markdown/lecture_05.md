# Lecture 5
### Avi Herman
### 9/17/2024

## Table of Contents
- [Rotational Motion](#rotational-motion)
  - [Units](#units)
  - [Rules](#rules)
  - [Right Hand Rule](#right-hand-rule)
    - [Visual Example of Right Hand Rule](#visual-example)
    - [Trick for Right Hand Rule](#trick-for-right-hand-rule)
- [Angular Velocity](#angular-velocity)
  - [Example: Find the angular velocity of the second hand on a clock](#example-find-the-angular-velocity-of-the-second-hand-on-a-clock)
- [Torque](#torque)
  - [Diagram of Torque](#diagram-of-torque)
- [Friction](#friction)
  - [Visual Example of Friction](#visual-example-of-friction)
- [PollEV Answers](#pollev-answers)


## Rotational Motion
### Units
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
### Visual Example of Right Hand Rule
- Note $\vec{\omega} = \vec{L}$ in this example
![Right Hand Rule](https://files.mtstatic.com/site_4539/11790/0?Expires=1726590181&Signature=ID-TUuh02uCfcyaYIhANNqxcQPUlc~~DT2R0-L4DSFltQD6BkBdeyYKnZNUcyaxMEFCKWdI-6abUyJ5pvJXtiAAEix8W7lJ9wnTk5~NzqbAbfuZ0ybJ-xEEw~DKPeTGVnF7Gekv16JVj7csbOldQpPoWVpy4LGywCJYq6We8RG4_&Key-Pair-Id=APKAJ5Y6AV4GI7A555NA)

### Trick for Right Hand Rule
- Clockwise = away from you
- Counterclockwise = towards you

## Angular Velocity
$\vec{\omega} = \frac{\vec{\theta}_f - \vec{\theta}_i}{t_f - t_i}$

### Example: Find the angular velocity of the second hand on a clock
- Understanding the Rotation and Angular Velocity
  - The second hand completes one full rotation (360°) in 60 seconds. In radians, a full rotation is \( 2\pi \) radians.
- Right-Hand Rule
  - For clocks, the second hand rotates clockwise. However, angular velocity and momentum are typically defined using the right-hand rule:
    - Curl the fingers of your right hand in the direction of the second hand's rotation (clockwise).
    - Your thumb points in the direction of the angular velocity vector \( \vec{\omega} \), which, in this case, points downward (into the clock face).
- Time for One Full Rotation
  - One complete revolution of the second hand takes 60 seconds.
- Calculating Angular Velocity
  - Angular velocity \( \omega \) is defined as the change in angular displacement over time. For uniform circular motion:
  \[
  \omega = \frac{\Delta \theta}{\Delta t}
  \]
    - Here, \( \Delta \theta = 2\pi \) radians (full circle) and \( \Delta t = 60 \text{ s} \).
- Angular Velocity (in radians per second)
  \[
  \omega = \frac{2\pi \text{ rad}}{60 \text{ s}} = \frac{\pi}{30} \text{ rad/s}
  \]

## Torque
- Torque is the rotational equivalent of force.
- $\vec{\alpha} = \frac{\vec{\tau}_{\text{net}}}{I}$
  - Units of $\vec{\tau}$ are Nm
  - Units of $\vec{\alpha}$ are $\frac{\text{rad}}{s^2}$
- $I$ rotational mass measures $\text{mass} \times \text{distance}^2$
  - Units of $I$ are kg m$^2$
- $\tau = |\vec{\tau}| = \vec{r} \times \vec{F}_\perp$
  - $\vec{r}$ is the distance from the axis of rotation
  - $\vec{F}$ is the force applied
### Diagram of Torque
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

### Visual Example of Friction
- Note $\vec{F}_\text{support} = \vec{F}_\text{normal}$
![Friction Diagram](https://tuitionphysics.com/wp-content/uploads/2020/06/free-body-diagram.jpg)

---

###### PollEV Answers
*D* ($\frac{2 \pi}{\text{day}} = 0.000727 \frac{\text{radians}}{s}$)
  - What is the angular speed of Earth around its axis?

To solve for the angular speed of the Earth around its axis, we can use the given information:

The Earth completes one full rotation (2π radians) in one day (24 hours).

First, convert the time period from days to seconds:
\[ 1 \text{ day} = 24 \text{ hours} \]
\[ 24 \text{ hours} = 24 \times 60 \text{ minutes} = 1440 \text{ minutes} \]
\[ 1440 \text{ minutes} = 1440 \times 60 \text{ seconds} = 86400 \text{ seconds} \]

Now, the angular speed (\(\omega\)) is given by:
\[ \omega = \frac{\Delta \theta}{\Delta t} \]

Where:
- \(\Delta \theta = 2\pi \text{ radians}\)
- \(\Delta t = 86400 \text{ seconds}\)

So,
\[ \omega = \frac{2\pi \text{ radians}}{86400 \text{ seconds}} \]

Simplify the expression:
\[ \omega = \frac{2\pi}{86400} \approx 0.0000727 \text{ radians/second} \]

Thus, the angular speed of the Earth around its axis is approximately \(0.0000727 \text{ radians/second}\).

