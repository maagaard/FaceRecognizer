# Advanced Machine Learning 02460 - Project
## Supervisor meeting - Week 7
**21-04-2016**

### Agenda
1. Stochastic gradient descent 
    * Talk to Søren about saving the C matrix 
2. 


### Minutes
- Stochastic gradient descent:
    - Sample small amount of data set
    - Maybe not that usable with active sets?
    - Important to update (and "discard") data used for gradient descent after every iteration.
    - 
- Remember to document experiments!
- Create a test script for LMNN on KISSME in order to compare stochastic gradient descent and active set implementation.

- Assumptions for stochastic gradient descent:
    - It is an underlying assumption, that the metric for one part of the data set, will be somewhat similar to other random parts of the data set

- Report:
    - Motivation, why learning a metric is interesting
    - Background material. Other ways of doing this
    - Algorithm, our implementation, have we diverge from the "paper"
    - Lots of experiments
        - Such as expensiveness of algorithm when evaluating large data sets
        - Dimensions
        - Etc?