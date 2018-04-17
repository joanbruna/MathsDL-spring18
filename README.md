# MathsDL-spring18
Topics course Mathematics of Deep Learning, NYU, Spring 18. CSCI-GA 3033. 

## Logistics

* Tuesdays from 7.10pm-9pm. CIWW 102

* Tutoring Session with Parallel Curricula (**optional**): Fridays 11am-12:30pm CIWW 101. The first week **only** it is 10:30am-12pm.

* Piazza: [sign-up here](https://piazza.com/nyu/spring2018/csciga3033)

* Office Hours: Tuesdays 9:30am-11:00am

## Instructors

__Lecture Instructor__: Joan Bruna (bruna@cims.nyu.edu)

__Tutor (Parallel Curricula)__: Cinjon Resnick (cinjon@nyu.edu)


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

The course will be graded with a final project -- consisting in an in-depth survey of a topic related to the syllabus,
plus a participation grade. The detailed abstract of the project will be graded at the mid-term. 

## Lectures

| Week        | Lecture Date           | Topic       |  References                     |
| ---------------|----------------| ------------|---------------------------|
| 1 | 1/23  | **Lec1** Introduction: The Curse of Dimensionality in ML [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture1.pdf) |  [References](doc/refs.md#lec1)  |
| 2 | 1/30  | **Lec2** Euclidean Geometric Stability. [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture2.pdf) |  [References](doc/refs.md#lec2)  |
| 3 | 2/6  | **Guest Lecture: Leon Bottou (Facebook/NYU)** [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/bottou-02.06.2018.pdf)  |  [References](doc/refs.md#lec3)  |
| 4 | 2/13  | **Lec3** Scattering Transforms and CNNs [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture3.pdf) |  [References](doc/refs.md#lec3)  |
| 5 | 2/20  | **Lec4** Non-Euclidean Geometric Stability. Gromov-Hausdorff distances. Graph Neural Nets [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture4.pdf)|  [References](doc/refs.md#lec4)  |
| 6 | 2/27  | **Lec5** Graph Neural Network Applications [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture5.pdf) |  [References](doc/refs.md#lec5)  |
| 7 | 3/6  | **Lec6** Unsupervised Learning under Geometric Priors. Implicit vs Explicit models. Optimal Transport models. Microcanonical Models. Open Problems [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture6.pdf)  |  [References](doc/refs.md#lec6)  |
| 8 | 3/13  | **Spring Break**  |  [References](doc/refs.md#lec8)  |
| 9 | 3/20  | **Lec7** Discrete vs Continuous Time Optimization. The Convex Case. [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture7.pdf)   |  [References](doc/refs.md#lec7)  |
| 10 | 3/27  | **Lec8** Discrete vs Continuous Time Optimization. Stochastic and Non-convex case [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture8.pdf) |  [References](doc/refs.md#lec8)  |
| 11 | 4/3  | **Lec9** Gradient Descent on Non-convex Optimization. [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture9.pdf) |  [References](doc/refs.md#lec9)  |
| 12 | 4/10  | **Lec10** Gradient Descent on Non-convex Optimization. Escaping Saddle Points efficiently. [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture10.pdf) |  [References](doc/refs.md#lec10)  |
| 13 | 4/17  | **Lec11** Landscape of Deep Learning Optimization. Spin Glasses, Kac-Rice, RKHS, Topology. [Slides](https://github.com/joanbruna/MathsDL-spring18/blob/master/lectures/lecture11.pdf) |  [References](doc/refs.md#lec11)  |
| 14 | 4/24  | **Lec12** **Guest Lecture: Behnam Neyshabur (IAS/NYU): Generalization in Deep Learning** |  [References](doc/refs.md#lec12)  |
| 15 | 5/1  | **Lec13** Stability. Open Problems. |  [References](doc/refs.md#lec13)  |



### Lab sessions / Parallel Curricula

## DeepStack living document: https://goo.gl/zzMzoz

* Resources:
  * MAS: [Multi Agent Systems](http://www.masfoundations.org/mas.pdf)
  * LT: [Marc Lanctot’s Thesis](http://mlanctot.info/files/papers/PhD_Thesis_MarcLanctot.pdf)
  * ICRM: [Introduction to Counterfactual Regret Minimization](http://modelai.gettysburg.edu/2013/cfr/cfr.pdf**)
  * PLG: [Prediction, Learning, and Games](http://www.ii.uni.wroc.pl/~lukstafi/pmwiki/uploads/AGT/Prediction_Learning_and_Games.pdf)
  
* Class 5: Counterfactual Regret Minimization #2
  * Motivation: We saw last week the practical side of CFR and how effective it 
  can be. This week we’ll be diving more into the theory underlying it. This 
  will culminate with Blackwell’s Approachability Theorem, a generalization of 
  repeated two-player zero-sum games.
  * Required:
    * PLG: Section 7.3-7.7, 7.9
  * Optional:
    * [A Simple Adaptive Procedure Leading to Correlated Equilibrium](http://wwwf.imperial.ac.uk/~dturaev/Hart0.pdf) --> Important originating paper.
    * [Prof. Johari's 2007 Class - 13](http://web.stanford.edu/~rjohari/teaching/notes/336_lecture13_2007.pdf)
    * [Prof. Johari's 2007 Class - 14](http://web.stanford.edu/~rjohari/teaching/notes/336_lecture14_2007.pdf)
    * [Prof. Johari's 2007 Class - 15](http://web.stanford.edu/~rjohari/teaching/notes/336_lecture15_2007.pdf)
    
* Class 4: Counterfactual Regret Minimization #1
  * Motivation: Counterfactual Regret Minimization (CFR) is only a decade old 
  but has already achieved huge success as the foundation underlying DeepStack 
  and Libratus. In the first of two weeks dedicated to CFR, we learn how it 
  works algorithmically.
  * Required Reading:
    * ICRM: 2.1-2.4, 3.1-3.4
    * LT: 2.2
    * Original Paper --> [Regret Minimization in Games with Incomplete Information](http://poker.cs.ualberta.ca/publications/NIPS07-cfr.pdf)
  * Optional Reading: The two below are CFR extensions used in DeepStack.
    * CFR-D --> [Solving Imperfect Information Games Using Decomposition](https://pdfs.semanticscholar.org/8216/0cbdcbeb13d53db85da928d8c42a789fdd69.pdf)
    * CFR+ --> [Solving Large Imperfect Information Games Using CFR+](https://arxiv.org/pdf/1407.5042.pdf)
  * Questions:
    * What is the difference between internal regret, external regret, and counterfactual regret?
    * Implement CFR (or CFR+ / CFR-D) in your favorite programming language to play Leduc Poker or Liar’s Dice. 
    * How do you know if you’ve implemented CFR correctly?

* Class 3: Extensive-Form Games
  * Motivation: What happens when players don't act simultaneously? Extensive-Form Games are an answer to this question. While this representation of a game always has a comparable Normal-Form, it's much more natural to reason about in this format.
  * Required Reading:
    * MAS 5.1.{1,2,3}
    * MAS 5.2.{1,2,3}
    * [Accelerating Best Response Calculation in Large Extensive Games](http://martin.zinkevich.org/publications/ijcai2011_rgbr.pdf) --> Important for understanding how to evaluate Poker algorithms.
  * Optional Reading: 
    * LT Section 2.1.2
  * Questions:
	  * What is the intuition for why not all normal form games can be transformed into perfect-form extensive games?
	  * How are the set of behavioral strategies different from the set of mixed strategies?
	  * Succinctly describe the technique demonstrated in the Accelerating Best Response paper.

* Class 2: Optimality and Equilibrium 
  * Motivation: How do you reason about games? The best strategy in multi-agent scenario depends on the choices of others. Game theory deals with this problem by identifying subsets of outcomes called solution concepts, of which fundamental ones are the Nash Equilibrium, Pareto Optimality, and Correlated Equilibrium.
  * Required Reading:
    * MAS Sections 3.3, 3.4.5, 3.4.7, 4.1, 4.2.4, 4.3, 4.6
    * LT Section 2.1.1
  * Optional Reading:
    * The rest of section 3.4 in MAS.
  * Questions:
    * Why must every game have a Pareto Optimal strategy?
    * Why must there always exist at least one Pareto Optimal Strategy in which all players adopt pure strategies?
    * Why in common-payoff games do all Pareto optimal strategies have the same payoff?
    * Why does definition 3.3.12 imply that the vertices of a simplex must all receive different labels?
    * Why in definition 3.4.12 does it not matter that the mapping is to pure strategies rather than a mixed strategy?
    * Take your favorite normal-form game, find a Nash Equilibrium, and then find a corresponding Correlated Equilibrium.

* Class 1: Normal-Form Games & Poker
  * Motivation: Normal-Form games are the backbone for many of the techniques that later were used in DeepStack and Libratus. Understanding them will be a necessary foundation to understanding the innovations they presented.
  * Required Reading:
    * MAS sections 3.1 & 3.2
    * LT pages 5-7
    * [The Game of Poker](https://arxiv.org/pdf/1701.01724.pdf) (Supplementary #1 on pages 16-17)
  * Optional Reading:
    * [The State of Solving Large Incomplete-Information Games, and Application to Poker](https://www.cs.cmu.edu/~sandholm/solving%20games.aimag11.pdf) (2010)
    * [Why Poker is Difficult](https://www.youtube.com/watch?v=2dX0lwaQRX0) (very good video by Noam Brown, the main author on Libratus. The first 18 minutes are most relevant for now.)
  * Questions:
    * Prove that in a zero-sum game, the nash equilibrium strategies are interchangeable. (LT)
    * Prove that in a zero-sum game, the expected payoff to each player is the same for every equilibrium. (LT)
    * Can you prove Lemma 3.1.6?
    * Can you prove Theorem 3.1.8 (which is a really cool result)? 


## AlphaGoZero living document: https://goo.gl/iFZ4XD

* Class 6: The Paper
  * Motivation: Let's read the paper!
  * Required Reading:
    * [Mastering the Game of Go Without Human Knowledge](https://www.dropbox.com/s/yva172qos2u15hf/2017-silver.pdf?dl=0)
    * [Thinking Fast and Slow with Deep Learning and Tree Search](https://arxiv.org/pdf/1705.08439.pdf)
  * Optional Reading:
    * [Deep Learning for Real-Time Atari Game Play Using Offline Monte-Carlo Tree Search Planning](http://papers.nips.cc/paper/5421-deep-learning-for-real-time-atari-game-play-using-offline-monte-carlo-tree-search-planning.pdf)
    * [Silver Thesis](http://papersdb.cs.ualberta.ca/~papersdb/uploaded_files/1029/paper_thesis.pdf): Section 4.6
    * [Mastering the game of Go with deep neural networks and tree search](https://storage.googleapis.com/deepmind-media/alphago/AlphaGoNaturePaper.pdf)
    * [Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm](https://arxiv.org/abs/1712.01815)
  * Questions:
    * What were the differences between "Mastering the Game of Go ..." and "Thinking Fast and Slow ..."?
    * What was common to both "Mastering the Game of Go ..." and "Thinking Fast and Slow ..."?

* Class 5: MCTS & RL
  * Motivation: Up to this point, we’ve learned a lot about how games can be solved and how RL works on a foundational level. Before we jump into the paper, one last foray contrasting and unifying the games vs learning perspective is worthwhile for understanding the domain more fully.
  * Required Reading:
    * [Vodopivec](http://www.jair.org/media/5507/live-5507-10333-jair.pdf): 
      * Connection between MCTS and RL → 3.1-3.4
      * Integrating MCTS and RL → 4.1-4.3
    * [Why did TD-Gammon Work?](https://papers.nips.cc/paper/1292-why-did-td-gammon-work.pdf)
  * Optional Reading:
    * Vodopivec: Survey of research inspired by both fields → 5.
  * Questions:
    * What are key differences between MCTS and RL?
    * UCT can be described in RL terms as the following “The original UCT searches identically as an offline on-policy every-visit MC control algorithm that uses UCB1 as the policy.” What do each of these terms mean?
    * What is a Representation Policy? Give an example not described in the text.
    * What is a Control Policy? Give an example not described in the text.

* Class 4: MCTS & UCT
  * Motivation: Monte Carlo Tree Search (MCTS) forms the backbone of AlphaGoZero. It’s what lets it reliably explore and then hone in on the best policy. UCT (UCB for Trees) builds on top of what we’ve been learning and, paired with MCTS, is integral to the training process.
  * Required Reading:
    * [Sutton](http://incompleteideas.net/book/bookdraft2017nov5.pdf): Section 8.11
    * [Browne](https://gnunet.org/sites/default/files/Browne%20et%20al%20-%20A%20survey%20of%20MCTS%20methods.pdf): Sections 2.2, 2.4, 3.1-3.5, 8.2-8.4.
    * [Silver Thesis](http://papersdb.cs.ualberta.ca/~papersdb/uploaded_files/1029/paper_thesis.pdf): Sections 1.4.2 and 3.
  * Optional Reading:
    * [Jess Hamrick on Browne](http://jhamrick.github.io/quals/planning%20and%20decision%20making/2015/12/16/Browne2012.html).
    * [Original MCTS Paper](https://hal.archives-ouvertes.fr/file/index/docid/116992/filename/CG2006.pdf).
    * [Original UCT Paper](http://ggp.stanford.edu/readings/uct.pdf).
    * Browne: 
      * 4.8: MCTS applied to Stochastic or Imperfect Information Games.
      * 7.2, 7.3, 7.5, 7.7: Applications of MCTS.
  * Questions:
    * Can you detail each of the four parts of the MCTS algorithm?
    * What characteristics make MCTS a good choice?
    * What are examples of domain knowledge default policies in Go?
    * Why is UCT optimal? Can you prove that the failure probability at the root converges to zero at a polynomial rate in the number of games simulated?

* Class 3: Policy and Value Functions
  * Motivation: The Policy and Value Functions are at the core of Reinforcement Learning. The Policy function is the set of probabilities you give to each possible move. The Value function is your estimate of how good is the current state. In AlphaGoZero, a single network calculates both a value and a policy, then later updates its weights based off of the difference between those figures and the empirical results.
  * Required Reading (note: Sutton from here out refers to the [final version](http://incompleteideas.net/book/bookdraft2017nov5.pdf). Make sure it says COMPLETE DRAFT):
    * Value Function:
      * Sutton 3.5, 3.6, 3.7
      * Sutton: 9.1, 9.2, 9.3 (important!)
    * Policy Function:
      * Sutton: 4.1, 4.2, 4.3
      * Sutton: 13.1, 13.2 (important!), 13.3, 13.4
  * Optional Reading:
    * Sergey Levine: [Berkeley Fall'17: Policy Gradients](https://www.youtube.com/watch?v=tWNpiNzWuO8&feature=youtu.be) →  This is really good.
    * Sergey Levine: [Berkeley Fall'17: Value Functions](https://www.youtube.com/watch?v=k1vNh4rNYec&feature=youtu.be) → This is really good.
    * [Karpathy does Pong](http://karpathy.github.io/2016/05/31/rl/).
    * [David Silver on PG](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching_files/pg.pdf).
    * [David Silver on Value](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching_files/FA.pdf).
  * Questions:
    * Why does policy gradient have such high variance?
    * What is the difference between off-policy and on-policy?
    * Sutton:
      * 3.13: What is the Bellman equation for action values, that is, for qπ? ...
      * 3.14: In the gridworld example … are the signs of these rewards important, or only the intervals between them? Prove ...
      * 3.15: Now consider adding a constant c to all the rewards in an episodic task … would this have any effect, or would it leave the task unchanged as in the continuing task above? Why or why not? Give an example. 
      * 3.20: Give the Bellman equation for q∗ for the recycling robot. 
      * 4.3: What are the equations analogous to (4.3), (4.4), and (4.5) for the action-value function qπ and its successive approximation by a sequence of functions q0, q1, q2, . . . ? 
      * 4.6 (important!): How would policy iteration be defined for action values? Give a complete algorithm for computing q∗, analogous to that on page 65 for computing v∗. Please pay special attention to this exercise, because the ideas involved will be used throughout the rest of the book. 
      * 13.2 (important!): Prove (13.7) using the definitions and elementary calculus.
    
* Class 2: Multi-Armed Bandits and Upper Confidence Bounds
  * Motivation: Bandits and UCB are key components of how MCTS was originally formalized. The node selection during the search is achieved through the UCB approach, which is analogues to how its performed in a multi-armed bandit scenario.
  * Required Reading: 
    * Sutton: Sections 2.1 - 2.6 (Find on newclasses.nyu.edu in the class materials)
    * [Jeremy Kun: Optimizing in the Face of Uncertainty](https://jeremykun.com/2013/10/28/optimism-in-the-face-of-uncertainty-the-ucb1-algorithm/)
  * Optional Reading:
    * [Original UCB1 Paper](https://homes.di.unimi.it/~cesabian/Pubblicazioni/ml-02.pdf)
    * [UW Lecture Notes](https://courses.cs.washington.edu/courses/cse599s/14sp/scribes/lecture15/lecture15_draft.pdf)
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


