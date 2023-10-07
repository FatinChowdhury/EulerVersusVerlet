# EulerVersusVerlet
Teammates: Fatin Chowdhury, Karim Mawji

Project Overview:

This project focuses on simulating a pendulum's motion, comparing the small angle approximation to the differential equation, and contrasting Euler's method with Verlet's method. A pendulum's behavior is governed by the laws of energy and momentum conservation. Small angle approximation is valid for angles under 10 degrees; beyond that, the full differential equation is necessary. The project leverages external sources and Google Colab for implementation, referencing the University of Delaware's article on Verlet and the textbook "Physics for Scientists and Engineers" for understanding.

Model and Numerical Methods:
The project simulates pendulum motion using Euler's and Verlet's methods, generating angular displacement vs. time graphs. Key steps include importing libraries (e.g., matplotlib and math), defining constants (DT, T_MAX, STEPS, g, l), and initializing conditions (Theta0, omega0, alpha0). Both methods involve iterative calculations of angular displacement, velocity, and acceleration. Results are plotted in a time vs. theta graph, comparing Euler's and Verlet's methods. Additionally, the project calculates the pendulum's period using Verlet's method and the small angle approximation, generating period vs. initial angle graphs. External sources provide guidance on Verlet's method and pendulum physics.

Validation:
The project's validation process involved comparing the generated graphs with those found in the textbook "Physics for Scientists and Engineers by Serway & Jewett, 10th edition." The results were found to be consistent with both the textbook's graphs and the fundamental principles of pendulum physics. For example, the small angle approximation's period vs. initial angle graph showed a constant period, aligning with the physics principles where the period depends solely on pendulum length and gravitational acceleration, both of which remain constant. This validation confirms the accuracy and adherence to established physics principles in the project's simulations.

Results:

Matplotlib (plt) was used for graphing results.
Comparison between small angle approximation (SAA) and full ordinary differential equation (ODE) for oscillation period vs. amplitude.
Period vs. initial angle graphs for SAA and non-SAA conditions.
A comparison graph showed angular frequency for Euler's and Verlet's methods.
These results provide insights into the accuracy of SAA and the effectiveness of numerical methods in modeling pendulum behavior.

