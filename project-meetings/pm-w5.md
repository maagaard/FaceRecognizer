# Advanced Machine Learning 02460 - Project
## Project meeting - Week 5
**07-04-2016**


# Progress since last time
-  Nothing noteworthy

# Today
- Better value for margin
    * We now compute it
- Code profiling
    - The intersect(A,B) used for finding correct targets and impostors, is very slow. Instead of intersect, the underlying method used by intersect(A,B), ismember(A,B) can be used. The ismember(A,B) returns an array indicating which values of A that is also found in B. 
- Implementing LMNN using active sets 
    - We first experienced a weird behavior of the loss function, showing spikes every time we recomputed the active sets. However, the loss function still converged somewhat like that of the full implementation. 
    - Investigations showed poorly handling of the active set's impostor indexes. Solving this issue showed gave us the following (Fishers Iris data set). 
    ![LMNN active]
    - In order to compare the active set implementation speed against the full implementation we profiled the code in Matlab. For a more reliable result we ran 500 iterations of each on the exact same data.
    - The full algorithm (called LMNN_v3):
    ![Full algo]
    - The active set implementation (called LMNN_v4):
    ![AS algo]
- Visualizing behavior of metric
    ![LMNN metric]


# Discussions
- Loss function numerical gradient seems correct

- Margin / scaling discussion
    - 1 margin with low scaling of data adds a large push contribution
    - 1 margin with large scaling of data adds a large pull contribution
    - max(max(targets)) adds a too large margin when we have outliers
    - median(median(targets)) seems beeter
    - Loss function becomes flat when we have a low scaling of data
    - Maybe scale data after cov(data) in order to normalize
    - Normalize data and use a unit margin. Normalizing:
    ```
        xTrain = (chol(inv(cov(xTrain))) * xTrain')';
    ```

- Active sets
    - If a data point has impostors it is active, else it isn't

- Real data set (larger)

- What about other norms? For instance the 1 norm?


# All groups meeting
- lfw_sifts.mat contains the treated face data


# Work for next week. 
- Test classification
- Visualize behavior of gradient
- Make some more examples for visualization 


[LMNN active]: /images/LMNN_v4_fishersiris_w5.png
[LMNN metric]: /images/LMNN_v4_metricplot_w5.png
[Full algo]: /images/full_algo_it500.png
[AS algo]: /images/active_set_algo_it500.png