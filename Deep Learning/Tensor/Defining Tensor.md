### Defining Tensor
We can define tensor in 2 ways.
1. `tf.Variable()`
2. `tf.constant()`

The difference between `tf.Variable()` and `tf.constant()` 
If tensors created with `tf.constant()` are immutable (can't be changed, can only be used to create a new tensor), where as, tensors created with `tf.Variable()` are mutable (can be changed).

**Note:** To change an element of a `tf.Variable()` tensor requires the `assign()` method.

### Tensor Attributes
There will be times when you'll want to get different pieces of information from your tensors, in particular, you should know the following tensor vocabulary:

-   **Shape:** The length (number of elements) of each of the dimensions of a tensor - `tensor.shape`.
-   **Rank:** The number of tensor dimensions. A scalar has rank 0, a vector has rank 1, a matrix is rank 2, a tensor has rank n - `tensor.ndim`.
-   **Axis** or **Dimension:** A particular dimension of a tensor - `tensor[0]`.
-   **Size:** The total number of items in the tensor - `tf.size(tensor)`.
