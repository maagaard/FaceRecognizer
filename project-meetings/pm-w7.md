# Advanced Machine Learning 02460 - Project
## Project meeting - Week 7
**21-04-2016**


# Progress since last time
 

# Today




# Considerations
- Size of alpha, especially when doing stochastic gradient descent
- Consider saving the indexing *C(i,targets(i,targets(i,:)>0))* in a constant
- Explicit computation of the C-matrix
- New data set! Olivetti face ....

# Report considerations
- This algorithm is not really that suitable for large data sets with large dimensions!
  - Show example calculation of the C-matrix for instance
- Maybe if more information about nearest points are available, many calculations can be omitted
  - Tree structure with reference to points to calculate distance to instead of actual distance?
  