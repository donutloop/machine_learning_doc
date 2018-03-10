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

## feature cross

A feature cross is a synthetic feature that encodes nonlinearity in the feature space by multiplying two or more input features together. (The term cross comes from cross product.) Let's create a feature cross named x3 by crossing x1 and x2:    

x3 = x1 * x2

We treat this newly minted x3 feature cross just like any other feature. The linear formula becomes:

y = b + w1 * x1 + w2 * x2 + w3 * x3

## Labels

A label is the thing we're predicting—the y variable in simple linear regression. The label could be the future price of wheat, the kind of animal shown in a picture, the meaning of an audio clip, or just about anything

## Features

A feature is an input variable—the x variable in simple linear regression. A simple machine learning project might use a single feature, while a more sophisticated machine learning project could use millions of features