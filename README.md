# ClosureSeparation
Computation of OEIS sequences A334254 and A334255 for n=6 and checking their values for n=3,4,5.

* A334254 (https://oeis.org/A334254) represents the number of closure operators on a set of n elements which satisfy the T_1 separation axiom, i.e. all singleton sets {x} are closed. For n>1, this property guarantees that the empty set is closed, i.e. the closure operators are strict.


* A334255 (https://oeis.org/A334255) represents Number of strict closure operators on a set of n elements which satisfy the T_1 separation axiom.



## Outline of A334254_and_A334255.ipynb

### 1. The main code with the recursive procedure to generate all closure systems represented as formal contexts and to select those satisfying the T_1 separation axiom.
### 2. Counting A334254 for n=6 with multiprocessing parallelisation.
### 3. Checking the values A334254 for n=3, 4, 5 with the code from Section 1.

## Outline of IneqA334254.ipynb

### 1. The main code with the recursive procedure to generate all closure systems represented as formal contexts and to select those satisfying the T_1 separation axiom.
### 2. Counting A334254 for n=2,3,4,5.
### 3. Counting nonisomorphic closure systems from those of A334254 for n=2,3,4,5.


## References

* Bernhard Ganter, Rudolf Wille:
Formal Concept Analysis - Mathematical Foundations. Springer 1999, ISBN 978-3-540-62771-5, pp. I-X, 1-284

* Dmitry I. Ignatov: On the Cryptomorphism between Davis' Subset Lattices, Atomic Lattices, and Closure Systems under T1 Separation Axiom, https://arxiv.org/abs/2209.12256, 2022
  

For any usage the acknowledgement of this repository and the paper is the necessary condition.
