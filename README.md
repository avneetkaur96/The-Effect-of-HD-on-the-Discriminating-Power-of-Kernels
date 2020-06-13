# norm_concentration_high_dimensions
Work done with Prof. Jayaram Balasubramaniam on 'The Effect of High Dimensions on the Discriminating Power of Kernels'

The use of kernels in ML algorithms is almost ubiquitous. However, the curse of high dimensionality is known to inflict kernels 
too. In this project, we begin by illustrating one aspect of this effect on Gaussian Kernels in high dimensions and discuss a
method of alleviation as suggested by Francois et al. [1] - that of  the use of p-Gaussian kernels that include a supplementary
degree of freedom in order to adapt to the distribution of data in high dimensional problems.
   
While the above proposed modification is theoretically desirable, it does not provide commensurate mitigation to many of the 
original problems. This provided the motivation to take up a similar study, wherein a suitable generalisation of the above 
solution of Francois et al., led us to determining alternate kernels, distances and transformations.
    
Our study has shown that we need to consider the (kernel, distance, transformation) as a triple and show that compatible 
triples can be effective in high dimensions and illustrate clearly that such triples do alleviate the identified problems of 
loss of contrast and high condition number, thus leading to increased stability in the employed algorithms. 

[1] Damien Francois, Vincent Wertz, and Michel Verleysen, About the locality of kernels in high-dimensional spaces, 
Proceedings of ASMDA 2005, International Symposium on Applied Stochastic Models and Data Analysis, 2005, p. 238-245.  
