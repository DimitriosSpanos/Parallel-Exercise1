# Parallel-Exercise1

**mmio.c** and **mmio.h** are used to extract the info from the .mtx files.
The source code is given in the following link that you provided.
https://math.nist.gov/MatrixMarket/mmio-c.html

## **2 Preliminaries**
The files that pertain to the preliminaries part of the exercise are
**main.c**, **main_openmp** and **main_cilk**. Choose the appropriate 
matrix by giving it as an argument to main(), as follows.

```
./main matrix.mtx
./main_openmp matrix.mtx
./main_cilk matrix.mtx
```
## **3 Main part**
The files that pertain to the main part of the exercise are **make_graph.c**
**main3.c**, **main3_openmp**, **main3_cilk** and **main3_thread**.

It's vital that the **make_graph** file is run first so that a *graph.mtx*
file is created. The remaining programs use that as their input.
The **make_graph** works like the previous ones, as follows.
```
./make_graph matrix.mtx
```
