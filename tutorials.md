---
layout: index
title: Tutorials
---

A collection of tutorials/books/reading lists/courses that might help.

- Tutorials
	* General Tutorials
		* [Stephane Caron's tutorials on Robotics](https://scaron.info/category/teaching.html).
		* [Shuo Yang's tutorial on Robotics](https://zhuanlan.zhihu.com/p/22266788).
		* [GitBook: How to learn Robotics](https://qiu6401.gitbook.io/how-to-learn-robotics/).
	* Mini Tutorials
	    * [Crash course on Lie theory](https://arxiv.org/abs/1812.01537).
	* Tools
		* [A great tutorial for MATLAB and Simulink](http://ctms.engin.umich.edu/CTMS/index.php?aux=Home)

- Websites
	* Steve LaValle's [website](http://lavalle.pl/).
	* Arkadi Nemirovski is a big name in the convex optimization community. His [website](https://www2.isye.gatech.edu/~nemirovs/) has some amazing contents including books and lecture notes on convex optimizations. I think his [book](https://www2.isye.gatech.edu/~nemirovs/lmco_run.pdf) and [lecture notes](https://www2.isye.gatech.edu/~nemirovs/LMCOLN2020WithSol.pdf) on modern convex optimization is brilliantly unique and helpful. I am currently going through the lecture notes.

- Conference Proceedings
	* [RSS](http://www.roboticsproceedings.org/)
	* ICRA: [[2020]](https://github.com/PaoPaoRobot/ICRA2020-paper-list) [[2019]](https://github.com/PaoPaoRobot/ICRA2019-paper-list)
	* IROS: [[2020]](https://github.com/PaoPaoRobot/IROS2020-paper-list) [[2019]](https://github.com/PaoPaoRobot/IROS2019-paper-list)

- Software
    * [Klampt](http://motion.cs.illinois.edu/klampt/)
    * [OMPL](https://ompl.kavrakilab.org/index.html)
    * [DART](https://dartsim.github.io/)
	
- Courses:
    * [Course of Study from CMU](https://www.ri.cmu.edu/wp-content/uploads/2018/08/COSAug2018.pdf)
	* Optimization
		* [Stephen Boyd's home page](https://stanford.edu/~boyd/people.html).
    
    * Robotics
		* [CMU 16-741 Mechanics of Manipulation](http://www.cs.cmu.edu/afs/cs/academic/class/16741-s07/www/).
		* [CMU 16-811 Math Fundamentals for Robotics](http://www.cs.cmu.edu/~me/courses/811/mathfund.html).

	* Others
		* [Introduction to Computing with Geometry](https://pages.mtu.edu/~shene/COURSES/cs3621/NOTES/). A good reference for Bezier curve, B-spline and NURBS.

- Books
	* Optimization
		* [Numerical Optimization](https://www.amazon.com/Numerical-Optimization-Operations-Financial-Engineering/dp/0387303030/ref=sr_1_1?keywords=numerical+optimization&qid=1555876008&s=gateway&sr=8-1) by Jorge Nocedal and Wright.
		* [Convex Optimization](https://www.amazon.com/Convex-Optimization-Corrections-2008-Stephen/dp/0521833787/ref=sr_1_1?keywords=convex+optimization&qid=1555876044&s=gateway&sr=8-1) by Stephen Boyd and L. Vandenberghe.
	* Motion Planning
	* State Estimation

- Thesis
	PhD/Master thesis tend to be very good portals to a specific research topics. Here is a collection of what might help.
	* [OSQP](https://osqp.org/) is a pretty fast QP solver, which is also a good application of the [ADMM](https://stanford.edu/~boyd/admm.html) algorithm.
	* [ECOS](https://www.research-collection.ethz.ch/handle/20.500.11850/74559), an embedded interior-point solver.

- Surveys
	* [An introduction on mixed-integer nonlinear optimization](https://www.mcs.anl.gov/papers/P3060-1112.pdf) by Pietro Belotti et al..

- Reading Lists
	* [On manipulation](https://nima-fazeli.github.io/Reading%20List/) by Nima Frazeli.
	* [On manipulation](https://mp.weixin.qq.com/s/S6TvqppQHQ6RFmb-_wVkGA) by Jiaji Zhou.

- Technical Writing
	* [Common Errors in Technical Writing](https://www.ece.ucdavis.edu/~jowens/commonerrors.html) by John Owens.
	* [LaTex Templates](https://github.com/OxDuke/latex_templates) by [Stephen Boyd](http://web.stanford.edu/~boyd/).
	* [Mathematical Writing](http://jmlr.csail.mit.edu/reviewing-papers/knuth_mathematical_writing.pdf) by Kunth et al..

## Miscellaneous things sorted by subjects

Here I would like to keep a list of references not directly related to Robotics but lay the foundation of, or at least somewhat related to the algorithmic aspect of Robotics. This list will be updated irregularly.

### Numerical methods
- [Numerical Linear Algebra](https://www.amazon.com/Numerical-Linear-Algebra-Lloyd-Trefethen/dp/0898713617/ref=sr_1_1?dchild=1&keywords=numerical+linear+algebra&qid=1599564453&sr=8-1) by Trefethen and Bau is my go-to textbook on dense linear algebra solvers.

- [Direct Methods for Sparse Linear Systems](https://my.siam.org/Store/Product/viewproduct/?ProductId=842) by Tim Davis is my go-to reference on sparse linear algebra solvers. 

- I have had the pleasure to read [Lloyd N. Trefethen](http://people.maths.ox.ac.uk/trefethen/)'s [Approximation Theory and Approximation Practice](https://my.siam.org/Store/Product/viewproduct/?ProductId=31254869) and [Exploring ODEs](http://people.maths.ox.ac.uk/trefethen/Exploring.pdf). I would give my full recommendation to those who found the topics interesting.

### Optimization

- Dimitri Bertsekas has a ton of amazing books and papers, but quite unfortunately I am not quite a fan of his style.

#### Convex Optimization

- See [Convex Optimization](https://www.amazon.com/Convex-Optimization-Corrections-2008-Stephen/dp/0521833787/ref=sr_1_1?keywords=convex+optimization&qid=1555876044&s=gateway&sr=8-1) [[PDF](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)] by S. Boyd and L. Vandenberghe for a basic overview of convex optimization. The book is clearly written and well understandable. It also has lecture videos that can be easily found on Youtube, which is a delight to watch.

- Beyond the basics, here are a few of my interests: distributed optimization, optimization on non-smooth and non-differentiable convex problems and high-speed solver implementations.

- [Proximal Algorithms](https://web.stanford.edu/~boyd/papers/pdf/prox_algs.pdf) by Neal Parikh and Stephen Boyd.

- ADMM is an old algorithm and has seen a recent revival probably due to the need for large-scale distributed optimization. See [Distributed Optimization and Statistical Learning via the Alternating Direction Method of Multipliers](https://web.stanford.edu/~boyd/papers/pdf/admm_distr_stats.pdf) by S. Boyd et al. for a modern introduction. A talk by Boyd: [link](https://www.youtube.com/watch?v=Xg0ozgCXXB8&ab_channel=MicrosoftResearch).

- There is a new book (as of September, 2020) coming up dealing with convex optimization: [Algorithms for Convex Optimization](https://convex-optimization.github.io/) by Nisheeth K. Vishnoi. I will take some time to go through the book. The author also has some interesting [blogs](https://nisheethvishnoi.wordpress.com/).

#### Nonlinear Optimization

- See [Numerical Optimization](https://www.amazon.com/Numerical-Optimization-Operations-Financial-Engineering/dp/0387303030/ref=sr_1_1?keywords=numerical+optimization&qid=1555876008&s=gateway&sr=8-1) by J. Nocedal and Wright for an overview of the general optimization.

### Game Physics

### Computer Graphics
I am a completely freshly green new babie to the CG world, I would like to keep a list of things that helped me the most during my CG journey.


