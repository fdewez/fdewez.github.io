---
permalink: /research/
title: "Research"
author_profile: true
classes: wide
---

## Statistical and learning methodologies for trajectory optimisation problems

### Description

Trajectory optimisation is a wide field of study with numerous applications in academic and industrial settings. Many algorithms have been developed to find the trajectory which minimises the criterion of interest while complying with certain constraints. Among them, optimal commands methods provide a large family of approaches to model and to solve numerically such optimisation problems. In this case an a priori knowledge of the underlying dynamics of the system is required to obtain a realistic solution.<br />

Nevertheless the exact knowledge of physical systems may be hard to model and numerical methods may require a huge amount of computational ressources. In view of this, we leverage numerous data coming from real-life situations to develop a new methodology to model trajectory optimisation problems. In a nutshell, this methodology, which is intended to be generic, exploits information contained in the data to obtain simple problems which take into account estimated properties of the system and which can be solved by efficient algorithms.<br />

This methodology has been applied to reduce the fuel consumption of airliners within the PERF-AI project. Further developments of this methodology are considered in view of new applications.

### Project

**Project name:** PERF-AI, Enhance Aircraft Performance and Optimisation through utilisation of Artificial Intelligence\
**Fundings:** H2020 Clean Sky 2\
**Partners:** [Safety Line](https://www.safety-line.fr)\
**Role:** Postdoctoral researcher

### Collaborators

[Benjamin Guedj](https://bguedj.github.io/), [Vincent Vandewalle](https://pro.univ-lille.fr/vincent-vandewalle/), [Arthur Talpaert](https://github.com/ArthurTlprt)

### Papers (see Publications for more details)

**Published:**

### Software

A Python librairy PyRotor has been developed and will be available soon at [https://github.com/bguedj/pyrotor](https://github.com/bguedj/pyrotor).


## Description of wave packets propagation

### Description

Quantum Mechanics is the field which seeks at describing atomic and sub-atomic phenomena. While it turns out to be highly efficient to model certain phenomena, some principles are actually not intuitive such as the Uncertainty Principle. Broadly speaking, it claims that the position and the momentum of a particle can not be localised at the same time. However it is still possible to derive partial information on these two quantities.<br />

The aim of this research project, which is actually the core of my PhD thesis, is to develop a methodology to quantify in a certain way the spatial localisation of a particle given a perfect knowledge of its momentum. This can be achieved by applying wisely the stationary phase method to solutions of dispersive equations describing quantum particles, leading to time-asymptotic descriptions of the position with explicit error. The mathematical results cover not only the Schrödinger equation but also relativistic equations and provide insightful interpretations from a physical point of view.

Applications to perturbed or nonlinear settings are expected to bring some new explicit results which could be interpreted and exploited by the Physics community.

### Project

**Fundings:** Labex [CEMPI](https://math.univ-lille1.fr/~cempi/) and the Nord-Pas-de-Calais region.\
**Role:** PhD student

### Collaborators

[Felix Ali Mehmeti](https://www.uphf.fr/LAMAV/membres/mehmeti_felix)

### Papers (see Publications for more details)

Todo

## Numerical optimisation for acoustic reconstruction problems

### Description

Sound source reconstruction problem is a typical ill-posed problem: a perfect reconstruction of the sources of interest requires an infinite number of sensors which is obvsiously impossible from a practical point of view. In view of this, many acoustic-based methods have been developed to solve the associated inverse problems from a finite and limited number of data. The resulting algorithms propose different compromises between precision of the reconstructed sources and the computational cost.<br />

The aim of this project is to reduce the computational complexity of an innovative but complex numerical method for inverse acoustic problems used by an industrial partner. A thorough study of this method has shown that many quantities are computed while they have only a very small influence on the precision of the solution. The task was then to adapt the original method to avoid these unnecessary computations. This has been achieved by exploiting some physical features of the problem, reducing hence the computational complexity without impacting too strongly the error of the method.

### Project

**Project name:** LUG2, Outils Modulaires Efficients d’Imagerie Acoustique\
**Fundings:** Fonds Unique Interministériel (FUI)\
**Partners:** [MicrodB](https://www.microdb.vibratecgroup.com)\
**Role:** Postdoctoral researcher

### Collaborators

[Thibaut Le Magueresse](https://www.linkedin.com/in/thibaut-le-magueresse/), [Ivan Logre](https://www.linkedin.com/in/logre/), [Christophe Picard](http://membres-ljk.imag.fr/picard/), [Christophe Picard](https://www.linkedin.com/in/christophe-picard-3ba08b1b/)

### Papers (see Publications for more details)

A paper explaining the adapted method is in progress.

### Software

The methodology has been implemented in Python and transfered to the industrial partner for real-case tests.

## Hill cipher

### Description

In cryptography, Hill cipher is a block-cipher developed by Hill in the late 1920s. This cipher has been proved vulnerable to many common attacks, preventing it from being used in practice. On the other hand, some articles have been recently published to propose new efficient ciphertext-only attacks, that is to say attacks wher the attacker has only access to the ciphertext.<br />

Following these articles, we propose a new kind of ciphertext-only attack by exploiting an algebraic weakness of the Hill cipher. In a nutshell we make use of the fact that the Hill cipher preserves some algebraic patterns within the texts to develop an attack consisting in making a restrictive search over the texts rather than over the keys. Theoretical studies and numerical tests show that this attack, called Orbit-Based Attack, has an interesting complexity in the worst case.<br />

This new attack allows to use efficient statistical models to further improve the search over texts. This work is in progress.

### Collaborators

[Valentin Montmirail](https://scholar.google.fr/citations?user=pdC7MpcAAAAJ&hl=fr&oe=ASCII)

### Papers (see Publications for more details)

Todo

### Software

The Orbit-Based Attack has been implemented in C++.

## Lights Out

### Description

The Lights Out game consists of a 5 by 5 grid of lights. Given a pattern of switched lights, the goal of the game is to switch all the lights off with the following rule: pressing a light will toggle it and the adjacent ones. While being simple to explain, it turns out to be hard to solve in practice without an efficient strategy.<br />

Linear algebra offers actually a very elegant framework to model the game. In particular abstract notions, such as the null space of a matrix, can be easily interpreted in terms of the game. An intuitive algorithm coming from this modelling permits to compute all the solutions of the game and to propose the best one, namely the solution with the fewest button presses.<br />

Workshops and talks for high-school students have been created to illustrate how mathematics can be smartly used in order to understand and solve complex problems.

### Collaborators

[Thibault Defourneau](https://www.linkedin.com/in/thibault-defourneau-6b138812a/), [Valentin Montmirail](https://scholar.google.fr/citations?user=pdC7MpcAAAAJ&hl=fr&oe=ASCII)

### Papers (see Publications for more details)

Todo

### Software

The algorithm has been implemented in Java together with an interface permitting to play and to solve the Lights Out. It is available at [https://github.com/Mystelven/LightsOuts-Math](https://github.com/Mystelven/LightsOuts-Math).