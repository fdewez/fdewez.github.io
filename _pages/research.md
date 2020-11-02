---
permalink: /research/
title: "Research"
author_profile: true
classes: wide
---
As a mathematician working in different fields, I leverage my experience to propose new points of view for concrete problems from the natural sciences or from the industry for a better understanding and novel numerical methods. I enjoy especially collaborating with experts from other fields to build a bridge between the mathematical sciences and other domains. Indeed the interpretation of mathematical concepts from other domains may help the mathematician to bring insights to those concepts, leading potentially to innovative methods which are both efficient and reliable. <br />

I detail below the projects in which I am or have been involved.

## Statistical and learning methodologies for trajectory optimisation problems

### Description

Trajectory optimisation is a wide field of academic and industrial study with numerous applications. Many algorithms have been developed to find the trajectory which minimises the criterion of interest while complying with certain constraints. Among them, we can mention optimal commands methods which provide a large family of physical-based approaches to model and to solve numerically such optimisation problems. In this case an a priori knowledge of the underlying dynamics of the system is required to obtain a realistic solution.<br />

Nevertheless the exact knowledge of physical systems may be hard to model and numerical methods may require significant computational ressources. In view of this, we leverage huge amounts of data coming from real-life situations to develop a new methodology for the modelling of trajectory optimisation problems. In a nutshell, this methodology, which is intended to be generic, exploits information contained in the data to obtain simpler problems which take into account estimated properties of the system and which can be solved by efficient algorithms.<br />

This work has been carried out in collaboration with aeronautics experts from Safety Line within the PERF-AI project for the reduction of fuel consumption in the aviation. Further developments of this methodology are considered in view of new applications.\
A first paper showing how to design individual performance models of physical systems has been published and a second one introducing the optimisation methodology is in progress; see [Publications](https://fdewez.github.io/publications/).

**Project:** PERF-AI, Enhance Aircraft Performance and Optimisation through utilisation of Artificial Intelligence\
**Fundings:** H2020 Clean Sky 2\
**Partners:** [Safety Line](https://www.safety-line.fr)\
**Role:** Postdoctoral researcher

### Collaborators

[Benjamin Guedj](https://bguedj.github.io/), [Baptiste Gregorutti](https://www.linkedin.com/in/thibaut-le-magueresse/), [Arthur Talpaert](https://github.com/ArthurTlprt), [Vincent Vandewalle](https://pro.univ-lille.fr/vincent-vandewalle/)

### Software

We develop the Python library PyRotor which will be available soon at [https://github.com/bguedj/pyrotor](https://github.com/bguedj/pyrotor).


## Description of wave packets propagation

### Description

Quantum Mechanics is the field which seeks at describing atomic and sub-atomic phenomena. While it turns out to be highly efficient to model certain phenomena, some principles are actually not intuitive such as the Uncertainty Principle. Broadly speaking, it claims that the position and the momentum of a particle can not be localised at the same time. However it is still possible to derive partial information on these two quantities.<br />

The aim of this research project, which is actually the core of my PhD thesis, is to develop a methodology to quantify in a certain way the spatial localisation of a particle given a perfect knowledge of its momentum. We achieve this result by applying wisely the stationary phase method to solutions of dispersive equations describing quantum particles, leading to time-asymptotic descriptions of the position with explicit error. Our mathematical results cover not only the Schrödinger equation but also a large family of evolution equations and provide insightful interpretations from a physical point of view.

Applications to perturbed or nonlinear settings are expected to bring some new explicit results which could be interpreted and exploited by the Physics community.\
Three papers detailing the methodology in the case of free particles have been published; see [Publications](https://fdewez.github.io/publications/). A preprint on an application of the method to the Schrödinger equation with potential is available [here](https://fdewez.github.io/files/fdewez-schrodinger_potential.pdf).

**Fundings:** Labex [CEMPI](https://math.univ-lille1.fr/~cempi/) and the Nord-Pas-de-Calais region\
**Role:** PhD student

### Collaborators

[Felix Ali Mehmeti](https://www.uphf.fr/LAMAV/membres/mehmeti_felix)

## Numerical optimisation for acoustic reconstruction problems

### Description

Sound source reconstruction problems are typically ill-posed: a perfect reconstruction of the sources of interest requires an infinite number of sensors which is obvsiously impossible from a practical point of view. In view of this, many acoustic-based methods have been developed to solve the associated inverse problems from a finite and limited number of data. The resulting algorithms propose different compromises between precision of the reconstructed sources and computational cost.<br />

The aim of this project is to reduce the computational complexity of an innovative but complex numerical method for inverse acoustic problems used by an industrial partner. A thorough study of this method has shown that many quantities are computed while they have only a very small influence on the precision of the solution. Our task was then to adapt the original method to avoid these unnecessary computations. To do so, we have exploited some physical features of the problem, reducing hence the computational complexity without impacting too strongly the error of the method.

This work has been carried out in collaboration with acoustic experts from MicrodB and LVA (INSA Lyon) within the LUG2 project.\
The writing of a paper on this method is in progress.

**Project:** LUG2, Outils Modulaires Efficients d’Imagerie Acoustique\
**Fundings:** Fonds Unique Interministériel (FUI)\
**Partners:** [MicrodB](https://www.microdb.vibratecgroup.com)\
**Role:** Postdoctoral researcher

### Collaborators

[Thibaut Le Magueresse](https://www.linkedin.com/in/thibaut-le-magueresse/), [Ivan Logre](https://www.linkedin.com/in/logre/), [Christophe Picard](http://membres-ljk.imag.fr/picard/), [Christophe Picard](https://www.linkedin.com/in/christophe-picard-3ba08b1b/)

### Software

The methodology has been implemented in Python and transfered to the industrial partner for real-case tests.

## Hill cipher

### Description

In cryptography, Hill cipher is a block-cipher developed by Hill in the late 1920s. This cipher has been proved vulnerable to many common attacks, preventing it from being used in practice. On the other hand, some articles have been recently published to propose new efficient ciphertext-only attacks, that is to say attacks where the attacker has only access to the ciphertext.<br />

Following these articles, we propose a new kind of ciphertext-only attack by exploiting an algebraic weakness of the Hill cipher. In a nutshell we make use of the fact that the Hill cipher preserves some algebraic patterns within the texts to develop an attack consisting in making a restrictive search over the texts rather than over the keys. Our theoretical studies and numerical tests show that this attack, called Orbit-Based Attack, has an interesting complexity in the worst case.<br />

This new attack allows to use efficient statistical models to further improve the search over texts. This work is in progress.\
An article on the Orbit-Based Attack has been published; see [Publications](https://fdewez.github.io/publications/).

### Collaborators

[Valentin Montmirail](https://scholar.google.fr/citations?user=pdC7MpcAAAAJ&hl=fr&oe=ASCII)

### Software

The Orbit-Based Attack has been implemented in C++.