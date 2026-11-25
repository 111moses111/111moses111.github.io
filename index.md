---
title: Moisej Plistiev
---

# Moisej Plistiev

moisej.plistiev [at] gmail [dot] com ·
[GitHub](https://github.com/111moses111) ·
[CV (PDF)](files/cv.pdf)

I am a mathematician based in Vienna.
I completed my MSc in Mathematics at the University of Vienna in 2025.
My research interests lie in computable analysis and computational complexity, in particular the localization of zeros of analytic functions and analytic continuation,
as well as analysis of algorithms, computer algebra, computational geometry, computational number theory and complex systems.

**I am currently applying for PhD positions.**

## Preprints

- **On Some Connections Between Computation of Integrals of Analytic Functions, Root finding, Integer Factorization and NP-Completeness**<br>
  Moisej Plistiev. Preprint, October 2026. [PDF](papers/integrals-root-finding-factorization.pdf)<br>
  An integration-based method for certified localization of real zeros of analytic functions,
  applied to integer factorization and an NP-complete quadratic Diophantine decision problem.
  This yields polynomial-time Turing reductions from these problems to the approximate evaluation of explicit analytic functions,
  with the required number of accuracy bits linear in the input length.

## Projects and software

- **Geometric aspects of the computational complexity of analytic functions** *(ongoing)*<br>
  How does the geometry of the domain of analyticity (the location of singularities, the shape of the region and the growth of the function in it)
  affect the complexity of computing analytic functions, and how can it be used to speed up such computations?
  A first part, *On effective distance of analytic continuation and contour integration* (in preparation),
  studies the relation between the geometry of the domain, the step size and the cost of computation.
  Next, we plan to develop the ideas of the method of [Gawronski, Müller and Reinhard](https://doi.org/10.1137/060669589)
  and to implement the resulting methods in Julia; applications include contour integration, root-finding
  and arbitrary-precision evaluation of special functions.

- **MassRoots.jl**<br>
  A Julia implementation of the integral mass method from the preprint for real zeros of analytic functions of one variable,
  including zeros without a sign change.
  Planned: the multidimensional case, certified results for general functions, and systematic testing.<br>
  [Code](https://github.com/111moses111/MassRoots.jl) ·
  [Preprint (PDF)](papers/integrals-root-finding-factorization.pdf)

## Theses

- ***Zur Berechnungskomplexität analytischer Funktionen und der Faktorisierung ganzer Zahlen***<br>
  (On the computational complexity of analytic functions and integer factorization).<br>
  MSc thesis, University of Vienna, 2025. Supervisor: Arnold Neumaier.<br>
  [PDF](https://utheses.univie.ac.at/thesis/78210) ·
  [DOI: 10.25365/thesis.79970](https://doi.org/10.25365/thesis.79970)

## Talks

- *Root-finding of analytic functions and factorization*.<br>
  [CCA 2024](https://cca-net.de/cca2024/), 21st International Conference on Computability and Complexity in Analysis,
  Swansea University, UK, July 2024.

---

<small>Last updated: November 2026</small>
