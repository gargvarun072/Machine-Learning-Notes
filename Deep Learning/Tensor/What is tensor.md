### What is Tensor ?

Tensors are multi-dimensional arrays with a uniform type (called a `dtype`). You can see all supported `dtypes` at [`tf.dtypes.DType`](https://www.tensorflow.org/api_docs/python/tf/dtypes/DType).

-   **scalar**: a single number.
```python
# Create a scalar (rank 0 tensor)
scalar = tf.constant(7)

<tf.Tensor: shape=(), dtype=int32, numpy=7>
```

- **vector**: a number with direction (e.g. wind speed with direction).
  ```python
# Create a vector (more than 0 dimensions)
vector = tf.constant([10, 10])

<tf.Tensor: shape=(2,), dtype=int32, numpy=array([10, 10], dtype=int32)>
```

- **matrix**: a 2-dimensional array of numbers.
  ```python
  # Create a matrix (more than 1 dimension)
matrix = tf.constant([[10, 7],[7, 10]])

<tf.Tensor: shape=(2, 2), dtype=int32, numpy=array([[10,  7],[ 7, 10]], dtype=int32)>
```
 
- **tensor**: an n-dimensional array of numbers (where n can be any number, a 0-dimension tensor is a scalar, a 1-dimension tensor is a vector).
  ```python
  # How about a tensor? (more than 2 dimensions, although, all of the above items are also technically tensors)
tensor = tf.constant([[[1, 2, 3],
                       [4, 5, 6]],
                      [[7, 8, 9],
                       [10, 11, 12]],
                      [[13, 14, 15],
                       [16, 17, 18]]])
                       
<tf.Tensor: shape=(3, 2, 3), dtype=int32, numpy=
array([[[ 1,  2,  3],
        [ 4,  5,  6]],

       [[ 7,  8,  9],
        [10, 11, 12]],

       [[13, 14, 15],
        [16, 17, 18]]], dtype=int32)>
```
