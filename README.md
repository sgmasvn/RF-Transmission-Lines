### RF-Transmission-Lines
* Challenge in RF Circuits as to how best to connect two wires together
* RF Circuits can be connected using Tranmission Lines
* In the past, Transmission Lines Design and Calculations were done using Maxwell Equations
* Maxwell Equations being 3-D equations required complex Multivariable Calculus -
**Transmission Line Theory** is a less complex(1-D) way to solve Transmission Line calculations
* Planar Circuits/Microstrip/CPW

* TEM wave - Plane wave confined to a Volume - wherein we can define a Voltage (No multi-mode propagation allowed)
* Lossless 
* Disperson Free -All waves irrespective of **Frequency** propagate at **Same Velocity**. If not, then waves propagating at different speeds will result in group-delay.



### Ideal Transmission Line -
* Transmission line segment - is broken down into smaller segments - delta(Z).
* delta(Z) much more smaller than wavelength
* Using Maxwell Laws - the delta(Z) segment can be transformed into a lumped-element model (as shown below)

R --> 0, and G --> infinity
![Transmission Line](https://github.com/sgmasvn/RF-Transmission-Lines/blob/main/Transmission.png)
* R  is measured in ohm/m
* L  in H/m
* C  in F/m
* G is the conductivity - which arises due to the dielectric

R --> 0, and G --> infinity
![LossLess](https://github.com/sgmasvn/RF-Transmission-Lines/blob/main/Lossless.png)
