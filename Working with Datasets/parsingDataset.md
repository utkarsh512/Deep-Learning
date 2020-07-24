# Parsing Dataset before applying deep-learning algorithms to it

## Step 1
* When the dataset is loaded, first find out the value of `m_train`, `m_test` and `num_px`, so as to get an idea of dimesions of matrices and vectors we will be dealing with.
* Preprocess the dataset to create matrices to be played with. Usually, X.reshape is used for this.
* __Center and Standardize__: In case of numerical data, it is better to subtract mean of the data from every elements, and then divide each element with standard deviation of the whole array. In case of images, we can divided each element by __255__.
