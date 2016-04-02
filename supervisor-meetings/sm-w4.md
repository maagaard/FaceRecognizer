# Advanced Machine Learning 02460 - Project
## Supervisor meeting - Week 4
**31-03-2016**

### Agenda
1. Progress / status
    * Show "results"
    * Question about algorithm
2. Project delimitation and learning goals
3. Plan


### Minutes

1. Moved calculations out of loops they do not depend on
2. Spend a lot of time correcting small mistakes in code
3. The relative impact of the margin depends on the initial scaling of the dataset
4. Test by numerical differentiation of the loss function showed that our gradient is correct (if loss function is correct)
5. Consider scaling the M-matrix, s.t. trace(M) = 1, caused a problem with the relative impact of the marging s.t. we did not converged to a solution
6. Emil was sick today
