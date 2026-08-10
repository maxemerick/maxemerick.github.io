---
permalink: /research/
title: "Research"
author_profile: true
redirect_from:
  - /research.html
---

My current research focuses on developing mathematical tools for the modeling, analysis, and control of continuum models of large-scale systems.

Large-scale systems are ubiquitous in the modern world: transportation and social networks, power grids, financial markets, biological and artificial neural networks, human and animal populations, robotic swarms, and the Internet of Things, to name a few. These systems play an enormous role in shaping our everyday lives, yet we do not have anything close to a general theory of behavior for these systems. The central challenge is that these systems are simply too large to analyze using classical methodologies. While numerical and data-driven approaches do play an important role here, they struggle to provide interpretable, structural insights. These structural insights are indispensable for the *design* of these systems in particular, which appears to be a foundational problem: while many reasonable control strategies perform well on a well-designed system (data-driven methods included), even the best control strategy will perform poorly on one that is poorly-designed.

One approach to getting a handle on the complexity of large-scale systems is to model them as *continua*, treating a system as one continuous medium as opposed to a large collection of individual components. These continuum models provide a more analytically tractable and scale-invariant way to study these systems. My research draws from a wide array of tools in mathematics (partial differential equations, optimal transport, geometric/variational methods), physics (continuum and statistical mechanics), and engineering (dynamics and control theory) in order to understand these continuum models and develop methods that can be applied towards the design, analysis, and control of real systems.

In pursuing this program, I see (at least) three central challenges in developing general theory for large-scale systems: understanding the role of heterogeneity, relating between microscopic (component-wise) and macroscopic descriptions, and modeling distributed architectures and the flow of information. I believe that general theory of this kind can only be built by working across a variety of problem domains, seeing where existing tools succeed, fail, or need to be extended. I have a number of active research thrusts designed to push in one or more of these directions. These are described below along with some of my past research projects.

Publications are listed under the project they are associated with. All publications can be found at my [Google Scholar page](https://scholar.google.com/citations?user=CN7oYBQAAAAJ&hl=en).



Tracking Control for Continuum Swarms
----------
Many large-scale systems can be naturally modeled using densities or distributions -- for example, spatial distributions of large-scale robotic swarms, densities of particulates immersed in a fluid, or probability densities arising in statistical/ensemble-type systems. A natural way to compare and manipulate such densities is using *optimal transport theory*, which provides methods for measuring differences and transforming between densities in ways which are compatible with the underlying physics. This project uses this framework to study tracking control: the problem of continuously transforming a density in order to follow a changing target. Such tracking behaviors are common in swarm robotics -- for example, data collection robots tracking points of interest, fire-fighting drones tracking a spreading fire, or autonomous taxis tracking shifting rider demand. We aim to understand efficient motion and tracking control in this setting, and to use this understanding to develop better predictive models, numerical algorithms, and control schemes.


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
In many applications it is important to be able to mix two fluids efficiently. In combustion engines one needs to mix fuel and air, in chemical processes such as polymer production one needs to mix monomers and reactants, and in lab-on-chip applications one needs to mix samples and reagents. While there are many heuristics for what makes a flow field good at mixing, we do not have a complete mathematical understanding of this behavior. As described above, this problem can also be modeled as a problem of controlling densities, and can be treated using the same optimal transport-related tools. This project aims to characterize maximally efficient mixing fields, thereby giving us a better mathematical understanding of mixing and helping us to design machines and protocols which can mix more effectively. Moreover, this problem provides a valuable test case for control of continuum systems with coupling constraints (in this case, incompressibility).


"Incompressible Fluid Mixing as Constrained Optimal Transport," \
**M. Emerick**, J. Igraszek, and B. Bamieh. In preparation for submission to Journal of Nonlinear Science.

"Incompressible Optimal Transport and Applications in Fluid Mixing," \
**M. Emerick** and B. Bamieh, 64th IEEE Conference on Decision and Control, pp. 3157-3162, 2025.



Mean-Field Oscillator Ising Machines
----------
Combinatorial optimization problems are ubiquitous in large-scale systems, with applications including circuit design, logistics and routing, resource allocation in networked systems, and data compression. In general, these problems are NP-hard, with the cost of obtaining exact solutions scaling exponentially with the network size. This has driven the development of alternative computational architectures such as Oscillator Ising Machines (OIMs) -- coupled-oscillator-based analog computers which are able to efficiently approximate solutions to these problems. In this project, we study the mean-field (continuum) limit of these OIMs, investigating the roles of symmetry in obtaining reduced-order density-based models and of various structural features in their analysis. Moreover, this problem provides a valuable test case for control of continuum systems exhibiting heterogeneity and nonlocal interactions.


"Mean-Field Oscillator Ising Machines: Gradient Flows and Classification of Limit Solutions," \
B. Bamieh, F. Bullo, **M. Emerick**, and A. R. Venkatakrishnan. In preparation for submission to SIAM Review (available on arXiv).



Distributed Control of Continuum Systems
----------
Approaches to control of large-scale systems can be (roughly) divided into two types: centralized and distributed. Centralized control architectures operate under the assumption that there exists a single decision-maker which is essentially both omniscient (able to access all the information in the system) and omnipotent (able to command all of the components in the system). While these sorts of architectures can have very high performance and are more straightforward to analyze, they tend to require hefty communication and computation infrastructure (making them difficult to scale), and introduce a singular point of failure (i.e. the decision-maker). On the other hand, distributed control architectures operate under the assumption that each component ("agent") in the system observes its own state and surroundings, communicates with its neighbors, and then makes its own decisions based on the limited information it has available. While these sorts of architectures can be extremely robust and efficient, they are harder to analyze since information is inherently localized and acquires its own dynamics. While distributed control has been studied in the discrete-agent setting for some time now, there is substantially less work on distributed control in the continuum, and it is not even clear how to best formulate the problem. We propose a new model of continuum distributed controllers as differential operators, which make control decisions as a function of the derivatives of the state and information at each point.


"On Distributed Control of Continuum Swarms: Local Controllers as Differential Operators," \
**M. Emerick**, S. P. Chhatoi, and B. Bamieh. In preparation for submission to IEEE Transactions on Control of Network Systems (available on arXiv).



Flight-Test Data Systems (Undergraduate Research)
----------
My undergraduate research focused on designing mechatronic devices for making real-time measurements of boundary layers on aircraft. These devices were designed to fit in low-profile, adhesive-mountable, and fully self-contained packages while maintaining high accuracy in the extreme environments encountered at altitude. I worked on three devices during my tenure in the lab: the "Pressurewing-I" and "Pressurewing-II", multi-sensors built on Adafruit's Feather platform, providing up to ten independent boundary layer measurements in addition to temperature/pressure, and the "BLDS-T", a large-scale distributed temperature-sensor network for thermal mapping ([news article](https://mustangnews.net/students-develop-next-gen-flight-test-data-system/)).


