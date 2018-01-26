# MathsDL-spring18
Topics course Mathematics of Deep Learning, NYU, Spring 18. CSCI-GA 3033. 

## Logistics

Tuesdays from 7.10pm-9pm. CIWW 102

Recitation (**optional**): Fridays 11am-12:30pm CIWW 101. The first week **only** it is 10:30am-12pm.

Piazza: [sign-up here](https://piazza.com/nyu/spring2018/csciga3033)

## Instructors

__Lecture Instructor__: Joan Bruna (bruna@cims.nyu.edu)

__Lab Instructor__: Cinjon Resnick (cinjon@nyu.edu)


## Syllabus

This Graduate-level topics course aims at offering a glimpse into the emerging mathematical questions around Deep Learning. In particular, we will focus on the different geometrical aspects surounding these models, from input geometric stability priors to the geometry of optimization, generalisation and learning. We will cover both the background and the current open problems. 

Besides the lectures, we will also run a parallel curricula (optional), which, starting from a landmark recent DL paper (AlphaGo), will trace back the fundamentals of Dynammic Programming, Policy Learning and Monte-Carlo Tree Search through the literature and lab materials. 

### Detailed Syllabus 

*  Introduction: the Curse of Dimensionality

* Part I: Geometry of Data
  * Euclidean Geometry: transportation metrics, CNNs , scattering. 
  * Non-Euclidean Geometry: Hausdorff-Gromov distances, Graph Neural Networks. 
  * Unsupervised Learning under Geometric Priors (Implicit vs explicit models, microcanonical, transportation metrics).
  * Applications and Open Problems: adversarial examples, graph inference, inverse problems.

* Part II: Geometry of Optimization and Generalization
  * Stochastic Optimization (Robbins & Munro, Convergence of SGD) 
  * Stochastic Differential Equations (Fokker-Plank, Gradient Flow, Langevin Dynamics, links with SGD; open problems) 
  * Information Geometry and Optimal Transport (Amari, Fisher-Rao metric, Wasserstein) 
  * Reproducing Kernel Hilbert Spaces 
  * Landscape of Deep Learning Optimization (Tensor/Matrix factorization, Deep Nets; open problems). 
  * Generalization in Deep Learning. 


## Pre-requisites

Multivariate Calculus, Linear Algebra, Probability and Statistics at solid undergraduate level.

Notions of Harmonic Analysis, Differential Geometry and Stochastic Calculus are nice-to-have, but not essential.

## Grading

The course will be graded with a final research project plus a participation grade. 
Details TBA. 

## Lectures

| Week        | Lecture Date           | Topic       |  References                     |
| ---------------|----------------| ------------|---------------------------|
| 1 | 1/23  | **Lec1** Introduction: The Curse of Dimensionality in ML [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture1.pdf) |  [References](doc/refs.md#lec1)  |
| 2 | 1/30  | **Lec2** Euclidean Geometric Stability. Scattering Transforms. Convolutional Neural Nets |  [References](doc/refs.md#lec2)  |
| 3 | 2/6  | **Guest** TBA |  [References](doc/refs.md#lec3)  |
| 4 | 2/13  | **Lec3** Non-Euclidean Geometric Stability. Gromov-Hausdorff distances. Graph Neural Nets |  [References](doc/refs.md#lec3)  |
| 5 | 2/20  | **Lec4** Unsupervised Learning under Geometric Priors. Implicit vs Explicit models. Optimal Transport models. Microcanonical Models.   |  [References](doc/refs.md#lec4)  |
| 6 | 2/27  | **Lec5** Applications and Open Problems. End of Part I.  |  [References](doc/refs.md#lec5)  |
| 7 | 3/6  | **Lec6** Stochastic Optimization. Convergence properties (or lack thereof).   |  [References](doc/refs.md#lec6)  |
| 8 | 3/13  | **Spring Break**  |  [References](doc/refs.md#lec8)  |
| 9 | 3/20  | **Lec7** Discrete vs Continuous Time Optimization. Fokker-Plank. Langevin Dynamics.  |  [References](doc/refs.md#lec7)  |
| 10 | 3/27  | **Lec8** Landscape of Deep Learning Optimization. Tensor factorization |  [References](doc/refs.md#lec8)  |
| 11 | 4/3  | **Lec9** Landscape of Deep Learning Optimization (cont'd). |  [References](doc/refs.md#lec9)  |
| 12 | 4/10  | **Lec10** Information Geometry. |  [References](doc/refs.md#lec10)  |
| 13 | 4/17  | **Lec11** Reproducing Kernel Hilbert Spaces |  [References](doc/refs.md#lec11)  |
| 14 | 4/24  | **Lec12** Optimal Transport in ML. Adversarial Training |  [References](doc/refs.md#lec12)  |
| 15 | 5/1  | **Lec13** Generalization. Review of Rademacher complexity. Stability. |  [References](doc/refs.md#lec13)  |



### Lab sessions / Parallel Curricula

## AlphaGoZero living document: https://goo.gl/iFZ4XD

* Class 2: Multi-Armed Bandits and Upper Confidence Bounds
  * Motivation: Bandits and UCB are key components of how MCTS was originally formalized. The node selection during the search is achieved through the UCB approach, which is analogues to how its performed in a multi-armed bandit scenario.
  * Required Reading: 
    * Sutton: Sections 2.1 - 2.6 (Find on newclasses.nyu.edu in the class materials)
    * Jeremy Kun: Optimizing in the Face of Uncertainty
  * Optional Reading:
    * Original UCB1 Paper
    * UW Lecture Notes
  * Questions:
    * Sutton Exercises 2.1, 2.2, 2.4, 2.5
    * Sutton: What are the pros and cons of the optimistic initial values method?
    * Kun: In the proof for the expected cumulative regret of UCB1, why is delta(T) a trivial regret bound if the deltas are all the same?
    * Kun: Do you understand the argument for why the regret bound is O(sqrt(KTlog(T)))?
    * Can you reproduce the UCB1 algorithm?

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


