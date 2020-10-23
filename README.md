# Planar-data-classification-with-one-hidden-layer
Aim is to build a simple neural network, which will have a hidden layer.

**Here:**
- Implement a 2-class classification neural network with a single hidden layer
- Use units with a non-linear activation function, such as tanh 
- Compute the cross entropy loss 
- Implement forward and backward propagation

**Result**:
Accuracy of 90% achieved.

**Interpretation**:
- The larger models (with more hidden units) are able to fit the training set better, until eventually the largest models overfit the data. 
- The best hidden layer size seems to be around n_h = 5. Indeed, a value around here seems to  fits the data well without also incurring noticeable overfitting.
- Regularization, lets you use very large models (such as n_h = 50) without much overfitting. 
