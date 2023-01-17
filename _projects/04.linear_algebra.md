---
layout: page
title: Linear Algebra
description: Linear Algebra
img: assets/img/svg/linear_algebra.svg
importance: 4
category: teaching
---

#### Classic Linear Algebra

- Linear Algebra Done Right [Link](https://link.springer.com/book/10.1007/978-3-319-11080-6)
- Linear Algebra by Petersen [Link](https://link.springer.com/book/10.1007/978-1-4614-3612-6)
- Applied Linear Algebra and Matrix Analysis by Shores [Link](https://link.springer.com/book/10.1007/978-3-319-74748-4ol)
- Applied Linear Algebra by Olver and Shakiban [Link](https://link.springer.com/book/10.1007/978-3-319-91041-3)
- Advanced Linear Algebra by Roman [Link](https://link.springer.com/book/10.1007/978-0-387-72831-5)

#### Numerical Linear Algebra

- Numerical Linear Algebra by Allaire and Kaber [Link](https://link.springer.com/book/10.1007/978-0-387-68918-0)
- Numerical Linear Algebra by Wendland [Link](https://www.cambridge.org/core/books/numerical-linear-algebra/3FA43F15246E9DC198455B02C1CE199A)
- Numerical Linear Algebra by Beilina, Karchevskii, and Karchevskii [Link](https://link.springer.com/book/10.1007/978-3-319-57304-5)
- Numerical Linear Algebra by Layton and Sussman [pdf](https://people.sc.fsu.edu/~jburkardt/classes/nla_2015/numerical_linear_algebra.pdf)
- Iterative Solution of Large Sparse Systems of Equations by Hackbusch [Link](https://link.springer.com/book/10.1007/978-3-319-28483-5)
- Iterative Methods for Sparse Linear Systems by Saad [pdf](https://www-users.cse.umn.edu/~saad/IterMethBook_2ndEd.pdf) 
- Hierarchical Matrices by Hackbusch [Link](https://link.springer.com/book/10.1007/978-3-662-47324-5)
- Tensor Spaces and Numerical Tensor Calculus by Hackbusch [Link](https://link.springer.com/book/10.1007/978-3-030-35554-8)

#### Experimentation Tools

- gnuplot [Link](http://www.gnuplot.info/)
- python [Link](https://www.python.org/) scipy [Link](https://scipy.org/) numpy [Link](https://numpy.org/) matplotlib [Link](https://matplotlib.org/)
- GNU Octave [Link](https://octave.org)
- eigen [Link](https://eigen.tuxfamily.org/index.php?title=Main_Page)
- lapack [Link](https://netlib.org/lapack/)
- Matrix Market [Link](https://math.nist.gov/MatrixMarket/)

##### Comparison of Numerical Linear ALgebra Libraries

###### Matrix types and operations

- ''Real'' – general (nonsymmetric) real
- ''Complex'' – general (nonsymmetric) complex
- ''SPD'' – symmetric positive definite (real)
- ''HPD'' – Hermitian positive definite (complex)
- ''SY'' – symmetric (real)
- ''HE'' – Hermitian (complex)
- ''BND'' – band

Operations:
- ''TF'' – triangular factorizations (LU, Cholesky)
- ''OF'' – orthogonal factorizations (QR, QL, generalized factorizations)
- ''EVP'' – eigenvalue problems
- ''SVD'' – singular value decomposition
- ''GEVP'' – generalized EVP
- ''GSVD'' – generalized singular value decomposition

|                          |Real|Complex|SPD|HPD|SY |HE |BND|TF |OF |EVP|SVD|GEVP|GSVD|
|--------------------------|----|-------|---|---|---|---|---|---|---|---|---|----|----|   
|ALGLIB                    |YES |YES    |YES|YES|NO |NO |NO |YES|YES|YES|YES|YES |NO  | 
|ATLAS                     |YES |YES    |YES|YES|NO |NO |NO |YES|NO |NO |NO |NO  |NO  | 
|Dlib                      |YES |YES    |YES|YES|YES|YES|NO |YES|YES|YES|YES|NO  |NO  | 
|GNU Scientific Library    |YES |YES    |YES|YES|NO |NO |NO |YES|YES|YES|YES|YES |YES |
|ILNumerics.Net            |YES |YES    |YES|YES|NO |NO |NO |YES|YES|YES|YES|YES |NO  | 
|IMSL Numerical Libraries  |YES |YES    |YES|YES|NO |NO |YES|YES|NO |YES|YES|YES |NO  | 
|LAPACK                    |YES |YES    |YES|YES|YES|YES|YES|YES|YES|YES|YES|YES |YES | 
|MKL                       |YES |YES    |YES|YES|YES|YES|YES|YES|YES|YES|YES|YES |YES | 
|NAG Numerical Library     |YES |YES    |YES|YES|YES|YES|YES|YES|YES|YES|YES|YES |YES | 
|NMath                     |YES |YES    |YES|YES|YES|YES|YES|YES|YES|YES|YES|NO  |NO  |
|SciPy (Python packages)   |YES |YES    |YES|NO |NO |NO |YES|YES|YES|YES|YES|NO  |NO  | 
|Eigen                     |YES |YES    |YES|YES|YES|YES|YES|YES|YES|YES|YES|YES |NO  | 
|Armadillo                 |YES |YES    |YES|YES|YES|YES|NO |YES|YES|YES|YES|YES |NO  | 


