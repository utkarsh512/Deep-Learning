## NumPy functions required while building and training a ConvNet
* ### Padding an nd-array
  * Let _X_ be an np.ndarray with dim as _(x1, x2, ..., xn)_ and let the padding we want for each dim be _(p1, p2, ..., pn)_.
  ```python3
  X_pad = np.pad(X, ((p1, p1), (p2, p2), ..., (pn, pn)), mode='constant', constant_values=(0, 0))
  ```
