# Advanced Machine Learning 02460 - Project
## Supervisor meeting - Week 2 
**10-03-2016**

### Agenda
1. Progress / status
2. Plan
3. Delimitation
4. Learning objectives
5. Other


### Minutes
1. kNN implementation
    - Maybe look at vectorization when computing distances
    - Maybe experiment with *bsxfun()* in matlab
        - Eg. *bsxfun(@minus, A, v)*
        - @minus, @plus, @times are fast!
2. Implement learning algorithm
    - Small data set (2 dimensions ~100 samples)
    - Get something working
    - Evaluate "hacks" in algorithm that are implemented to lowers computation time
    - Major tasks
        - Compute gradient (careful bookkeeping of targets and impostors)
        - Maybe look at energy of cost function
        - Plot *M*, either by plotting *L(or L') = chol(M)*
            - Basis change by multiplying original data with L
3. Agree on this after easter, bring preliminary delimitation
4. Agree on this after easter, bring preliminary goals and objectives
5. Other:
    - Data sets:
        - Maybe have a look at kissme

