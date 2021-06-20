# Polynomial-Class
The code implements a polynomial class with various properties and functions.

Properties :

An integer (lets say A) which holds the coefficient and degrees. Use array indices as degree and A[i] as coefficient of ith degree.
An integer holding total size of array A.
Functions :

Default constructor
Copy constructor
setCoefficient - This function sets coefficient for a particular degree value. If the given degree is greater than the current capacity of polynomial, increase the capacity accordingly and add then set the required coefficient. If the degree is within limits, then previous coefficient value is replaced by given coefficient value
Overload "+" operator (P3 = P1 + P2) : Adds two polynomials and returns a new polynomial which has result.
Overload "-" operator (P3 = p1 - p2) : Subtracts two polynomials and returns a new polynomial which has result
Overload * operator (P3 = P1 * P2) : Multiplies two polynomials and returns a new polynomial which has result
Overload "=" operator (Copy assignment operator) - Assigns all values of one polynomial to other.
print() - Prints all the terms (only terms with non zero coefficients are to be printed) in increasing order of degree. Print pattern for a single term : "x" And multiple terms should be printed separated by space. And after printing one polynomial, print new line. For more clarity, refer sample test cases
Input Format :

Line 1 : N, total number of terms in polynomial P1 Line 2 : N integers representing degree of P1 (separated by space) Line 3 : N integers representing coefficients of P1 (separated by space) Line 4 : M, total number of terms in polynomial P2 Line 5 : M integers representing degree of P2 (separated by space) Line 6 : M integers representing coefficients of P2 (separated by space) Line 7 : Integer C, choice representing the function to be called (See main for more details)

Sample Input 1 : 3

1 3 5

1 2 -4

4

0 1 2 3

4 2 -3 1

1

Sample Output 1 : 4x0 3x1 -3x2 3x3 -4x5

Sample Input 2 : 3

1 3 5

1 2 -4

4

0 1 2 3

4 2 -3 1

2

Sample Output 2 : -4x0 -1x1 3x2 1x3 -4x5
