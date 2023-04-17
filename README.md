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

I showing in medium article

 3. Designing Experiments
    * Describe according to the stages described in the previous stage

I showing in medium article

 4. Analyzing and Interpreting the Data
    * Ensure the trushworthiness
        * check the data quality (missing value, duplicate data, distribution of data)
        * perform SRM test with chi-square test
    * Result of the hypothesis testing
    * Confidence interval for estimate the difference between treatment and control

I showing in medium article

 5. Conclusion and Recommdentation
    * Make a summary with
        * The conclusion from the previous analysis
        * Recommendations for the business
        * Recommendation for the next experiment

I showing in medium article

 6. References
    * It contains references that you use.
    * Remember, plagiarism is highly avoided

[1] Johari, R., Pekelis, L., & Walsh, D. J. (2015). Always valid inference: Bringing sequential analysis to A/B testing. arXiv preprint arXiv:1512.04922.

[2] Kharitonov, E., Vorobev, A., Macdonald, C., Serdyukov, P., & Ounis, I. (2015, August). Sequential testing for early stopping of online experiments. In Proceedings of the 38th International ACM SIGIR Conference on Research and Development in Information Retrieval (pp. 473–482).

[3] Johari, R., Koomen, P., Pekelis, L., & Walsh, D. (2017, August). Peeking at a/b tests: Why it matters, and what to do about it. In Proceedings of the 23rd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (pp. 1517–1525).

[4] Yang, F., Ramdas, A., Jamieson, K. G., & Wainwright, M. J. (2017). A framework for multi-a (rmed)/b (andit) testing with online fdr control. Advances in Neural Information Processing Systems, 30.

[5] Rubin, D. B. (1980). Randomization analysis of experimental data: The Fisher randomization test comment. Journal of the American statistical association, 75(371), 591–593.

[6] Zhou, Y., Liu, Y., Li, P., & Hu, F. (2020). Cluster-adaptive network a/b testing: From randomization to estimation. arXiv preprint arXiv:2008.08648.

[7] Rysman, M. (2009). The economics of two-sided markets. Journal of economic perspectives, 23(3), 125–143.

[8] Sutton, R. S., Szepesvári, C., & Maei, H. R. (2008). A convergent O (n) algorithm for off-policy temporal-difference learning with linear function approximation. Advances in neural information processing systems, 21(21), 1609–1616.

[9] Gordon Lan, K. K., & DeMets, D. L. (1983). Discrete sequential boundaries for clinical trials. Biometrika, 70(3), 659–663.

[10] Ertefaie, A. (2014). Constructing dynamic treatment regimes in infinite-horizon settings. arXiv preprint arXiv:1406.0764.

[11] Hu, X., Qian, M., Cheng, B., & Cheung, Y. K. (2021). Personalized policy learning using longitudinal mobile health data. Journal of the american statistical association, 116(533), 410–420.

[12] Liao, P., Qi, Z., Wan, R., Klasnja, P., & Murphy, S. A. (2022). Batch policy learning in average reward markov decision processes. The Annals of Statistics, 50(6), 3364–3387.

[13] Jiang, N., & Li, L. (2016, June). Doubly robust off-policy value evaluation for reinforcement learning. In International Conference on Machine Learning (pp. 652–661). PMLR.

[14] Kallus, N., & Uehara, M. (2022). Efficiently breaking the curse of horizon in off-policy evaluation with double reinforcement learning. Operations Research.
[15] Sutton, R. S., & Barto, A. G. (2018). Reinforcement learning: An introduction. MIT press.

[16] Zhang, B., Tsiatis, A. A., Laber, E. B., & Davidian, M. (2013). Robust estimation of optimal dynamic treatment regimes for sequential treatment decisions. Biometrika, 100(3), 681–694.

[17] Ertefaie, A. (2014). Constructing dynamic treatment regimes in infinite-horizon settings. arXiv preprint arXiv:1406.0764.

[18] Luckett, D. J., Laber, E. B., Kahkoska, A. R., Maahs, D. M., Mayer-Davis, E., & Kosorok, M. R. (2019). Estimating dynamic treatment regimes in mobile health using v-learning. Journal of the American Statistical Association.

[19] Shi, C., Wan, R., Song, R., Lu, W., & Leng, L. (2020, November). Does the markov decision process fit the data: testing for the markov property in sequential decision making. In International Conference on Machine Learning (pp. 8807–8817). PMLR.

[20] Shi, C., Zhang, S., Lu, W., & Song, R. (2022). Statistical inference of the value function for reinforcement learning in infinite-horizon settings. Journal of the Royal Statistical Society Series B: Statistical Methodology, 84(3), 765–793.

[21] Candes, E., Tao, T., et al. (2007). The dantzig selector: Statistical estimation when p is much larger than n. Annals of statistics, 35(6):2313–2351.

[22] Sutton, R. S., & Barto, A. G. (2018). Reinforcement learning: An introduction. MIT press.

[23] Metelkina, A., & Pronzato, L. (2017). Information-regret compromise in covariate-adaptive treatment allocation.

[24] Jennison, C., & Turnbull, B. W. (1999). Group sequential methods with applications to clinical trials. CRC Press.

[25] Luckett, D. J., Laber, E. B., Kahkoska, A. R., Maahs, D. M., Mayer-Davis, E., & Kosorok, M. R. (2019). Estimating dynamic treatment regimes in mobile health using v-learning. Journal of the American Statistical Association.

[26] Ning, Y., & Liu, H. (2017). A general theory of hypothesis tests and confidence regions for sparse high dimensional models.

# Overview
* python/: This folder contains all of the Python code that was used in the numerical experiments.
   * For one experiment, conf.py sets the true parameters and functions used in the estimate. To represent one numerical experiment, I utilize the key of a Python dict.
   * main.py is a command-line-only entry point. To start a new experiment, type python main.py 0, and to see the result, type python main.py 1. 
   * _analyzer.py contains functions for making tables and drawing plots. 
   * _monitor.py is a platform for realizing the algorithm in my paper, which includes the estimation and hypothesis test parts.
* data/: This folder contains raw results and images from each experiment.
   * The names of raw findings are similar to.json.
