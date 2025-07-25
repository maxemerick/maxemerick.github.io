---
permalink: /research/
title: "Research"
author_profile: true
redirect_from:
  - /research.html
---

My current research centers around mathematical methods for analysis and control of density-based systems. These could be densities of particles immersed in a fluid, probability densities arising from stochastic processes, or density approximations of very-large-scale systems. Analyzing and manipulating these sorts of systems is challenging because they are typically nonlinear and have an infinite number of degrees of freedom. My research aims to develop mathematical methods which leverage structure in these systems to make their analysis and control more tractable.

Below is a short description of current and past research projects. Publications are listed under the project they are associated with. All publications can be found at my [Google Scholar](https://scholar.google.com/citations?user=CN7oYBQAAAAJ&hl=en).


Tracking Control in Wasserstein Space
----------
In many settings in swarm robotics, it is desirable that a swarm of robots continuously "track" (i.e. follow) a given entity as it changes. For example, data collection robots may need to track points-of-interest as they move around, fire-fighting drones may need to track a fire as it evolves, and fleets of autonomous taxis may need to track "rider demand" as it shifts throughout the day. One natural setting in which to investigate this behavior is the so-called "Wasserstein space" of optimal transport theory, which is able to effectively capture spatial discrepancies between swarm and target densities. This project aims to understand efficient motion and tracking control in this space, and use this understanding to develop better predictive models, numerical algorithms, and control schemes.


“Optimal Assignment and Motion Control in Two-Class Continuum Swarms,” \
**M. Emerick,** S. Patterson, and B. Bamieh, IEEE Transaction on Control of Network Systems. In review.

“Causal Tracking of Distributions in Wasserstein Space: A Model Predictive Control Scheme,” \
**M. Emerick,** J. Jonas, and B. Bamieh, 63rd IEEE Conference on Decision and Control, pp. 7606-7611, 2024.

“Continuum Swarm Tracking Control: A Geometric Perspective in Wasserstein Space,” \
**M. Emerick** and B. Bamieh, 62nd IEEE Conference on Decision and Control, pp. 1367-1374, 2023.

“Optimal Combined Motion and Assignments with Continuum Models,” \
**M. Emerick,** S. Patterson, and B. Bamieh, IFAC-PapersOnLine, vol. 55, no. 13, pp. 121-126, 2022.



Incompressible Fluid Mixing
----------
In many engineering applications it is important to be able to mix two fluids efficiently. In combustion engines one needs to mix fuel and air, in chemical process such as polymer production one needs to mix monomers and reactacts, and in lab-on-chip applications one needs to mix samples and reagents. While there are many heuristics for what makes a flow field good at mixing, we do not have a complete mathematical understanding of this behavior. This projects aims to characterize maximally efficient mixing fields, thereby giving us a better mathmatical understanding of mixing and helping us to design machines and protocols which can mix more effectively.


“Incompressible Optimal Transport and Applications in Fluid Mixing,” \
**M. Emerick** and B. Bamieh, 64th IEEE Conference on Decision and Control. In review.



Boundary-Layer Data Systems
----------
My undergraduate research focused on designing mechatronic devices for making real-time measurements of boundary layers on aircraft. These devices were designed to fit in low-profile, adhesive-mountable, and fully self-contained packages while maintaining high accuracy in the extreme environments encountered at altitude. I worked on three devices during my tenure in the lab: the "Pressurewing-I" and "Pressurewing-II", multi-sensors built on Adafruit's Feather platform, providing up to ten independent boundary layer measurements in addition to temperature/pressure, and the "BLDS-T", a large-scale distributed temperture-sensor network for thermal mapping ([news article](https://ceng.calpoly.edu/connection/2019/10/cal-poly-autonomous-flight-lab-conducts-first-flight-of-next-generation-flight-test-data-system/)).


