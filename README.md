# Notes an linux tricks


## BLAS/LAPACK on Debian/Ubuntu

BLAS:
```bash
$ sudo update-alternatives --config libblas.so.3
```

LAPACK:
```bash
$ sudo update-alternatives --config liblapack.so.3
```

On ubuntu one must use openblas with standar lapack for numpy to work.

Note that the number of threads used by openblas can be set manually by:
```bash
$ export OPENBLAS_NUM_THREADS=1
```

