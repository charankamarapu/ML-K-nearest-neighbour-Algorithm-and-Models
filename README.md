# ML-K-nearest-neighbour-and-Models
### INTRODUCTION
The k-nearest neighbors (KNN) algorithm is a simple, easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems.It is a supervised machine learning algorithm (as opposed to an unsupervised machine learning algorithm) is one that relies on labeled input data to learn a function that produces an appropriate output when given new unlabeled data./
- The KNN algorithm assumes that similar things exist in close proximity. In other words, similar things are near to each other.
- Here k is the no of neighbhour that we wish to considerfor the caluclation.
- The algorithm takes the first K nearest neghbours
- If regression, it returns the mean of the K labels
- If classification, return the mode of the K labels
- we usually make K an odd number to have a tiebreaker./

### PROS
- The algorithm is simple and easy to implement.
- There’s no need to build a model, tune several parameters, or make additional assumptions.
- The algorithm is versatile. It can be used for classification, regression, and search.

### CONS
- The algorithm gets significantly slower as the number of examples and/or predictors/independent variables increase.
