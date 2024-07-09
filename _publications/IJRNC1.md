---
title: "Iterative distributed model predictive control for nonlinear systems with coupled non‐convex constraints and costs"
collection: publications
permalink: /publication/IJRNC1
excerpt: 'This paper proposes a distributed model predictive control (DMPC) algorithm for dynamic decoupled discrete-time nonlinear systems subject to nonlinear (maybe non-convex) coupled constraints and costs.'
date: 2024-07-25
venue: 'International Journal of Robust and Nonlinear Control'
paperurl: 'https://onlinelibrary.wiley.com/doi/abs/10.1002/rnc.7341'
citation: 'Wu, J., Dai, L., & Xia, Y. (2024). Iterative distributed model predictive control for nonlinear systems with coupled non‐convex constraints and costs. International Journal of Robust and Nonlinear Control, 34(11), 7220-7244.'
---

This paper proposes a distributed model predictive control (DMPC) algorithm for dynamic decoupled discrete-time nonlinear systems subject to nonlinear (maybe non-convex) coupled constraints and costs. Solving the resulting nonlinear optimal control problem (OCP) using a DMPC algorithm that is fully distributed, termination-flexible, and recursively feasible for nonlinear systems with coupled constraints and costs remains an open problem. To address this, we propose a fully distributed and globally convergence-guaranteed framework called inexact distributed sequential quadratic programming (IDSQP) for solving the OCP at each time step. Specifically, the proposed IDSQP framework has the following advantages: (i) it uses a distributed dual fast gradient approach for solving inner quadratic programming problems, enabling fully distributed execution; (ii) it can handle the adverse effects of inexact (insufficient) calculation of each internal quadratic programming problem caused by early termination of iterations, thereby saving computational time; and (iii) it employs distributed globalization techniques to eliminate the need for an initial guess of the solution. Under reasonable assumptions, the proposed DMPC algorithm ensures the recursive feasibility and stability of the entire closed-loop system. We conduct simulation experiments on multi-agent formation control with non-convex collision avoidance constraints and compare the results against several benchmarks to verify the performance of the proposed DMPC method.
