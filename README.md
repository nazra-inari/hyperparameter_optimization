# Hyperparameter Optimization (Incl. Bayesian Optimization)

![Hyperparameter Optimization (Incl. Bayesian Optimization)](./imgs/title_img.png)

Hyperparameter optimization is a crucial skill required to train a good machine learning model. This guide explains hyperparameters from the ground up and will showcase detailed examples and walkthroughs for the tools we have at our disposal (incl. Bayesian Optimization) to try and select the best values for them.

Table of Contents
* What are Hyperparameters?  
* Examples and types of Hyperparameters  
* Which hyperparameters should you tune?  
* How do you tune hyperparameters?  
* The challenge of hyperparameter tuning  
* Tuning Strategies  
* Load and split the data  
* Train a base model  
* Isolated Experimental Based Hyperparameter Optimization  
  * Single Validation Set
    * Tuning max_depth
      * Visualize the results
    * Tuning min_samples_split
      * Visualize the results
  * k-Fold Cross Validation
    * Tuning max_depth
      * Visualize the results
    * Tuning min_samples_split
      * Visualize the results
    * Tuning multiple hyperparatmeters simultaneously
      * Visualize the results
  * Grid Search
  * Random Search
* Sequential Model Based Optimization (SMBO)
  * Bayesian Optimization
    * Surrogate Model
    *  Acquisition or Selection Function
    * How does it work?
    * Visualizing Bayesian Optimization
    * Example of Bayesian Optimization
