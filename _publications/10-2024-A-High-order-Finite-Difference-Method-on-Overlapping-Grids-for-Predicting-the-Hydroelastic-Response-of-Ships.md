---
title: "A High-order Finite Difference Method on Overlapping Grids for Predicting the Hydroelastic Response of Ships"
collection: publications
category: books
permalink: /publication/A-High-order-Finite-Difference-Method-on-Overlapping-Grids-for-Predicting-the-Hydroelastic-Response-of-Ships
year: 2024
venue: "Technical University of Denmark"
paperurl: 'https://findit.dtu.dk/en/catalog/6675796ca83eb417d322c154'
citation: 'Zhou, B. (2024). A High-order Finite Difference Method on Overlapping Grids for Predicting the Hydroelastic Response of Ships. Technical University of Denmark.'
---

## Abstract
This PhD thesis presents a numerical solution of the hydroelastic problems encountered especially by large flexible ships sailing in waves. The solution is implemented by extending an existing seakeeping tool (OceanWave3D-seakeeping) to allow for the efficient and accurate evaluation of the hydroelastic response of ships. OceanWave3D-seakeeping has been developed by the Maritime Group at DTU-Construct based on solving the linearized potential flow theory using high-order finite differences on overlapping curvilinear boundary-fitted grids. Modal superposition is employed to couple the hydrodynamic and structural analysis of ships at both zero and non-zero forward speed. The ship girder is approximated by an Euler-Bernoulli or a Timoshenko beam, and the vertical bending deformation is mainly considered in this work. The shear effects on the hydroelastic response are also investigated in the Timoshenko beam approximation. The solution has been validated against experimental measurements and reference numerical solutions for several test cases. The correct computation of the hydrostatic stiffness, structural stiffness and hydrodynamic forces is the key to the
accurate prediction of the hydroelastic response, and these three terms are discussed deeply in this thesis.

With respect to the hydrostatic stiffness model, some controversy has long existed in the literature about its correct form for elastic motion modes, with Newman [1] and Malenica [2] arriving at different forms which are respectively defined in earthand body-fixed reference systems. In this thesis a complete derivation of both forms including the buoyancy and gravitational terms is provided, and the equivalence of the two models associated with elastic motions is confirmed.

A finite element method (FEM) is a common way to compute the structural stiffness of ship hulls. However, for large modern ships, a FEM calculation based on a full structure is inevitably time-consuming since distinguished differences between the longitudinal and the cross-sectional scales of ship hulls usually exist, and the sectional configurations are generally complex, bringing difficulties to numerical modeling. Considering that the structure of modern ships (for example container ships), is usually nearly periodic in the longitudinal direction, in this thesis the ship hull is approximated as a periodic beam and a new implementation of asymptotic homogenization (NIAH) is introduced to efficiently calculate the structural stiffness. This can greatly improve the computational efficiency compared with a full FEM model. Several test cases with both solid and thin-walled sections are given to validate the proposed technique. A range of representative mid-ship sections for a container ship are also considered to investigate the influence of stiffeners on the hydroelastic response.

In the hydrodynamic part, zero-speed and forward-speed radiation and diffraction problems including the well-known m−terms in the body boundary conditions, have both been solved. For generalized modes, the boundary conditions using the corresponding generalized m−terms are applied in the calculation. Neumann-Kelvin (NK) and double-body (DB) linearization models are applied as the steady base flow, and their performance is investigated by comparison with experimental measurements. In head seas, the influence of increasing forward speed on the resonant response of the flexible modes is also studied.

Through the integration of hydroelastic analysis using potential flow theory, and advanced numerical techniques, this thesis contributes to a deeper understanding of the complex interaction between flexible ship hulls and ocean waves, offering valuable insights for the maritime industry.

## Keywords
- Overlapping Grid
- High-order Finite Difference
- Hydroelastic Response
- Hulls (Ships)
- Finite Difference Method
