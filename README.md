**Pacmann AI**

# The Algorithm employs A/B Testing to estimate causal dynamic effects with the help of reinforcement Learning

[@github:zulkarnainprastyo](https://github.com/zulkarnainprastyo), [@medium:Zulkarnain Prastyo](https://medium.com/@zulkarnain.prastyoumb23093)

## Table of Contents

* [Introduction and Background](#introduction-and-background)
* [Setting Up Problem](#setting-up-problem) 
* [Designing Experiments](#designing-experiments)
* [Analyzing and Interpreting the Data](#analyzing-and-interpreting-the-data)
* [Conclusion and Recommdentation](#conclusion-and-recommdentation)
* [References](#references)

# Outline

# Project Background 
The main objective of the experimental design and A/B testing course is to prepare you in making experimental designs and conducting A/B testing and conducting A/B testing to solve a problem.

Through this project, you will be asked to
 * Create an A/B testing plan
 * Perform A/B testing analysis from the given dataset

# Project Stages
    Stage #1 - Choose Cases
    Stage #2 - Setting Up Problem
    Stage #3 - Designing Experiments
    Stage #4 - Running Experiment and Obtaining Data
    Stage #5 - Analyzing and Interpreting the Data
    Stage #6 - Make Conclusion and Recommedentation
    Stage #7 - Make Easy Report and Presentation

# Outcome Project
1. Code
2. Easy Report
3. Presentation

# Format Easy Report Project
 1. Introduction and Background
    * Explain the case and the problem that you want to solve
A/B testing, or online experimentation, is a standard business strategy for comparing new products to old products in the pharmaceutical, technology, and traditional industries. A major challenge arises in online experiments with two-sided marketplace platforms (e.g. Lyft, Uber, Curb) where only one unit receives a series of treatments over time. In these experiments, treatment at a given time affects current outcomes as well as future outcomes. This paper aims to introduce a reinforcement learning framework for A/B testing in these experiments while characterizing long-term treatment effects. The testing procedure I propose allows for sequential monitoring and online updates. It is universally applicable to various process designs in different industries. In addition, I systematically investigate the theoretical properties (e.g., size and power) of my testing procedure. Finally, I apply my framework to simulated data and a real data example obtained from a technology company to illustrate its advantages over current practice.



 2. Setting Up Problem
    * Describe according to the stages described in the previous stage

 3. Designing Experiments
    * Describe according to the stages described in the previous stage

 4. Analyzing and Interpreting the Data
    * Ensure the trushworthiness
        * check the data quality (missing value, duplicate data, distribution of data)
        * perform SRM test with chi-square test
    * Result of the hypothesis testing
    * Confidence interval for estimate the difference between treatment and control

 5. Conclusion and Recommdentation
    * Make a summary with
        * The conclusion from the previous analysis
        * Recommendations for the business
        * Recommendation for the next experiment

 6. References
    * It contains references that you use.
    * Remember, plagiarism is highly avoided

Overview
* python/: This folder contains all of the Python code that was used in the numerical experiments.
   * For one experiment, conf.py sets the true parameters and functions used in the estimate. To represent one numerical experiment, I utilize the key of a Python dict.
   * main.py is a command-line-only entry point. To start a new experiment, type python main.py 0, and to see the result, type python main.py 1. 
   * _analyzer.py contains functions for making tables and drawing plots. 
   * _monitor.py is a platform for realizing the algorithm in my paper, which includes the estimation and hypothesis test parts.
* data/: This folder contains raw results and images from each experiment.
   * The names of raw findings are similar to.json.
