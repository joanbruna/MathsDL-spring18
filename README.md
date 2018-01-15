# MathsDL-spring18
Topics course Mathematics of Deep Learning, NYU, Spring 18. CSCI-GA 3033. 

## Logistics

Tuesdays from 7.10pm-9pm. CIWW 1012

Recitation (**optional**): Fridays 12pm-2pm TBA. 

## Instructors

__Lecture Instructor__: Joan Bruna (bruna@cims.nyu.edu)

__Lab Instructor__: Cinjon Resnik (cinjon@nyu.edu)


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

* Minimax and Alpha-Beta Pruning
  * Knuth: Sections 1-3, 6-7
  * Optional:
    * Alpha-Beta:
      https://chessprogramming.wikispaces.com/Alpha-Beta,
      http://blog.hackerearth.com/minimax-algorithm-alpha-beta-pruning,
      https://www.cs.cornell.edu/courses/cs312/2002sp/lectures/rec21.htm
    * Minimax: 
      https://chessprogramming.wikispaces.com/Minimax
      https://www.youtube.com/watch?v=6ELUvkSkCts
* Multi-Armed Bandits and UCB (Upper Confidence Bound)
  * Sutton 2.1 - 2.6 (Note: would host Sutton)
  * UCB1 Paper: https://homes.di.unimi.it/~cesabian/Pubblicazioni/ml-02.pdf
  * Optional:
    * UCB Paper http://www.jmlr.org/papers/volume3/auer02a/auer02a.pdf
    * UCB1 Write-Up: https://jeremykun.com/2013/10/28/optimism-in-the-face-of-uncertainty-the-ucb1-algorithm/
* Policy and Value functions
  * Value: 
    * Sutton 9.1, 9.2
    * Silver: https://www.youtube.com/watch?v=UoPei5o4fps, 
    * Optional:
      http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching_files/FA.pdf,
      https://people.eecs.berkeley.edu/~pabbeel/cs287-fa11/slides/mdps-intro-value-iteration.pdf
  * Policy:
    * Sutton 13.1, 13.2, 
    * Silver: https://www.youtube.com/watch?v=KHZVXao4qXs
    * Optional: http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching_files/pg.pdf
* MCTS and UCT (UCB applied to trees)
  * Silver Thesis (Note: would host the thesis): 1.4.2 (MCTS), 3.3.2 - 3.3.5 (MCTS), 3.3.6 (UCT)
  * Sutton: 8.7
  * Browne on MCTS: 2.2, 2.4, 3.1, 3.3, 3.4, 8.3
  * Optional & fun —> 7.2, 7.3, 7.5, 7.7
  * Jess Hamrick Summary
  * Optional:
      https://hal.archives-ouvertes.fr/file/index/docid/116992/filename/CG2006.pdf (orig MCTS paper)
      http://ggp.stanford.edu/readings/uct.pdf (UCT paper)
* MCTS & RL
  * http://www.jair.org/media/5507/live-5507-10333-jair.pdf: 3.1-3.3, 4.3-4.5, 
  * Optional: Section 5
* AlphaZero: Putting it all together
  * Silver Thesis: 4.6.1-4.6.3 (history in Go)
  * The Paper (Mastering the Game of Go Without Human Knowledge)
  * Optional:
    http://papers.nips.cc/paper/5421-deep-learning-for-real-time-atari-game-play-using-offline-monte-carlo-tree-search-planning.pdf
  * Thinking Fast and Slow with Tree Search  




