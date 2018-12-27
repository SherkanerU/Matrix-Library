# Matrix Library
While working on the n-dimensional projection project I realized that I needed to calculate inverses of matrices.  I coded this mainly as an exersize in matrix algebra.  It's not as fast as it could possibly be, to invert matrices it uses a an adjugate matrix method.  This is slow since the determinant method is called so many times in generating the matrix of minors.  The determinant method uses the recursive method to calculate the determinant!  These are fast enough for my purposes, but I may go back in the future to make it faster.

I also added a Point and Vector class.  The point object is essentially just a collection of coordinated, with some methods to easily access and manipulate them.  The vector class is a child of it and can do a lot of basic vector algebra operations such as calculation of dot products, projections, compositions, scalar multiplications, etc...  

The matrix class allows for collections of points and vectors to be turned into matrices either as columns or rows of the matrix.  
