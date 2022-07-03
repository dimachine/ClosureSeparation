# ClosureSeparation
Computation of OEIS sequences A334254 and A334255 for n=6 and checking their values for n=3,4,5.

* A334254 (https://oeis.org/A334254) represent the number of closure operators on a set of n elements which satisfy the T_1 separation axiom, i.e. all singleton sets {x} are closed. For n>1, this property guarantees that the empty set is closed, i.e. the closure operators are strict.


* A334255 (https://oeis.org/A334255) Number of strict closure operators on a set of n elements which satisfy the T_1 separation axiom.



## Outline 

### 1. The main code with the recursive procedure to generate all closure systems represented as formal contexts and to select those satysfying the T_1 separation axiom.
### 2. Counting A334254 for n=6 with multiprocessing parallelisation.
### 3. Checking the values A334254 for n=3, 4, 5 with the code from Section 1.


## References

* Bernhard Ganter, Rudolf Wille:
Formal Concept Analysis - Mathematical Foundations. Springer 1999, ISBN 978-3-540-62771-5, pp. I-X, 1-284
