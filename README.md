# Customer Segmentation Using Unsupervised Learning 
Customer Segmentation involves grouping customers based on shared characteristics, behaviors and preferences. Businesses can tailor their strategies and target specific groups more effectively and enhance overall market value by segmenting their customer. T-distributed Stochastic Neighbor Embedding and K Means was used to segment the customer.

T-distributed Stochastic Neighbor Embedding (t-SNE) is a non linear dimensionality reduction technique used for visualizing high-dimensional data in a lower-dimensional space mainly in 2D or 3D. Unlike linear methods such as Principal Component Analysis (PCA), t-SNE focus on preserving the local structure and pattern of the data.

K-means Algorithm
We specify the number of clusters that we need to create.
- The algorithm selects k objects at random from the dataset. This object is the initial cluster or mean.
- The closest centroid obtains the assignment of a new observation. We base this assignment on the Euclidean Distance between object and the centroid.
-  k clusters in the data points update the centroid through calculation of the new mean values present in all the data points of the cluster. - The kth cluster’s centroid has a - - Length of p that contains means of all variables for observations in the k-th cluster. We denote the number of variables with p.
-  Iterative minimization of the total within the sum of squares. Then through the iterative minimization of the total sum of the square, the assignment stop wavering when we - - Achieve maximum iteration. The default value is 10 that the R software uses for the maximum iterations.

## Library
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Sklearn

### Dataset
new.csv


