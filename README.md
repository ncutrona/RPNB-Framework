# Bayesian Regularized Iterative Soft Thresholding Algorithm


The BARISTA repository is a dedicated codebase to work recently submitted to the NeurIPS 2023 Conference. This readme file will contain the paper abstract, a link to the data used for experimentation, and a python notebook with dedicated instructions on how to use our algorithm.


### Paper Abstract

Weighted Naive Bayes methods have recently been developed to alleviate the strong conditional independence assumption of traditional Naive Bayes classifiers. In particular, class-specific attribute weighted Naive Bayes (CAWNB) has been shown to yield excellent performance on many modern datasets. Such methods, however, are prone to over-fitting on small sample, large feature space data. In this work, we propose a Bayesian Regularized Iterative Shrinkage-Thresholding Algorithm (\texttt{BARISTA}), which includes both $\ell_1$ and $\ell_2$ regularization to mitigate this problem. As we show, estimating the parameters of \texttt{BARISTA} via maximum likelihood yields a convex objective that can be efficiently optimized using a Fast Iterative shrinkage-thresholding Algorithm (FISTA). The resulting algorithm has many attractive theoretical and numerical properties, including a guaranteed linear rate of convergence. Using several benchmark datasets, we also demonstrate how \texttt{BARISTA} can yield a significant increase in performance compared to many state-of-the-art Bayesian methods.


### Data Access

For now, we direct users to the UCI Machine Learning Repository [link](https://archive.ics.uci.edu/ml/index.php). If this work is accepted, we will release a link to our research group's one-drive that contains already pre-processed data.


### How To Run



