# Advanced Machine Learning 02460 - Project
# Week 1 
**03-03-2016**

## Large-Margin Nearest Neighbours
**Metric Learning**

- Søren is in 321, door 009

### Overview of the project
- Distance metric used to identify nearest neighbours
    - Metric adapted to problem being solved -> Find good metric for faces
    - Learn metric from labeled examples. Is that possible?
    - Use only relevant parts of image (faces and not background)

- Possible tasks
    1. Which person is this?
    2. Is this the same person as this?

- Learn good distance measures between features
    - Come up with a matrix that makes the distance measure better
    - A change of basis (new coordinate system for feature vector)

### Prioritized plan for the next week
1. Read the research paper ["Distance Metric Learning for Large Margin Nearest Neighbor Classification"](http://jmlr.csail.mit.edu/papers/volume10/weinberger09a/weinberger09a.pdf)
2. Read chapter 2 in Bishop
3. Implement kNN with Euclidian distance and run it (maybe just pseudo code)
    - Optimize it and make it fast
4. Download [data](https://lrs.icg.tugraz.at/research/kissme/)
5. If time: Research on key image points for faces



### Meeting notes

##### Poster presentation
1. What did we do
2. What did we learn, what did we find out
3. Where did we fail
4. Incorporate feedback into report

##### Report
- 4 pages (dense af)
- Get feedback on preliminary report as we go a long

##### Other stuff
- Agree on dates for feedback with Søren H.
- Weekly meeting with Søren thursdays from 11-12
- Maybe compare our implementation with other public implementations
- Put everything into the log