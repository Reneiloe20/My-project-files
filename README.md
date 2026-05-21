# Physics of Diffusion Models in Generative AI

## Overview
This project explores the mathematics and physics behind diffusion models used in generative artificial intelligence. 

The work focuses on the diffusion equation and how probability distributions evolve over time, drawing parallels between statistical physics and modern AI image generation models.

---

## Objectives
- Study the diffusion equation
- Simulate Gaussian diffusion numerically
- Compare numerical and analytical solutions
- Visualize the evolution of probability distributions
- Relate physical diffusion processes to generative AI models

---

## Mathematical Background

The diffusion equation is given by:

\[
\frac{\partial P(x,t)}{\partial t}
=
D \frac{\partial^2 P(x,t)}{\partial x^2}
\]

where:
- \(P(x,t)\) is the probability distribution
- \(D\) is the diffusion coefficient
- \(x\) is position
- \(t\) is time

The analytical solution for an initial localized distribution is:

\[
P(x,t)
=
\frac{1}{\sqrt{4\pi Dt}}
\exp\left(
-\frac{x^2}{4Dt}
\right)
\]

---

## Technologies Used
- Python
- NumPy
- LaTeX

---


