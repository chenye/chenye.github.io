---
layout: post
title: "ACS4Fun: An Ant Colony System for General Function Optimization"
excerpt: "This code solves function minimization problems. It was first wrote in 2003 with some minor updates."
date: 2015-09-05 11:46:00
categories: projects
tags: [projects, ant colony optimization, optimization]
comments: true
share: true
---

This is a C++ code that was developed to find the solution(s) that minimize any given general function of real variables. It was first developed in 2003 and a related paper was published in 2004 (in Chinese). Although it is an old code and the performance of the algorithm is not as good as the state-of-the-art algorithms, it could still be used by people with a non-optimization background to solve many function optimization problems.

The `main.cpp` contains a simple example of how to use the code.

{% highlight C++ %}
CACS4Fun acs;

acs.alpha=0.2;      // alpha in pheromone global update rule
acs.num_ants=20;    // number of ants to be used to search the solution space
acs.num_iters=500;  // number of iteration
acs.num_layers=60;  // number of layers or number of digits to encode a solution
acs.dimension=10;   // dimension of the solutions, using 60 layers to encode 10 dimension means
	                    // 6 layers/digits are used to represent one dimension, or one real number
acs.p0=0.8;         // the probability of using pseudo-propotional selection method
acs.rho=0.2;        // rho is used in pheromone local update rule
acs.tau0=0.01;      // initial value for the pheromone intensities
	
acs.allocate_vars();
acs.start();
	
{% endhighlight %}

