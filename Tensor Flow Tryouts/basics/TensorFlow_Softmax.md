#**TensorFlow Softmax explanation** 

#### Overview
---

In this piece of code we are shown 3 values in a Numpy array.

We can vary those values by simple scale them (x10, x0.1, etc) to check what happens to the resulting probabilities tensor.

#### Multiplying by 10
---

We can see that when we multiply by 10 times each of the values in the array, the resulting probabilities are closer to either zero or one.
---

#### Dividing by 10
---

We can see that when we divide by 10 times each of the values in the array, the resulting probabilities are closer to the uniform distribution.

