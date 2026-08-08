---
permalink: /research/
title: "Research"
author_profile: true
redirect_from:
  - /research.html
---

My research focuses on developing mathematical tools for the modeling, analysis, and control of continuum models of large-scale systems.

Large-scale systems are ubiquitous in the modern world: transportation and social networks, power grids, financial markets, biological and artificial neural networks, human and animal populations, robotic swarms, and the Internet of Things, to name a few. These systems play an enormous role in shaping our everyday lives, yet we do not have anything close to a general theory of behavior for these systems. The central challenge is that these systems are simply too large to analyze using classical methodologies. While numerical and data-driven approaches do play an important role, they struggle to provide interpretable, structural insights. This sort of insight is needed -- if not for the analysis or manipulation of these systems -- for their *design*.

One approach to getting a handle on the complexity of these systems is to model them as *continua*, treating them as one continuous medium as opposed to a large collection of individual components. These continuum models provide a more analytically tractable and scale-invariant way to study these systems. My research draws from a wide array of tools in mathematics (partial differential equations, optimal transport, geometric/variational methods), physics (continuum and statistical mechanics), and engineering (control theory) in order to understand these continuum models and develop methods that can be applied towards the design, analysis, and control of real systems.

Below is a short description of my current and past research projects. Publications are listed under the project they are associated with. All publications can be found at my [Google Scholar page](https://scholar.google.com/citations?user=CN7oYBQAAAAJ&hl=en).



Distributed Control of Continuum Systems
----------
Description here


"On Distributed Control of Continuum Swarms: Local Controllers as Differential Operators,"
**M. Emerick**, S. P. Chhatoi, and B. Bamieh. In preparation for submission to IEEE Transactions on Control of Network Systems (available on arXiv).



Tracking Control for Continuum Swarms
----------
In many settings in swarm robotics, it is desirable that a swarm of robots continuously "track" (i.e. follow) a given entity as it changes. For example, data collection robots may need to track points-of-interest as they move around, fire-fighting drones may need to track a fire as it evolves, and fleets of autonomous taxis may need to track "rider demand" as it shifts throughout the day. One natural setting in which to investigate this behavior is the so-called "Wasserstein space" of optimal transport theory, which is able to effectively capture spatial discrepancies between swarm and target densities. This project aims to understand efficient motion and tracking control in this space, and use this understanding to develop better predictive models, numerical algorithms, and control schemes.


"Optimal Assignment and Motion Control in Two-Class Continuum Swarms," \
**M. Emerick,** S. Patterson, and B. Bamieh, IEEE Transaction on Control of Network Systems, vol. 13, no. 1, pp. 130-142, 2026.

"Causal Tracking of Distributions in Wasserstein Space: A Model Predictive Control Scheme," \
**M. Emerick,** J. Jonas, and B. Bamieh, 63rd IEEE Conference on Decision and Control, pp. 7606-7611, 2024.

"Continuum Swarm Tracking Control: A Geometric Perspective in Wasserstein Space," \
**M. Emerick** and B. Bamieh, 62nd IEEE Conference on Decision and Control, pp. 1367-1374, 2023.

"Optimal Combined Motion and Assignments with Continuum Models," \
**M. Emerick,** S. Patterson, and B. Bamieh, IFAC-PapersOnLine, vol. 55, no. 13, pp. 121-126, 2022.



Incompressible Fluid Mixing
----------
In many engineering applications it is important to be able to mix two fluids efficiently. In combustion engines one needs to mix fuel and air, in chemical process such as polymer production one needs to mix monomers and reactants, and in lab-on-chip applications one needs to mix samples and reagents. While there are many heuristics for what makes a flow field good at mixing, we do not have a complete mathematical understanding of this behavior. This project aims to characterize maximally efficient mixing fields, thereby giving us a better mathmatical understanding of mixing and helping us to design machines and protocols which can mix more effectively.


"Incompressible Fluid Mixing as Constrained Optimal Transport,"\
**M. Emerick**, J. Igraszek, and B. Bamieh. In preparation for submission to Journal of Nonlinear Science.

"Incompressible Optimal Transport and Applications in Fluid Mixing," \
**M. Emerick** and B. Bamieh, 64th IEEE Conference on Decision and Control, pp. 3157-3162, 2025.



Mean-Field Oscillator Ising Machines
----------
Description here


"Mean-Field Oscillator Ising Machines: Gradient Flows and Classification of Limit Solutions,"
B. Bamieh, F. Bullo, M. Emerick, and A. R. Venkatakrishnan. In preparation for submission to SIAM Review (available on arXiv).



Flight-Test Data Systems (Undergraduate Research)
----------
My undergraduate research focused on designing mechatronic devices for making real-time measurements of boundary layers on aircraft. These devices were designed to fit in low-profile, adhesive-mountable, and fully self-contained packages while maintaining high accuracy in the extreme environments encountered at altitude. I worked on three devices during my tenure in the lab: the "Pressurewing-I" and "Pressurewing-II", multi-sensors built on Adafruit's Feather platform, providing up to ten independent boundary layer measurements in addition to temperature/pressure, and the "BLDS-T", a large-scale distributed temperature-sensor network for thermal mapping ([news article](https://mustangnews.net/students-develop-next-gen-flight-test-data-system/)).


