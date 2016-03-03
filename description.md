# Advanced Machine Learning 02460 - Project

## Large-Margin Nearest Neighbours

- Søren is in 321, door 009

### Overview 
- Distance metric used to identify nearest neighbours
    - Metric adapted to problem being solved -> Find good metric for faces
    - Learn metric from labeled examples. Is that possible?
    - Use only relevant parts of image (faces and not background)

- Possible tasks:
    1. Which person is this?
    2. Is this the same person as this?

- Learn good distance measures between features
    - Come up with a matrix that makes the distance measure better
    - A change of basis (new coordinate system for feature vector)

### Plan 
- Read chapter 2 in Bishop
- Read the research paper ["Distance Metric Learning for Large Margin Nearest Neighbor Classification"](http://jmlr.csail.mit.edu/papers/volume10/weinberger09a/weinberger09a.pdf)
- Download [data](https://lrs.icg.tugraz.at/research/kissme/)
- Implement kNN with Euclidian distance and run it
    - Optimize
- Research on key image points for faces


### Learning objective
- 

### Links to read

- [https://en.wikipedia.org/wiki/Large_margin_nearest_neighbor](https://en.wikipedia.org/wiki/Large_margin_nearest_neighbor)

*Killian Q. Weinberger among others*

- [http://www.cs.cornell.edu/~kilian/code/lmnn/lmnn.html](http://www.cs.cornell.edu/~kilian/code/lmnn/lmnn.html)
- [http://jmlr.csail.mit.edu/papers/volume10/weinberger09a/weinberger09a.pdf](http://jmlr.csail.mit.edu/papers/volume10/weinberger09a/weinberger09a.pdf)
- [http://papers.nips.cc/paper/2795-distance-metric-learning-for-large-margin-nearest-neighbor-classification.pdf](http://papers.nips.cc/paper/2795-distance-metric-learning-for-large-margin-nearest-neighbor-classification.pdf)
-[Bitbucket lmnn project](https://bitbucket.org/mlcircus/lmnn)

*Other*

- [Python notebook on implementing LMNN in Python](http://nbviewer.jupyter.org/gist/iglesias/6576096)
- [https://cs.gmu.edu/~carlotta/publications/01461432.pdf](https://cs.gmu.edu/~carlotta/publications/01461432.pdf)
- [Other article from google](https://www.google.dk/url?sa=t&rct=j&q=&esrc=s&source=web&cd=7&ved=0ahUKEwjArdG6lqTLAhWhO5oKHb3SBrYQFghOMAY&url=https%3A%2F%2Fwww.aaai.org%2Focs%2Findex.php%2FAAAI%2FAAAI11%2Fpaper%2Fdownload%2F3571%2F3889&usg=AFQjCNGhvQLnTIA3nRQbt9AJZ5WM92XYoQ&sig2=qqUyyKCLqzqIlgWFo5XsKw&cad=rja)


