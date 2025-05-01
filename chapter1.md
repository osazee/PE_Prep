## Mass and Volumetric Flow Rates

Units, Dimensions, and Dimensional Homogeneity

Before we embark on our discussion of engineering thermodynamics, we need to address the topic of units,
dimensions, unit conversions, and dimensional homogeneity. A lack of familiarity with unit conversions is one of
the biggest hindrances to success in the P.E. exam. The purpose of this section is to describe our recommended
approach to avoid the common pitfalls encountered during the solution of exam-style problems.

Physical quantities require quantitative descriptions when solving engineering problems. Consider the density as
one such quantity. It is a measure of the mass contained in a unit volume. However, density is not considered a
“fundamental” dimension. Only length, mass, time, temperature plus five more’ are fundamental. All other
quantities (e.g. volume, energy, power, etc.) can be expressed in terms of fundamental dimensions. For
instance, the dimensions of force can be related to the fundamental dimensions of mass, length, and time. To

give the dimensions of a quantity a numerical value, a set of units must be selected.

Two sets of units are in common use today: the United States Customary System (USCS), and the SI (from the
french name Le Systéme International d’ Unités).2° The SI is a logical and simple system based on a decimal
relationship between the various units. The English system, however, has no apparent systematic numerical
base, and various units in this system are related to each other rather arbitrarily (1ft=12in, 1ton=2,000Ib,
1 pint=160z, etc.).

In SI, the units of mass, length, and time are the kilogram (kg), meter (m), and second (s), respectively. The
respective units in the USCS are the pound-mass (Ibm), foot (ft), and second (s). The force unit in SI is the
newton (N), and it is defined as the force required to accelerate a mass of 1 kg at a rate of 1 m/s*. In the USCS,
the force unit is the pound-force (Ibf) and is defined as the force required to accelerate a mass of 32.174 lbm (1
slug) at a rate of 1 ft/s*. That is,

1N=1kg·m/s² and 1 Ibf=32.174 Ibm·ft/s²

1 The others are electric current, luminous intensity, plane angle, solid angle, and amount of substance.  
2. The USCS is practically the same as the English System and the Imperial System.  
3. The SI system is also known as the International System. It is practically the same as the “metric” system.

---

## Page 2



The term weight is often incorrectly used to express mass. Unlike mass, weight W is a force. It is the
gravitational force applied to a body, and its magnitude is determined from Newton's second law,

W = mg (1-1)

where m is the mass of the body, and g is the local gravitational acceleration. For most practical purposes, the
gravitational acceleration g can be assumed to be constant at 9.81 m/s², or 32.2 ft/s².

We are familiar with the magnitude of one pound-force; think of the last time you got a “pound” of cheese at the
grocery store. A pound-force is also roughly the weight of three avocados. The magnitude of one newton is
approximately one-fourth of a pound-force. The mass of a body is independent of its location. In contrast, the
weight changes with a change in gravitational acceleration. A body weighs less on top of a mountain because g
decreases with altitude. On the surface of Mars, an object weighs about 40% of what it normally weighs on
earth. The primary cause of confusion between mass and weight is that mass is usually measured indirectly by
measuring the weight.

Work, which is a form of energy, can simply be defined as force times distance; therefore, it has the unit
“newton-meter” (N-m), which is called a joule (J). That is,

1 J = 1 N·m  
A more common unit for energy in SI is the kilojoule (1 kJ = 10³ J). In the USCS, the energy unit is the Btu (British
thermal unit), which is defined as the energy required to raise the temperature of 1 lbm of water at 68°F by 1°F.
Owing to its definition as force times displacement, another unit for energy in the USCS is the foot pound-force
(ft-lbf).

All equations must be dimensionally homogeneous. That is, every term in an equation must have the same
units. If at some stage of an analysis, you find yourself in a position to add two quantities that have different
units, it is a clear indication that something went wrong at an earlier stage. Therefore, checking dimensions is a
valuable tool to spot errors. We strongly encourage you to always keep track of units and never, ever, write down
a number without its accompanying units. Carelessness with units and unit conversions can make the difference
between passing and failing the P.E. exam.

Unity conversion ratios are identically equal to 1 and are unit-less, and thus such ratios (or their inverses) can
be inserted conveniently into any calculation to properly convert units, because any quantity multiplied (or
divided) by 1 remains unchanged. For example, the quantity:

1 lbf / 32.174 lbm·ft/s²

---

## Page 3

is a ratio of two quantities that are identical, so it is equal to 1. Likewise, quantities such as:

12 in / 1 ft, 7.481 gal / 1 ft³, 6.895 kPa / 1 psi, 448.83 gpm / 1 ft³/s

are all identically equal to 1 and are frequently inserted into calculations to ensure the dimensional homogeneity
of equations. Some books insert the archaic gravitational constant gc, defined as gc = 32.174 lbm·ft/lbf·s² into
equations in order to force units to match. This practice leads to unnecessary confusion and is strongly
discouraged. We recommend you instead use unity conversion ratios.

