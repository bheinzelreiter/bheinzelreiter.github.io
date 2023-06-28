---
permalink: /research-interests
title: "Research Interests"
excerpt: "Research Interests"
author_profile: true
---

My research interests are centered around the numerical study of optimal control problems. I am especially interested in computational methods for large-scale systems arising from real-world problems and in their challenges from a numerical linear algebra point of view. Overall, my research interests can be narrowed down to two main areas, which are described subsequently.

## PDE-constrained optimization
A wide range of physical processes may be modeled by PDEs. These models sometimes depend on parameters, which often entails the question, what choices of parameters are optimal. These kinds of problems lead to so-called PDE-constrained optimization problems. Upon discretization, these problems turn out to be high-dimensional and one is forced to use bespoke methods for solving them. I am interested in the development and the study of fast iterative solvers for these problems. Moreover, I study methods for PDE-constrained optimization based on the Hamilton-Jacobi-Bellman equations. 

## Receding Horizon Control/Feedback control
When considering time-dependent PDE-constrained optimization problems, solving the optimization problem on a fixed time horizon does not always give a reliable solution in practice. Inaccuracies of the models, errors in measurements, or uncertainties can require one to continuously update the control as time proceeds. Controls of this kind are called *feedback controls* and often preferred over so-called *open-loop controls*. Although equations for feedback controls can be derived theoretically, these can become numerically intractable even for small problems with coarse discretizations. One approach that circumvents this is called *receding horizon control* (RHC). RHC reformulates the feedback control problem as a sequence of open-loop controls. This does not only enable to achieve a feedback control, but also allows one to incorporate complex constraints on the state and the control. I am interested in the mathematical formulation of RHC and in methods for achieving theoretical asymptotic stability. 
