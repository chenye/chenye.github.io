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

The `main.cpp` contains a simple example to use the class `CAcs4Fun` to find the optimal solution of function

\[y = sum{(x_i-0.5)^2}\]

This function is defined in the function `evaluate()` as the default objective function. We can modify the definition to reflect the actual function we want to optimize (Or in a more C++ way, define `evaluate()` as a virtual function and then override it). However, in 

~~~ cpp
CACS4Fun *acs;
acs = new CACS4Fun();
acs->alpha = 0.8;
#=> define
~~~