When we say that equations must be dimensionally homogeneous, we mean that the dimensions of the left side
of the equation must be the same as those on the right side, and all additive separate terms must have the same
dimensions. We accept as a fundamental premise that all equations describing physical phenomena must be
dimensionally homogeneous. If this were not true, we would be attempting to equate or add unlike physical
quantities, which would not make sense. For example, the equation for the velocity, V, of a uniformly accelerated
body is:

V = V₀ + at

Here we note that the dimensions of all three terms are length/time — thus, the equation is dimensionally
homogeneous.

To illustrate the use of unity conversion ratios consider this example (formatted in “PE style"):

*Example:*  
The velocity (inches per second) at t = 0.25 min if the initial velocity V₀ = 50 ft/min and  
a = 0.85 ft/s² is most nearly:  
(A) 71.3  
(B) 163  
(C) 815  
(D) 9780

*Wrong approach:*  
V = V₀ + at = 50 + 0.85 × 0.25 = 71.25 → picks (A), incorrect due to unit mismatch

*Another common mistake:*  
Fails to fully convert time and gets 815, which is close to (C) but wrong in units.


## Page 4

Note the use of the unity conversion factor on the second term (highlighted in blue), to ensure consistency of
units for the calculation. Note that "815" is one of the answer choices. However, the question specifies the units
of the answer must be in inches per second. Choosing (C) 815, would be wrong — even though the answer is
correct! We leave it as an exercise for you to confirm that the correct answer is (B).

The PEMH contains a unit conversion table under the heading “Measurement Relationships". Here we discuss
how to use this table to build unity conversion factors. The table has columns labeled “Multiply”, “by”, and “to
Obtain". The row for British Thermal Unit (Btu) reads:

Multiply by to Obtain  
Btu 778 ft-lbf

Therefore, if you need to express say 1,500 Btu in ft-lbf you would multiply 1,500 times 778 to obtain 1,500 Btu =
1,167,000 ft-lbf. This same table can be used to build unity conversion factors that can be conveniently inserted
in calculations. The row in question can be interpreted as stating that 1Btu = 778 ft-lbf. Therefore, the following
ratios:

1Btu / 778 ft-lbf or 778 ft-lbf / 1Btu

can be inserted anywhere we need them. For example consider the following equation:  
e = u + Pv + V² / 2

---

## Page 5

Ibf  ft² Ibf ft² | 1Btu Btu ft²  
50×65 lbm ~ ... and now we need another unity conversion factor to express this term in Btu/lbm:  
Btu ft² _ Btu ft² | 12in² _ Btu  
0.3856 ... = 55.53 Btu/lbm

Now for the third term on the right hand side,  
1 ft² _ ft² 1 Ibf _ ft-lbf 1Btu _ Btu  
= 0.0025 Btu/lbm

Now that all terms are written in consistent units, we can add them:  
e = 1,500 + 55.53 + 0.0025 = 1,555.53 Btu/lbm

Some valid equations contain constants with dimensions. For example:  
d = 16.1 t²

This equation is actually a particular case of:  
d = (1/2) g t²  
Valid for g = 32.2 ft/s², so d = 16.1 t² only works in ft, s

---

## Page 6

Problems

1-01. The energy per unit mass of a stream of fluid, e, is given by:  
e = u + Pv + V² / 2  
Find pressure P in lbf/in² for:  
u = 1,500 Btu/lbm,  
e = 1,620 Btu/lbm,  
v = 6 ft³/lbm,  
V = 400 ft/s

1-02. Same formula:  
Find e in kJ/kg for:  
u = 3,100 kJ/kg,  
P = 3 MPa,  
v = 0.1 m³/kg,  
V = 120 m/s

1-03. For V = Z(α - 1) + G, determine dimensions of Z, α, G.

1-04. Given:  
Δp = K₁(μV/D) + K₂[(A₀ - A₁)/A₀]² (ρV²/2)  
Find SI dimensions of K₁ and K₂.


## Page 7

1-05. The Weber number is a dimensionless parameter, given by:

We = (ρV²L) / σ

where ρ is density, V is a velocity, L is a length, and σ is a material property of the fluid. Since the Weber
number is dimensionless, the units of σ must be:

(A) lbm/(ft·s)  
(B) lbf/ft  
(C) ft/lbf  
(D) s²/lbm

---

1-06. A formula to estimate the volume rate of flow Q over a dam of length B is:

Q = 3.09 B H³ᐟ² (in ft³/s where B, H are in feet)

What is the equivalent in gallons per day (gpd)?

(A) Q = 0.00027 B H³ᐟ²  
(B) Q = 0.413 B H³ᐟ²  
(C) Q = 36,000 B H³ᐟ²  
(D) Q = 2 × 10⁶ B H³ᐟ²

---

1-07. To calculate a force:

F = mV + pA  
where:  
m = 600 kg/min  
V = 2 m/s  
p = 29.7 kPa  
A = 50.3 cm²

What is F (N)?

(A) 35  
(B) 169  
(C) 1513  
(D) 2694

---

## Page 8

1-08. Flow rate Q = F / (ρV)  
F = 35 lbf  
ρ = 6.26 lbm/gallon  
V = 15 ft/s  
Q in cubic feet/hour:

(A) 0.373  
(B) 12  
(C) 5,775  
(D) 43,172

---

1-09. Water (ρ = 62.4 lbm/ft³) at 300 gpm in 4" schedule-40 pipe (ID = 4.026").  
Find average flow velocity in ft/s.

