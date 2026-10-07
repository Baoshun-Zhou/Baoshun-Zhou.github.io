---
title: "Hydroelastic solutions using a high-order finite difference method based on the mode functions of a Timoshenko beam"
collection: publications
category: conferences
permalink: /publication/Hydroelastic-solutions-using-a-high-order-finite-difference-method-based-on-the-mode-functions-of-a-Timoshenko-beam
year: 2023
venue: "23rd Nordic Maritime Universities Workshop"
paperurl: 'https://findit.dtu.dk/en/catalog/640b8c8f59a40f3a3e977227'
citation: 'Zhou, B., Amini Afshar, M., Bingham, H. B., & Shao, Y. (2023). Hydroelastic solutions using a high-order finite difference method based on the mode functions of a Timoshenko beam. Abstract from 23rd Nordic Maritime Universities Workshop, Göteborg, Sweden.'
---

## Abstract
This work is part of the ongoing implementation of hydroelastic solution for ships inside the Ocean Wave3D-seakeeping code. This solver has been developed by the Maritime Group at DTU Department of Civil and Mechanical Engineering based on linearized potential flow theory [1, 2, 3, 4, 5]. The numerical implementation has been conducted on overlapping grids using a high-order finite difference method. A Fast Fourier Transform (FFT) has been employed to transform the
time-domain hydrodynamic solutions to frequency-domain solutions. A pseudo-impulse tailored to the desired frequency range is used as the forcing for the time-domain solution. In previous work [5], a preliminary implementation of hydroelastic solutions was implemented in OceanWave3D-seakeeping with an Euler-Bernoulli beam model to represent the eigenmodes of the flexible ship hull. However, shear effects are ignored by this beam theory, even though the shear effect is very important to acurately predict the structural deformation especially for a thick beam model. In this work, ship hulls have been treated using the Timoshenko beam model including shear effects. The influence of shear effects are also discussed through a couple of numerical test cases. Good agreement with reference solutions illustrates the effectiveness of the numerical implementation. The current work focuses on zero speed, and work is also in progress to validate
the implementation at forward speeds.

## Keywords
- Hydroelastics
- Generalized Modes
- Ships
- Timoshenko Beam
- Shear Effect
