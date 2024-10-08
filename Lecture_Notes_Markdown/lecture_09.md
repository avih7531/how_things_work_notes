# Lecture 9
### Avi Herman
### 10/8/2024

## Table of Contents
- [Electric Forces](#electric-forces)
  - [Coulomb's Law](#coulombs-law)
- [Polarization](#polarization)
  - [Diagram of Charge Polarization](#diagram-of-charge-polarization)
- [Transfer of Charge](#transfer-of-charge)
  - [Types of Charge Transfer](#types-of-charge-transfer)
  - [Diagram of Charge Transfer](#diagram-of-charge-transfer)
- [Electric Field](#electric-field)
  - [Dictionary](#dictionary)
  - [Air](#air)
  - [Diagram of Lightning Charges](#diagram-of-lightning-charges)
- [Discharge, Conductors, and Capacitors](#discharge-conductors-and-capacitors)
- [PollEV Answers](#pollev-answers)

## Electric Forces
- Example
  - `[1]========[2]======->F_21`
  - `Q1         Q2`

### Coulomb's Law
  - $\vec{F}_21^\text{Elctrostatic} = \frac{kq_1q_2}{r_{21}^2} \cdot (\hat{r}_{21})$
    - Where
      - $k = 8.99 \times 10^9 \frac{Nm^2}{C^2}$
      - $q_1, q_2$ are charges equal to $-1.6 \times 10^{-19}C$ per electron ($C$ is a *Coulomb*)
      - $r_{21}$ is the distance between the two charges
      - $\hat{r}_{21}$ is the unit vector pointing from $Q_1$ to $Q_2$
  - $\vec{F}_{21}^\text{Gravity} = \frac{Gm_1m_2}{r_{21}^2} \cdot (-\hat{r}_{21})$ ***Not on the exam***
    - Where
      - $G = 6.67 \times 10^{-11} \frac{m^3}{kg \cdot s^2}$
      - $m_1, m_2$ are masses
      - $r_{21}$ is the distance between the two masses
      - $\hat{r}_{21}$ is the unit vector pointing from $m_1$ to $m_2$

## Polarization
- Polarization is the separation of charges in a material
- An object can be neutrally charged as a whole, but still have an area which is largely positive or negative

### Diagram of Charge Polarization 
![Polarization](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQi_TRZdz1H-OEkqqpTca8DMbfDRZbPY7_WTA&s)

## Transfer of Charge
- Most dissimilar materials are have different electron affinities
  - This causes a transfer of charge when the two materials are brought into contact
- The transfer of charge is due to the difference in electron affinities
  - The material with the higher electron affinity will attract electrons from the material with the lower electron affinity
  - Thus, the material with the higher electron affinity will become negatively charged, and the material with the lower electron affinity will become positively charged

### Types of Charge Transfer
- **Conduction**
  - Transfer of charge through direct contact
  - Example: Rubbing a balloon on your hair
- **Induction**
  - Transfer of charge through electric fields
  - Example: When a negatively charged balloon is brought near a neutral metal sphere, the electrons in the sphere are repelled, causing the near side to become positively charged through induction without direct contact.

### Diagram of Charge Transfer
![Charge Transfer](https://panchbhaya.weebly.com/uploads/1/3/7/0/13701351/charging-by-induction-and-conduction.png?685)

## Electric Field
- The electric field is a vector field that describes the force experienced by a positive test charge at any point in space

### Dictionary
| Feature                             | Static Electricity                                     | Gravity                                          |
|-------------------------------------|--------------------------------------------------------|--------------------------------------------------|
| Force Equation                      | $\vec{F} = k\frac{q_1q_2}{r^2}$                        | $\vec{F} = G\frac{m_1m_2}{r^2}$                  |
| Charge/Mass                         | $q$ is charge                                          | $m$ is mass                                      |
| Potential Energy                    | $U_\text{electrostatic} = k\frac{q_1q_2}{r}$           | $U_\text{gravity} = mgh$                         |
| Voltage/Gravitational Potential     | $V = \frac{U_\text{electrostatic}}{q}$                 | $V_\text{gravity} = gh$                          |
| Field Equation                      | $\vec{E} = -\vec{V} V$ or $\vec{E} = \nabla V$         | $\vec{g} = \frac{Gm}{r^2}$                       |
| Force in Field                      | $\vec{F} = q\vec{E} = -\vec{V} U_\text{electrostatic}$ | $\vec{F} = m\vec{g} = -\vec{V} U_\text{gravity}$ |

- **Force Equation**
  - The force in static electricity (Coulomb's Law) is calculated based on the charges $q_1$ and $q_2$, the distance between them $r$, and the Coulomb constant $k$. It expresses the attractive or repulsive force between two charges.
  - The gravitational force (Newton's Law of Gravitation) depends on the masses $m_1$ and $m_2$, the distance between them $r$, and the gravitational constant $G$. It describes the attractive force between two masses.

- **Charge/Mass**
  - The charge $q$ is the fundamental property of matter in electrostatics, determining how particles interact via electric forces. Charges can be positive or negative, and like charges repel, while opposite charges attract.
  - The mass $m$ is the fundamental property in gravity, determining how strongly objects are attracted to each other. Mass is always positive, and gravitational force is always attractive.

- **Potential Energy**
  - Electrostatic potential energy $U_\text{electrostatic}$ is the energy stored between two charges $q_1$ and $q_2$ separated by a distance $r$. The energy depends on the Coulomb constant $k$ and describes how the configuration of charges affects energy.
  - Gravitational potential energy $U_\text{gravity}$ is the energy stored in an object of mass $m$ at a height $h$ in a gravitational field $g$. It describes the potential energy due to an object's position in a gravitational field.

- **Voltage/Gravitational Potential**
  - Voltage (electric potential) $V$ is the potential energy per unit charge. It describes how much energy a charge will gain or lose when moving through an electric field. It's calculated as the electrostatic potential energy divided by the charge $q$.
  - Gravitational potential is the potential energy per unit mass in a gravitational field. It’s expressed as $gh$, where $g$ is the gravitational field strength and $h$ is the height.

- **Field Equation**
  - The electric field $\vec{E}$ is derived from the potential $V$ by the equation $\vec{E} = -\nabla V$. This equation states that the electric field is the negative gradient of the electric potential, pointing in the direction of decreasing potential.
  - The gravitational field $\vec{g}$ is the force per unit mass and is derived from the source mass $M$ by $\vec{g} = \frac{GM}{r^2}$. It describes the strength and direction of the gravitational force experienced by a mass at a distance $r$ from the source mass.

- **Force in Field**
  - The force on a charge $q$ in an electric field $\vec{E}$ is given by $\vec{F} = q\vec{E}$. The term $-\vec{V} U_\text{electrostatic}$ might have been used to represent the interaction between the charge and potential in shorthand, though it should typically be written in terms of the gradient of the potential.
  - The force on a mass $m$ in a gravitational field $\vec{g}$ is given by $\vec{F} = m\vec{g}$. The expression $-\vec{V} U_\text{gravity}$ could be shorthand for the interaction between the gravitational field and the potential energy, though typically it is expressed as $mgh$.

### Air
- The air is a dielectric material that can be polarized by an electric field
  - Dielectric materials are insulators that can be polarized by an electric field
- The makeup of air is
  - 78% Nitrogen
  - 21% Oxygen
  - 1% Argon and other gases
- Lightning happens when the air is ionized by a strong electric field
  - When $E > 3 \times 10^6 \frac{V}{m}$, the air is ionized and conducts electricity

### Diagram of Lightning Charges
![Lightning](https://cdn.britannica.com/78/7578-050-1A948331/charges-regions-thundercloud-charge-lightning-discharge-others.jpg)

## Discharge, Conductors, and Capacitors
- **Discharge**
  - The release of stored energy in a capacitor
  - The energy is released as heat and light
- **Conductors**
  - Materials that allow the flow of charge
  - The charges are free to move within the material
  - Inside a conductor, $\vec{E} = 0$
    - This is because the charges are free to move and will move to cancel out any electric field
    - Also why during lightning, it is a good idea to be inside a car because the metal shell will conduct the charge around you meaning you won't get fried
- **Capacitors**
  - Devices that store energy in an electric field

###### PollEV Answers
- *A* **Attract one another**
  - If I stick two pieces of (identical) plastic tape together, one above the other, and then peel them apart, they will...
    - When two pieces of plastic tape are stuck together and then peeled apart, one piece typically becomes positively charged, and the other becomes negatively charged due to the transfer of electrons. As a result, the two pieces develop opposite charges, which means they will attract each other due to electrostatic forces.
- *D* **Distributed near the exterior surface of the ball**
  - If you put net electric charge on a solid metal (conducting) ball, itself electrically insulated from the environment, where will the excess charge go?
    - In a conductor, excess charge always resides on the outer surface. This is because the charges repel each other and seek to maximize their distance from one another, which results in them distributing themselves on the surface of the conductor.
