# Principal-Component-Analysis-in-Fixed-Income
The objective is to apply the multivariate principal components analysis technique to yield curves of different credit quality, calculating eigenvalues, eigenvectors and principal components.

The objective of this code is to carry out Principal Component Analysis (PCA) on two yield curves: one from a AAA rating issuer and the other from a BBB rating corporate.

- To do this, start by loading a file with the data of the time series of the interest rates for both issuers (X).
- The original series are selected in level or differences
- the the data is transformed into differences on the mean or standardized variables.
- The covariance matrix is calculated.
- On this covar matrix, the eigenvalues (A) and the eigenvectors (U) are calculated.
- The matrix of main components is obtained (P = XU).
- The cumulative variance by principal component is obtained.
- The interpretation of the main components obtained from the different risk factors is analyzed.


![gra8](https://user-images.githubusercontent.com/101003293/156915108-97024091-3915-4fd0-b150-2085cdd58594.png)
