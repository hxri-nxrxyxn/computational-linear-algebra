## Pseudocode for linear algebra

```python

FUNCTION matrix_sum(A, B):


END FUNCTION

```


$$
    A = \begin{pmatrix}
        1 & 2 & 3 \\
        3 & 4 & 5 \\
        5 & 6 & 7 \\
        \end{pmatrix}
$$

## Pseudocode - Solution of System of Equations

```

FUNCTION solution(A, B):
    create augmented matrix: K = [A|B]
    reduce in row reduced echolon form
    rank = no of non zero rows of RREF
    IF (rank(K) != rank(A)):
        print "System is inconsistent"
    ELSE:
        solve using back substitution
END FUNCTION

```


