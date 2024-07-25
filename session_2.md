## Pseudocode - Solution of System of equation

```

FUNCTION solution(A, B):
    create augmented matrix: k - [A|B]
    reduce in row reduced echolon form
    rank = no of non zero rows of RREF
    IF (rank(K) != rank(A)):
        print "System is inconsistent"
    ELSE:
        solve using back substitution
END FUNCTION

```
