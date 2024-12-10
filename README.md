# Data-preprocessing-

Feature scaling means adjusting the values of data so that they all fall within a similar range

Normalization
Goal: Rescale the data to fit within a fixed range, usually between 0 and 1.
When to Use:
When you know your data has no outliers and is already roughly in the same range.
Commonly used in algorithms like neural networks and k-nearest neighbors (KNN) where distances matter.
Effect: Compresses all values into the same range, making it sensitive to outliers.

Standardization
Goal: Scale data to have a mean of 0 and a standard deviation of 1.
When to Use:
When your data has a normal (Gaussian) distribution or when you don’t know its range.
Useful in algorithms like support vector machines (SVMs) and principal component analysis (PCA).
Effect: Centers the data but doesn’t bound it within a specific range, so outliers have less impact.

