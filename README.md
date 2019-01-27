# PCA
PCA ( Principal Component Analysis)
It is unsupervised 
Used for:
1)Noise Filter
2)Visualization
3)Feature Extraction
4)Gene data Analysis
5)  etc....

It Identify pattern in data and Detect the correlation between variables

Reduces the dimensions of a d-dimensional dataset by projecting it onto a (n)-dimensional subspace(Where n<d)
<h4>Main function of PCA </h4>
Standardize the data
Obtain the eigenVectors and EigenValues from the Covariance matrix or Correlation matrix, or perform Singular Vector Decomposition
Sort eignValue in descending Order and choose the n eigenVectors that corrspond to the n largest eigenValues where n is the number of dimension of the new feature subspace(n<=d)
Construct the projection matrix W from the selected n-eginevectors
Transform the original dataset X via W to obtain a n-dimensional feature subspace Y

Link:
setosa.io/ev/principal-component-analysis/
https://plot.ly/ipython-notebooks/principal-component-analysis/


# LDA
LDA (Linear Discriminat Analysis)
Used as a dimensionality reduction technique
Used in pre-processing step for pattern classification 
Has the goal to project a dataset onto a lower-dimensional space

LDA is diffrenet from PCA because in addition to finding the component axies with LDA we are intersted in the axis that maximize the SEPARATION between multiple classes


The goal of LDA is to project a feature space ( a dataset n-dimensional smaples) onto a small subspace sunspace k(where k<= n-1) while maintaining the class-discriminatory information 

Both PCA and LDA are <h5>Linera transormation</h5> technique used for dimensional reduction. PCA is describe as Unsupervised but LDA is supervosed because of the relation to the dependent variable.

<h3>For Non-Linear Dataset use KernalPCA</h3>
