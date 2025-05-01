
## Page 1



PART I: THERMODYNAMICS & ENERGY BALANCES

Mass and Volumetric Flow Rates

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
