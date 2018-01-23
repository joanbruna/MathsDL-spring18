# MathsDL-spring18
Topics course Mathematics of Deep Learning, NYU, Spring 18. CSCI-GA 3033. 

## Logistics

Tuesdays from 7.10pm-9pm. CIWW 102

Recitation (**optional**): Fridays 11am-12:30pm CIWW 101. The first week **only** it is 10:30am-12pm.

## Instructors

__Lecture Instructor__: Joan Bruna (bruna@cims.nyu.edu)

__Lab Instructor__: Cinjon Resnick (cinjon@nyu.edu)


## Syllabus

This Graduate-level topics course aims at offering a glimpse into the emerging mathematical questions around Deep Learning. In particular, we will focus on the different geometrical aspects surounding these models, from input geometric stability priors to the geometry of optimization, generalisation and learning. We will cover both the background and the current open problems. 

Besides the lectures, we will also run a parallel curricula (optional), which, starting from a landmark recent DL paper (AlphaGo), will trace back the fundamentals of Dynammic Programming, Policy Learning and Monte-Carlo Tree Search through the literature and lab materials. 

## Pre-requisites

Multivariate Calculus, Linear Algebra, Probability and Statistics at solid undergraduate level.

Notions of Harmonic Analysis, Differential Geometry and Stochastic Calculus are nice-to-have, but not essential.

## Grading

The course will be graded with a final research project plus a participation grade. 
Details TBA. 

## Lectures

*  Introduction: the Curse of Dimensionality [1 lecture]


* Part I: Geometry of Data
  * Euclidean Geometry: transportation metrics, CNNs , scattering. [2 lectures]
  * Non-Euclidean Geometry: Hausdorff-Gromov distances, Graph Neural Networks. [1 lecture]
  * Unsupervised Learning under Geometric Priors (Implicit vs explicit models, microcanonical, transportation metrics). [1 lecture]
  * Reproducing Kernel Hilbert Spaces [1 lecture]
  * Applications and Open Problems: adversarial examples, graph inference, inverse problems. [1 lecture]

* Part II: Geometry of Optimization and Generalization
  * Stochastic Optimization (Robbins & Munro, Convergence of SGD) [1.5 lecture]
  * Stochastic Differential Equations (Fokker-Plank, Gradient Flow, Langevin Dynamics, links with SGD; open problems) [1.5 lecture]
  * Information Geometry (Amari, Fisher-Rao metric, Wasserstein) [0.5 lecture]
  * Landscape of Deep Learning Optimization (Tensor/Matrix factorization, Deep Nets; open problems). [1.5 lecture]
  * Generalization: (Rademacher Complexity, Entropy Bounds, Covering Numbers; measuring capacity in CNNs; open problems). [2 lectures]


### Lab sessions / Parallel Curricula

* AlphaGoZero living document: https://goo.gl/iFZ4XD

* Class 1: Minimax and Alpha Beta Pruning
  * Motivation: These original core ideas did so much for the study of games. They spurred the field forward starting in the 50s and still to this day have mindshare in how to build a computer engine that beats games, including in popular chess engines like Stockfish.
  * Required Reading: 
    * [Cornell Recitation on Minimax & AB Pruning](https://www.cs.cornell.edu/courses/cs312/2002sp/lectures/rec21.htm)
    * [Knuth](https://pdfs.semanticscholar.org/dce2/6118156e5bc287bca2465a62e75af39c7e85.pdf): 6 (Theorems 1&2, Corollaries 1&3).
  * Optional Reading:
    * [CMU's MFAI Lecture 1](https://www.cs.cmu.edu/~arielpro/mfai_papers/lecture1.pdf).
    * Knuth: 1-3.    
    * [Chess Programming on Minimax](https://chessprogramming.wikispaces.com/Minimax)
    * [Chess Programming on AB Pruning](https://chessprogramming.wikispaces.com/Alpha-Beta)
  * Questions:
    * (Knuth) Show that AlphaBetaMin(p, alpha, beta) = -AlphaBetaMax(p, -beta, -alpha). (p. 300)
    * (Knuth) For Theorem 1.(1), why are the successor positions of type 2? (p. 305)
    * (Knuth) For Theorem 1.(2), why is it that p’s successor position is of type 3 if p is not terminal?
    * (Knuth) For Theorem 1.(3), why is it that p’s successor positions are of type 2 if p is not terminal?
    * (Knuth) Show that the subparts of Theorem 2, are correct.