1-10. Same as 1-09.  
Find mass flow rate in lbm/hr.

1-11. Steam (v = 5 ft³/lbm) at 500 ft/s in 4" schedule-40 pipe (ID = 4.026").  
Find mass flow rate in lbm/hr.

1-12. Volumetric flow rate of steam in CFM (from above).

1-13. Air flow: 3,000 CFM at 2,200 ft/min in circular duct.  
Find duct diameter (inches).

1-14. In a 3" ID pipe:  
Compare 300 gpm water vs. 300 lbm/h steam (v = 7 ft³/lbm).  
Which has higher velocity?

---

## Page 9

Solutions

1-01. Solve for Pv:  
Pv = e - u - V²/2  
e = 1620 Btu/lbm  
u = 1500 Btu/lbm  
V²/2 = (400²)/2 = 80,000 ft²/s²  
→ convert using:  
80,000 ft²/s² × 1 lbf × 1 ft / (778 ft·lbf/Btu × 1 lbm) ≈ 102.9 Btu/lbm  
Pv = 1620 - 1500 - 102.9 = 17.1 Btu/lbm  
P = Pv/v = 17.1 / 0.163 ≈ 105.3 lbf/in²

---

1-02.  
u = 3100 kJ/kg  
Pv = 3 MPa × 0.1 m³/kg = 300 kJ/kg  
V²/2 = 120² / 2000 = 7.2 kJ/kg  
e = 3100 + 300 + 7.2 = 3407.2 kJ/kg

---

1-03. From V = Z(α - 1) + G  
V → [L/T]  
G → [L/T]  
α → dimensionless  
Z → [L/T]

## Page 10

1-04. Each term in the equation has units of pressure.

Δp = K₁ (μV/D) + K₂ [(A₀ - A₁)/A₀]² (ρV²/2)

- The area ratio is dimensionless.
- The remaining terms have pressure units.
- Therefore:
  - K₁ is dimensionless
  - K₂ is dimensionless

---

1-05. Correct answer: (B)

To keep the Weber number dimensionless:

We = (ρV²L) / σ

So σ must have the same units as ρV²L, which are force per unit length → lbf/ft.

---

## Page 11

1-06. Correct answer: (D)

Convert Q = 3.09 B H³ᐟ² from ft³/s to gallons/day:

1 ft³ = 7.481 gallons  
1 day = 86,400 s

Q = 3.09 × 7.481 × 86400 = 1,997,119 B H³ᐟ²

Closest match → D. Q = 2×10⁶ B H³ᐟ²

---

1-07. Correct answer: (B)

F = mV + pA  
m = 600 kg/min → 10 kg/s  
V = 2 m/s  
p = 29.7 kPa  
A = 50.3 cm² = 0.00503 m²

F = (10)(2) + (29,700)(0.00503)  
= 20 + 149.4 = 169.4 N

---

1-08. Correct answer: (D)

Q = F / (ρV)  
F = 35 lbf → converted to ft·lbf/s  
ρ = 6.26 lbm/gallon  
V = 15 ft/s  
Final result: Q ≈ 43,172 ft³/hr

---

## Page 12

1-11. Steam mass flow rate

Given:  
v = 5 ft³/lbm  
V = 500 ft/s  
Pipe ID = 4.026 in → Area A = πD²/4 ≈ 0.0883 ft²

ṁ = AV / v = 0.0883 × 500 / 5 = 8.83 lbm/s = 31,826 lbm/hr

---

1-12. Volumetric flow rate

Q = ṁ × v = 8.83 × 5 = 44.15 ft³/s = 2649 ft³/min

---

1-13. Duct diameter

Q = 3000 CFM  
V = 2200 ft/min  
A = Q / V = 1.364 ft²  
D = √(4A/π) ≈ 1.33 ft = 15.8 in

---

1-14. Velocity comparison

*Water*  
Q = 300 gpm = 40.1 ft³/min  
D = 3 in → A = 0.0491 ft²  
V = Q / A = 817 ft/min

*Steam*  
ṁ = 300 lbm/h = 5 lbm/min  
v = 7 ft³/lbm  
Q = ṁ × v = 35 ft³/min  
V = Q / A = 713 ft/min

*Conclusion:* Water flows faster than steam.
