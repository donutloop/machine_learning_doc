# Convention 

```math
y' = b + w1 * x1
```

where:

* y' is the predicted label (a output)
* b is the bias (the y-intercept). In some machine learning documentation it is instead referred to as w0
* w1 is the weight of feature 1. Weight is the same concept as slope written with m above
* x1 is feature (a input)


## Squared loss

the square of the difference between the label and the prediction

```math
(observation - prediction(x))2 = (y - y')2
```

## Weight initialization 

* For convex problems, weights can start anywhere
    * Convex: think of a bowl shape 
    * Just one minimum
* Forshadowing: not true for neural nets
    * Non-convex: think of an egg crate
    * More than one minimum
    * Strong dependency on initial values    