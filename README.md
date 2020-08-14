# Fuzzy Clustering Using Hybrid Fuzzy c-means and Fuzzy Particle Swarm Optimization
(A Research Paper Implementation - Paper attached above)

## ABSTRACT

  Fuzzy clustering is an important problem which is the subject of active research in several real world applications. Fuzzy c-means (FCM) algorithm is one of the most popular fuzzy clustering techniques because it is efficient, straightforward, and easy to implement. However FCM is sensitive to initialization and is easily trapped in local optima. Particle swarm optimization (PSO) is a stochastic global optimization tool which is used in many optimization problems. In this paper a hybrid fuzzy clustering method based on FCM and fuzzy PSO (FPSO) is proposed which make use of the merits of both algorithms. Experimental results show that our proposed method is efficient and can reveal encouraging results.

## INTRODUCTION

  Clustering is the process of assigning data objects into a set of disjoint groups called clusters so that objects in each cluster are more similar to each other than objects from different clusters. Clustering techniques are applied in many application areas such as pattern recognition, data mining, machine learning, etc.

### I. FUZZY C-MEANS ALGORITHM
  Fuzzy c-means (FCM) clustering is an effective algorithm, but the random selection in center points makes the iterative process fall into the local optimal solution easily. For solving this problem, recently evolutionary algorithms such as genetic algorithm (GA), simulated annealing (SA), ant colony optimization (ACO), and particle swarm optimization (PSO) have been successfully applied.

### II. PARTICLE SWARM OPTIMIZATION
  Particle Swarm Optimization (PSO) is a population- based optimization tool, which could be implemented and applied easily to solve various function optimization problems, or the problems that can be transformed to function optimization problems.
### A. FUZZY PARTICLE SWARM OPTIMIZATION FOR FUZZY CLUSTERING
  In 2004 a version of particle swarm optimization for TSP called fuzzy particle swarm optimization (FPSO) was proposed. In their proposed method the position and velocity of particles redefined to represent the fuzzy relation between variables.

### III. HYBRID FUZZY C-MEANS AND FUZZY PARTICLE SWARM OPTIMIZATION FOR CLUSTERING PROBLEM
  The FCM algorithm is faster than the FPSO algorithm because it requires fewer function evaluations, but it usually falls into local optima. In this paper, a hybrid fuzzy clustering algorithm based on FCM and FPSO called FCM-FPSO is proposed. FCM-FPSO algorithm applies FCM to the particles in the swarm every number of iterations/generations such that the fitness value of each particle is improved. The experimental results over six real-life data sets indicate the FCM-FPSO algorithm is superior to the FCM algorithm and FPSO algorithm for this problem.

## DATASETS

  For evaluating the FCM, FPSO, and FCM-FPSO methods, six well-known real-world data sets have been considered:
1. Fisher’s iris data set, which consists of three different species of iris flower. For each species, 50 samples with four features were collected;
2. Glass, which consists of 214 objects and 6 different types of glasses. Each type has 9 features;
3. Wisconsin breast cancer data set, which consists of 683 objects and 2 categories characterized by 9 features;
4. Wine, which consists of 178 objects and 3 different types characterized by 13 features;
5. Contraceptive Method Choice (CMC), which consists of 1473 objects and 3 different types characterized by 9 features;
6. Vowel data set, which consists of 871 Indian Telugu vowel sounds, the data set has three features and six overlapping clusters.

  These data sets cover examples of data of low, medium and high dimensions. These algorithms are implemented using R Studio.

## CITATION

Izakian, H., Abraham, A. and Snášel, V., 2009, December. Fuzzy clustering using hybrid fuzzy c-means and fuzzy particle swarm optimization. In 2009 World Congress on Nature & Biologically Inspired Computing (NaBIC) (pp. 1690-1694). IEEE.
