# Lecture 1 (Math Review)
### Avi Herman
### 9/9/2024

## Table of Contents
- [Symbols & Notation](#symbols--notation)
- [Exponents](#exponents)
  - [Properties](#properties)
- [Scientific Notation & E Notation](#scientific-notation--e-notation)
  - [Operations](#operations)
  - [Addition/Subtraction](#additionsubtraction)
- [Units](#units)
  - [Conversion example](#conversion-example)
  - [Metric System Prefixes](#metric-system-prefixes)
- [Numerical Precision](#numerical-precision)
- [Trigonometry](#trigonometry)
  - [Radians vs Degrees](#radians-vs-degrees)
- [Proportional Relationships](#proportional-relationships)
- [Order-of-Magnitude Estimation](#order-of-magnitude-estimation)
- [Gravitational Law](#gravitational-law)
  - [Proportionality of Force](#proportionality-of-force)
- [Vector Math](#vector-math)
  - [Vector Notation](#vector-notation)
  - [Vector Addition](#vector-addition)
  - [Scalar Multiplication](#scalar-multiplication)
  - [Dot Product](#dot-product)
  - [Cross Product](#cross-product)
  - [Magnitude of a Vector](#magnitude-of-a-vector)
  - [Unit Vector](#unit-vector)
  - [Vector Example](#vector-example)

---

## Symbols & Notation
| Symbol    | Meaning                |
|-----------|------------------------|
| $=$       | Equals                 |
| $\neq$    | Not equal              |
| $\propto$ | Proportional to        |
| $E$       | Exponent value         |
| $\ldots$  | Continued series       |

---

## Exponents

Exponents (or powers) are shorthand for repeated multiplication. For instance:
- $a^2 = a \times a$ ("a squared")
- $a^3 = a \times a \times a$ ("a cubed")
- $a^n = a \times a \times \cdots \times a$ ("n times")

Rules for exponents:
- $a^1 = a$
- $a^0 = 1$
- $a^{-n} = \frac{1}{a^n}$

Example powers of 10:
- $10^6 = 1,000,000$
- $10^{-3} = 0.001$

### Properties:
1. $a^m \times a^n = a^{m+n}$
2. $\frac{a^m}{a^n} = a^{m-n}$
3. $(a^m)^n = a^{m \times n}$

---

## Scientific Notation & E Notation

Scientific notation simplifies large/small numbers by expressing them as a small number multiplied by a power of 10. For example:
- $3.56 \times 10^3$ becomes $3.56E+3$
- $7.87 \times 10^{-4}$ becomes $7.87E-4$

### Operations:
- **Multiplication:** $(2.5 \times 10^3) \times (4.3 \times 10^5) = (2.5 \times 4.3) \times 10^{3+5} = 10.75 \times 10^8 = 1.075 \times 10^9$
- **Division:** $\frac{4.3 \times 10^5}{2.5 \times 10^3} = \frac{4.3}{2.5} \times 10^{5-3} = 1.72 \times 10^2$

### Addition/Subtraction:
To add or subtract in scientific notation, first convert all numbers to the same power of 10:
- $4.3 \times 10^5 - 2.5 \times 10^3 = 4.3 \times 10^5 - 0.025 \times 10^5 = (4.3 - 0.025) \times 10^5 = 4.275 \times 10^5$

---

## Units

Units are essential for expressing physical quantities, and errors in unit specification lead to significant issues. Common SI units:
- **Length:** $1 \, km = 10^3 \, m$, $1 \, cm = 10^{-2} \, m$
- **Mass:** $1 \, g = 10^{-3} \, kg$, $1 \, mg = 10^{-6} \, kg$
- **Time:** $1 \, ns = 10^{-9} \, s$

### Conversion example:
To convert 1 cm to nanometers:
$1 \, cm = 10^{-2} \, m = 10^7 \, nm$

### Metric System Prefixes:
- **Tera (T):** $1 \, T = 10^{12}$
- **Giga (G):** $1 \, G = 10^9$
- **Mega (M):** $1 \, M = 10^6$
- **Kilo (k):** $1 \, k = 10^3$
- **Centi (c):** $1 \, c = 10^{-2}$
- **Milli (m):** $1 \, m = 10^{-3}$
- **Micro (\mu):** $1 \, \mu = 10^{-6}$
- **Nano (n):** $1 \, n = 10^{-9}$
- **Pico (p):** $1 \, p = 10^{-12}$

---

## Numerical Precision

Precision is critical when dealing with empirical data. 
- **Significant figures**: Only write digits that are meaningful and supported by the measurement's precision.
- Example: The dinosaurs were killed off **about** $6.5 \times 10^7$ years ago, not exactly $6.50 \times 10^7$ years.

To specify a number with an uncertainty:
- Example: $1.364 \pm 0.003$ implies the true value is between $1.361$ and $1.367$.

---

## Trigonometry

For a right triangle:
- $\sin \phi = \frac{opposite}{hypotenuse}$
- $\cos \phi = \frac{adjacent}{hypotenuse}$
- $\tan \phi = \frac{opposite}{adjacent}$

Mnemonic: **SOH-CAH-TOA**

Example:
- If $a = 4 \, cm$, $b = 3 \, cm$, and $c = 5 \, cm$, then $\sin \phi = \frac{3}{5} = 0.6$

### Radians vs Degrees:
$360^\circ = 2\pi$ radians. Therefore, $1$ radian = $\frac{360^\circ}{2\pi} \approx 57.296^\circ$.

---

## Proportional Relationships

Relationships between variables often take proportional forms:

- **Direct Proportion:** $a \propto b$
  - Example: The interest paid on a bank account is directly proportional to the balance.
  
- **Inverse Proportion:** $a \propto \frac{1}{b}$
  - Example: If the length of a guitar string doubles, its frequency is halved.
  
- **Square Proportion:** $a \propto b^2$
  
- **Inverse Square Proportion:** $a \propto \frac{1}{b^2}$

Proportionality can be written as an equation with a constant:
- Example: $f = \frac{C}{\ell}$, where $f$ is frequency, $\ell$ is string length, and $C$ is a constant depending on string tension and density.

---

## Order-of-Magnitude Estimation

In physics, estimates are often good enough for practical purposes. The goal is to get the **order of magnitude** right, not exact values.

Example: Estimating the number of piano tuners in New York City.
- NYC population = $8$ million.
- Estimate: $1$ piano for every $100$ people $\Rightarrow 80,000$ pianos.
- Each tuner tunes 500 pianos per year $\Rightarrow 160$ tuners needed.

---

## Gravitational Law

Newton's law of universal gravitation:
$F = G \frac{m_1 m_2}{d^2}$

Where:
- $F$ is the gravitational force,
- $G$ is the gravitational constant,
- $m_1$ and $m_2$ are the masses of the two objects,
- $d$ is the distance between them.

### Proportionality of Force:
- **Proportional to mass**: $F \propto m_1$, $F \propto m_2$.
- **Inverse-square relation to distance**: $F \propto \frac{1}{d^2}$.

Example:
- If the Earth-moon distance were halved, the gravitational force would increase by a factor of $4$ due to the inverse-square law.


---

## Vector Math

Vectors are quantities that have both magnitude and direction. They are often represented as arrows in a coordinate system.

### Vector Notation
- A vector can be written as **v** or \(\vec{v}\).
- In component form: \(\vec{v} = \langle v_x, v_y, v_z \rangle\).

### Vector Addition
- To add two vectors, add their corresponding components:
  $$
  \vec{u} + \vec{v} = \langle u_x + v_x, u_y + v_y, u_z + v_z \rangle
  $$

### Scalar Multiplication
- To multiply a vector by a scalar, multiply each component by the scalar:
  $$
  c \cdot \vec{v} = \langle c \cdot v_x, c \cdot v_y, c \cdot v_z \rangle
  $$

### Dot Product
- The dot product of two vectors is a scalar:
  $$
  \vec{u} \cdot \vec{v} = u_x v_x + u_y v_y + u_z v_z
  $$

### Cross Product
- The cross product of two vectors is another vector:
  $$
  \vec{u} \times \vec{v} = \langle u_y v_z - u_z v_y, u_z v_x - u_x v_z, u_x v_y - u_y v_x \rangle
  $$

### Magnitude of a Vector
- The magnitude (or length) of a vector \(\vec{v}\) is:
  $$
  |\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}
  $$

### Unit Vector
- A unit vector has a magnitude of 1 and points in the same direction as the original vector:
  $$
  \hat{v} = \frac{\vec{v}}{|\vec{v}|}
  $$

### Vector Example
- Given \(\vec{a} = \langle 2, 3, 4 \rangle\) and \(\vec{b} = \langle 1, 0, -1 \rangle\):
  - \(\vec{a} + \vec{b} = \langle 3, 3, 3 \rangle\)
  - \(2 \cdot \vec{a} = \langle 4, 6, 8 \rangle\)
  - \(\vec{a} \cdot \vec{b} = 2 \cdot 1 + 3 \cdot 0 + 4 \cdot (-1) = -2\)
  - \(\vec{a} \times \vec{b} = \langle 3 \cdot (-1) - 4 \cdot 0, 4 \cdot 1 - 2 \cdot (-1), 2 \cdot 0 - 3 \cdot 1 \rangle = \langle -3, 6, -3 \rangle\)
  - \(|\vec{a}| = \sqrt{2^2 + 3^2 + 4^2} = \sqrt{29}\)
  - \(\hat{a} = \frac{\vec{a}}{\sqrt{29}} = \langle \frac{2}{\sqrt{29}}, \frac{3}{\sqrt{29}}, \frac{4}{\sqrt{29}} \rangle\)

---
