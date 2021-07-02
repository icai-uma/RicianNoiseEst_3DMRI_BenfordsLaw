# X
Rician noise estimation for 3D Magnetic Resonance Images based on Benford's Law

This project consist of 3 directories:
- input: it contains 2 3D-MRI brain images form the NKI-RS repository.
- output: the folder where the results will have save it.
- src: the code consist in 2 Jupyter files:
    -   01_loadMRI_boxplot.ipynb
    -   02_randomData_method.ipynb

Easily you can download the code and ejecute each Jupyter to visualize:

Files obtained from the '01_loadMRI_boxplot.ipynb' file:
- 1 csv file:
    - 10 equal spaced noise added to each MRI, Bhattacharyya Coefficient and Kullback.Leibler divergence values for each noise added.
- 2 boxplots, to represent the values of each colum of the csv above:
    - Bhattacharyya Coefficient vs noise.
    - Kullback.Leibler divergence vs noise.
    
Files obtained from the '02_randomData_method.ipynb' file:
- 1 csv file:
    - 20 random noise added to each MRI, Bhattacharyya Coefficient and Kullback.Leibler divergence values for each noise added.
- 2 tables with MSE value for each regressor:
    - Bhattacharyya Coefficient.
    - Kullback.Leibler divergence.
- 2 tables with R2 value for each regressor:
    - Bhattacharyya Coefficient.
    - Kullback.Leibler divergence.
- 2 scatterplot with the regressors:
    - Bhattacharyya Coefficient.
    - Kullback.Leibler divergence.

The content you should be able to see is in the 'output_should_be_appear' directory.

