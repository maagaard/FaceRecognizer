# Advanced Machine Learning 02460 - Project
## Project meeting - Week 6
**14-04-2016**


# Progress since last time
-  We can visualize the margin of a specific point
-  We have started to look at the KISSME dataset and found problematic consequences of the size
    - Time: we have eliminated the expensive trace function saving aproximately 1/2-1/3 running time
    - Space: The C matrix is incredible large, we have mailed Søren concerning this problem 


# Today
- Simple classification using KNN with a metric learned by our LMNN algorithm of the Fisher's Iris data set: 
  - 120 of the samples were used for training and 30 samples for testing. Out of the 30 test samples, 4 were misclassified in this instance:
  ![classification]
- Improvement of LMNN by removing calculations where result was never used


# Sketch of report plan
- Motivation/Short description
- Describe algorithm
   - Targets
   - Impostors
   - Push / pull
   - loss function
- Simple results w. fisher iris
   - Scaling, margin targets
   - Solution of this problem
   - Different heuristics (l1 norm)

- Active sets
   - 

- The KissMe dataset
  - Description of dataset
      - We cannot be sure to have K target neighbours
      - Duplicates???
  - Problem which we will solve
  - Results


# Discussions
- Memory problems
- Duplicates in KissMe if not enough neigbours


# Work for next week. 
- 


[classification]: /images/LMNN_classification_fisher_w6.png