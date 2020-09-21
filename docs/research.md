# Research 

The research interests of this group include:  

- Numerical integration of ODEs  
- Numerical solution of nonlinear eigenvector problems   
- Numerical linear algebra   
- Computational data science   
- Spectral graph theory   
- Numerical Optimization 
- Analysis of complex networks   

and their applications to a wide range of real-world problems. Some specific topics of interest  are:

### Numerical integration of nonsmooth dynamical systems 
The numerical treatment of differential equations usually relies on smoothness assumptions which play a fundamental role in the development of suitable schemes and in their convergence analysis. However, an emergent field of interest is systems of ODEs with discontinuous right hand side and many applications can be found in control theory (bang-bang controls), mechanical systems (dry friction) biology (gene regulatory networks), chemistry (gas liquid models). In most mathematical models described by discontinuous ODEs the vector field is piecewise smooth in subregions separated by manifolds and discontinuities take place across the manifolds. The existence and uniqueness of solutions are not anymore guaranteed at such interfaces and the classical Filippov theory becomes ambiguous when the discontinuity manifolds have co-dimension greater than 1. Infinitely many vector fields could be selected along the discontinuity manifolds and the corresponding solutions might have different qualitative behavior. This issue clearly affects also the numerical approximation of the solutions. Our aim is to investigate physical regularizations so to allow one to select a Filippov solution that has physical relevance. If we can show that the solutions of the regularized system converge uniformly to a particular Filippov solution, then we can select this solution for the discontinuous problem. The persistence of the qualitative behavior of solutions under regularization is fundamental if we wish to replace the discontinuous system with the regular one or viceversa, hence we will investigate this persistence as well. At the state of the art, numerical techniques for discontinuous problems, even though efficient, need to select a priori a sliding vector field in Filippov convex combination. Our studies would give rigorous theoretical justifications to make such selection in agreement with the original real life model that one wishes to simulate. Our research project focuses on getting new theoretical insight into numerical approaches and on exploiting this insight for the design and implementation of efficient algorithms.

<!-- Informal enquiries can be made to Nicola Guglielmi (nicola.guglielmi@gssi.it) -->
 


### Computational analysis of complex networks
Networks are a very powerful tool to model complex systems and analyze large data. For example, in exploratory data analysis we are often interested in finding clusters or communities, or assessing the importance (or centrality) of datapoints. As many real-world systems feature geographical, temporal, or categorical metadata and higher-order structures (motifs), models based on higher-order graphs such as hypergraphs, multilayer graphs and simplicial complexes are nowadays becoming prevalent.
We are interested in developing both theoretical foundations and efficient algorithms for a range of network analysis problems. We are particularly interested in methods that exploit matrix and tensor representations of the data to approximately solve related combinatorial optimization problems such as community detection, clustering, core-periphery analysis.



### Spectral methods for machine learning
Spectral methods play a fundamental role in machine learning, statistics, and data mining.
Methods for important tasks such as clustering, semi-supervised learning, dimensionality reduction, latent factor models, ranking and preference learning and covariance estimation
all use information about eigenvalues and eigenvectors (or singular values and singular vectors) from an underlying data matrix.
Even though spectral methods are both powerful and convenient, they often rely on a linear approximation of the ideal learning problem which sometimes yields inaccurate results. We are interested in developing spectral methods that are based on nonlinear eigenvalue problems with eigenvector nonlinearities. This class of eigenvector methods is very broad and includes several nonlinear dimensionality reduction models and tight relaxation of cut functions, to name some. Moreover, it allows us to develop numerical linear algebra tools to efficiently perform the nonlinear spectral methods.  
