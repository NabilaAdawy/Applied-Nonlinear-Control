# Applied-Nonlinear-Control

The goal of this course is to learn the basics of fundamental nonlinear control theory. The course is directed through the developing the reasonably simple mathematical tools that can be directly applied to real problems.

## Learning outcomes 
(as mentioned in the beginning of the course)
- Recall what is system, control theory, linear and nonlinear phenomena.
- Perform linear and nonlinear analysis, with focus on Lyapunov theory.
- Design classical controllers based on system model, even in case when inputs not aligned with outputs
- Implement the robust and adaptive controllers that will work in case when you don't know your system model exactly.

In general you will get the set of tools that allow you to go deeper both inside the research and practical issues of control. In the last lecture you will have a gentle introduction to modern control theory and advanced methods.

### Hand book: 
[Applied Nonlinear Control](http://www.ioe.nchu.edu.tw/Pic/CourseItem/4497_APPLIED%20NONLINEAR%20CONTROL_slotine_Part1.pdf)


## First Home Assignment
Simulating the responses for nonlinear systems to study the nonlinear behavior: Multiple equilibrium points, Oscillations and Limit Cycles, Bifurcations, Chaos.

## Second Home Assignment
#####Implementing some practical tasks regarding Phase Plane Analysis: 
- Concepts of Phase Plane Analysis:
  - Phase Portraits.
  - Singular Points.
  - Symmetry in Phase Plane Portraits.
- Constructing Phase Portraits.
- Determining Time from Phase Portraits.
- Phase Plane Analysis of Linear Systems.
- Phase Plane Analysis of Nonlinear Systems.
- Existence of Limit Cycles.

#####Implement software routine that will implement the Lyapunov linearization method including:
- Solving for equlibrium
- Symbolical linearization
- Checking for the stability of each equlibrium
- Drawing the phase portrait together with stable and unstable points.

## Third Home Assignment
Implementing some practical tasks regarding** Lyapunov Direct method** and determining **local and global stability**. Estimating **Regions of Attraction**, study **Robustness Analysis**,** Convergence Rates**. and **Control Design Based on Lyapunov Direct Method**.


## Term Project
At the end of the semester my term project was about impelementing Trajectory Optimization (which is an open loop control) for a Cart-Pole system using Casadi framework.
The swing up problem for a cart-pole system is to find the force as a function of time that will move the cart and have this pendulum which has no motor actuated on it, swing up to be balanced above the cart.
