---
content_type: page
title: Syllabus
uid: 0fe70028-e5b8-3fb2-cf17-324c4c113b28
---

Course Meeting Times
--------------------

Lectures: 2 sessions / week, 1.5 hours / session

Course Description
------------------

This course will cover a collection of geometric techniques that apply broadly in modern algorithm design. The exact topics covered will depend on student interest, but a (perhaps overly ambitious) set of possibilities includes:

### Spectral Graph Theory

Graph Laplacians and their eigenvalues, connections to random walks and mixing, isoperimetric and Cheeger inequalities, expanders, and random graphs. Applications to include graph cutting, clustering, approximate counting, disjoint path problems, routing, and graph drawing.

### Convex Geometry

Geometric properties of high-dimensional convex bodies, Fritz John's theorem and isotropy, Brunn-Minkowski and isoperimetric inequalities, concentration of measure and connections to probability theory. Applications to include volume computation and convex programming.

### Multiplicative Weights

The multiplicative weights update method, its geometric meaning, and the many ways that it appears in modern computer science, with a focus on its use in optimization. Applications to include fast approximation algorithms for graph problems, "boosting" in learning and complexity theory, online algorithms, and zero-sum games.

### Iterative Methods for Linear Algebra

How to use geometric information to quickly solve linear systems and eigenvalue problems. Will cover basic iterative methods, the Lanczos algorithm, conjugate gradients, preconditioning, and how spectral graph theory can be used to improve the construction of preconditioners.

### Lattices and Basis Reduction

Basic properties of lattices, Minkowski's theorem, and the LLL algorithm. Applications to include solving low-dimensional integer programs and breaking cryptosystems.

### LP- and SDP-based Approximation Algorithms for NP-Hard Problems

Linear and semidefinite programming relaxations of NP-hard problems, rounding techniques, and primal-dual methods.

Course Goals
------------

*   To learn a collection of powerful (and interrelated) mathematical techniques for algorithm design
    *   Topics picked to be both mathematically interesting and practically useful
    *   Will sometimes have long mathematical interludes, but always with proportional algorithmic payoffs
*   To be able to apply these tools directly to your research
    *   Whether your work is theoretical or applied
    *   I'll suggest open research questions whenever possible

Course Requirements
-------------------

The course requirements will comprise two parts:

1.  Problem sets, and
2.  Scribe notes

### 1\. Problem Sets

I do not want this course to present an onerous workload, but I do want to give out enough problems to allow people to really learn the material. Since this is an advanced graduate class, I believe that students are capable of deciding for themselves how best to make this tradeoff. As such, I will hand out problem sets for each major topic and correct them, but I will not expect you to do all of the problems that I distribute. I will expect students to do as many as is necessary for a good-faith effort to learn the material. I recommend a total equivalent to at least two graduate problem sets over the course of the semester. Undergraduates taking this class will have a slightly more concrete set of requirements in which the number of required problems will be specified more precisely.

### 2\. Scribe Notes

I would like to have scribes for every lectures. Each student should do his/her fair share of these.

Collaboration Policy
--------------------

Collaboration is encouraged on the problem sets. However, you should think about the problems yourself before discussing them with others. Furthermore, you must write your solutions up individually and understand anything that you hand in. If you do collaborate, you must acknowledge your collaborators in your writeup. Use of outside sources is strongly discouraged; if, however, you do use an outside source, you must reference it in your solution.

Prerequisites
-------------

This is a graduate-level class and will move fairly quickly. We shall assume a significant level of mathematical maturity. The formal prerequisites are fairly minimal however; they consist of:

*   Multivariable Calculus (18.02)
*   Linear Algebra (18.06)
*   Basic Algorithms, and
*   Basic Probability

Some experience with algorithms beyond the introductory level will be helpful, but it is not strictly necessary.

Calendar
--------

| SES # | TOPICS | KEY DATES |
| --- | --- | --- |
| {{< td-colspan 3 >}}**Spectral Graph Theory**{{< /td-colspan >}} |||
| 1 | Linear algebra review, adjacency and Laplacian matrices associated with a graph, example Laplacians | &nbsp; |
| 2 | Properties of the Laplacian, positive semidefinite matricies, spectra of common graphs, connection to the continuous Laplacian | &nbsp; |
| 3 | Courant-Fischer and Rayleigh quotients, graph cutting, Cheerger's Inequality | &nbsp; |
| 4 | (Lazy) random walks, their stationary distribution and l2-convergence, normalized Laplacian, conductance, Monte Carlo methods | &nbsp; |
| 5 | Monte Carlo methods continued, approximate DNF counting, approximating the permanent of 0-1 matrices | &nbsp; |
| 6 | Diameters and eigenvalues, expander graphs | &nbsp; |
| 7 | Nonblocking routing networks, local and almost-linear time clustering and partitioning, Lovasz-Simonovits Theorem | &nbsp; |
| 8 | Local and almost-linear time clustering and partitioning (cont.), PageRank, introduction to sparsification | &nbsp; |
| 9 | Sparsification (combinatorial and spectral), effective resistance, matrix pseudoinverses and tail bounds | &nbsp; |
| 10 | Spectral sparsification (cont.), introduction to convex geometry | Problem set 1 due |
| {{< td-colspan 3 >}}**Convex Geometry**{{< /td-colspan >}} |||
| 11 | Polar of a convex body, separating hyperplanes, norms and convex bodies, Banach-Mazur distance, Fritz John's theorem | &nbsp; |
| 12 | Separating hyperplanes (cont.), Banach-Mazur distance, Fritz John's theorem, Brunn-Minkowski inequality | &nbsp; |
| 13 | Brunn-Minkowski inequality (cont.), Brunn's theorem, isoperimetric inequality, Grunbaum's theorem | &nbsp; |
| 14 | Approximating the volume of a convex body | &nbsp; |
| 15 | Random sampling from a convex body (cont.), grid walk, introduction to concentration of measure | &nbsp; |
| 16 | Concentration of measure and the isoperimetric inequality, Johnson-Lindenstrauss theorem | &nbsp; |
| 17 | Johnson-Lindenstrauss theorem (cont.), Dvoretsky's theorem | &nbsp; |
| {{< td-colspan 3 >}}**Lattices and Basis Reduction**{{< /td-colspan >}} |||
| 18 | Lattices, fundamental parallelepiped and dual of a lattice, shortest vectors, Blichfield's theorem | &nbsp; |
| 19 | Minkowski's theorem, shortest/closest vector problem, lattice basis reduction, Gauss' algorithm | &nbsp; |
| 20 | LLL algorithm for lattice basis reduction, application to integer programming | Problem set 2 due |
| {{< td-colspan 3 >}}**Iterative Methods for Linear Algebra**{{< /td-colspan >}} |||
| 21 | Iterative methods to solve linear systems, steepest descent | &nbsp; |
| 22 | Convergence analysis of steepest descent and conjugate gradients | &nbsp; |
| 23 | Preconditioning on Laplacians, ultra-sparsifiers | &nbsp; |
| {{< td-colspan 3 >}}**Multiplicative Weights**{{< /td-colspan >}} |||
| 24 | Multiplicative weights | &nbsp; |
| 25 | Multiplicative weights and applications to zero-sum games, linear programming, boosting, and approximation algorithms | Problem set 3 due