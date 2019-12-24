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

For program 5, give number of points and processes as cmd line arguments
```
$ ./a.out 5 10
```

For program 6, install gd library if not installed using the following command:
```
sudo apt-get install libgd2-xpm-dev
```
and give an input image and an output file name and number of threads as cmd line args
```
./a.out input.png output.png 4
```
the file type should be png


> Command to execute MPI programs:

```
$ mpicc <file>.c
$ mpirun -np 4 ./a.out
```


