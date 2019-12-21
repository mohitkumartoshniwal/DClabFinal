## parallel_programming_lab  

> Command to execute Openmp programs:

```
$ gcc -fopenmp <file>.c  
$ ./a.out  
```

For programs using math library, Use:
```
$ gcc -fopenmp <file>.c -lm
$ ./a.out  
```

> Command to execute MPI programs:

```
$ mpicc <file>.c
$ mpirun -np 4 ./a.out
```


