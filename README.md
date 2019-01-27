# PCA
PCA ( Principal Component Analysis)
It is unsupervised 
Used for:
1)Noise Filter
2)Visualization
3)Feature Extraction
4)Gene data Analysis
5)  etc....

<br>It Identify pattern in data and Detect the correlation between variables</br>

<br>Reduces the dimensions of a d-dimensional dataset by projecting it onto a (n)-dimensional subspace(Where n<d)</br>
<h4>Main function of PCA </h4>
<br>Standardize the data</br>
<br>Obtain the eigenVectors and EigenValues from the Covariance matrix or Correlation matrix, or perform Singular Vector Decomposition</br>
<br>Sort eignValue in descending Order and choose the n eigenVectors that corrspond to the n largest eigenValues where n is the number of dimension of the new feature subspace(n<=d)</br>
<br>Construct the projection matrix W from the selected n-eginevectors</br>
<br>Transform the original dataset X via W to obtain a n-dimensional feature subspace Y</br>

Link:
<br>setosa.io/ev/principal-component-analysis/</br>
<br>https://plot.ly/ipython-notebooks/principal-component-analysis/</br>


# LDA
<br>LDA (Linear Discriminat Analysis)</br>
<br>Used as a dimensionality reduction technique</br>
<br>Used in pre-processing step for pattern classification </br>
<br>Has the goal to project a dataset onto a lower-dimensional space</br>

<br>LDA is diffrenet from PCA because in addition to finding the component axies with LDA we are intersted in the axis that maximize the SEPARATION between multiple classes</br>


<br>The goal of LDA is to project a feature space ( a dataset n-dimensional smaples) onto a small subspace sunspace k(where k<= n-1) while maintaining the class-discriminatory information</br> 

<br>Both PCA and LDA are <h5>Linera transormation</h5> technique used for dimensional reduction. PCA is describe as Unsupervised but LDA is supervosed because of the relation to the dependent variable.</br>

<h3>For Non-Linear Dataset use KernalPCA</h3>
