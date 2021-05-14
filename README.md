# PCA --- A dimensional reduction method for data points with linear structure
Given 𝑚 data points, 𝑥1, 𝑥2,…𝑥m ∈ 𝑅d
(1) Compute mean miu and covariance matrix C from data
(2) Take the eigenvectors 𝑤1,𝑤2,… of 𝐶 corresponding to the largest eigenvalue 𝜆1, the second largest eigenvalue 𝜆2...
(3) Compute reduced representation zi = wj.T*(xi-miu)/(𝜆1^1/2), where i denotes ith data point, j denotes jth component.
