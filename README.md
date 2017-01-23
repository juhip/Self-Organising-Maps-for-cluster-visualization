# Self-Organising-Maps-for-cluster-visualization

# Manifold Learning
High-dimensional datasets can be very difficult to visualize. To aid visualization of the structure of a dataset, the dimension must be reduced in some way.

## Random Projection of data :
The simplest way to accomplish this dimensionality reduction is by taking a random projection of the data. 
Disadv :Though this allows some degree of visualization of the data structure, the randomness of the choice leaves much to be desired. In a random projection, it is likely that the more interesting structure within the data will be lost.

 Other methods : 
 a number of supervised and unsupervised linear dimensionality reduction frameworks have been designed, such as:
 i. Principal Component Analysis (PCA)
 ii. Independent Component Analysis
 iii. Linear Discriminant Analysis, 
and others. These algorithms define specific rubrics to choose an “interesting” linear projection of the data. 
Disadv :These methods can be powerful, but often miss important non-linear structure in the data.

## What is Manifold learning? 
Manifold Learning can be thought of as an attempt to generalize linear frameworks like PCA to be sensitive to non-linear structure in data. Though supervised variants exist, the typical manifold learning problem is unsupervised: it learns the high-dimensional structure of the data from the data itself, without the use of predetermined classifications.

## What is a Self Organizing Map?
The Self Organizing Maps (SOM), also known as Kohonen maps, are a type of Artificial Neural Networks able to convert complex, nonlinear statistical relationships between high-dimensional data items into simple geometric relationships on a low-dimensional display. In a SOM the neurons are organized in a bidimensional lattice and each neuron is fully connected to all the source nodes in the input layer.

## Manifold Learning Implementations
Isomap (Isometric Mapping) : http://scikit-learn.org/stable/modules/generated/sklearn.manifold.Isomap.html#sklearn.manifold.Isomap
extension of Multi-dimensional Scaling (MDS) or Kernel PCA. Isomap seeks a lower-dimensional embedding which maintains geodesic distances between all points. Isomap can be performed with the object  
