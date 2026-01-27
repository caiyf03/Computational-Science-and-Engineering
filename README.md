This repository contains the official implementation for **APPLICATION OF FINITE ELEMENT METHODS IN SOLVING PDE-CONSTRAINED OPTIMIZATION FOR HEAT CONDUCTION PROBLEMS.**

The main text of the paper can be found at: [computerscience (Finalversion).pdf](computerscience%20(Finalversion).pdf)

In this article, we combine the concepts of finite element methods and convex optimization to sequentially solve three predictive problems in heat conduction, achieving promising results.

**ABSTRACT**

This project applies finite element methods (FEM) to solve partial differential equation (PDE)–constrained optimization problems arising in heat conduction scenarios. Motivated by theoretical foundations from Computational Science and Engineering and Numerical Optimization, the study explores how numerical optimization and PDE discretization interact in practice. Through a series of thermodynamic case studies, the work demonstrates how FEM can be combined with control and optimization techniques to analyze temperature distributions and infer internal heat sources under PDE constraints. All computational implementations are developed from first principles and tailored to the specific thermal problems considered.

**Keywords**

PDE · Thermal Conduction Problem · Control Optimization Theory

**Teammember**: YiFan Cai(leader), FanHao Bu, PeiJun Xu

**Methods**
The approach begins with formulating the heat conduction problems as PDE-constrained optimization problems, where the objective typically involves minimizing discrepancies in temperature fields or control costs subject to the governing heat equation. The PDEs are discretized using the finite element method, enabling numerical solution of both the state and adjoint equations. Optimization is then performed over control parameters using standard numerical solvers embedded within the FEM framework. Through iterative solution of PDE states and optimization updates, the project integrates FEM discretization with convex optimization strategies to handle constraints effectively across each case study.

![](1.png)
![](2.png)
![](3.png)
