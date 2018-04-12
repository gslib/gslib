# GSLIB 

[![Build Status](https://travis-ci.org/gslib/gslib.svg?branch=master)](https://travis-ci.org/gslib/gslib)

* Gather/Scatter for nearest neighbor data exchange
* XXT solver (parallel direct solver)
* AMG solver 
* Robust spectral element interpolation for a given set of points

# Build Instructions

The build system relies on GNU Make with the `make` command. To compile gslib just run:

```
make CC=mpicc
make PREFIX=<install path> install
```

# Applications

**\[1]&#160;[Nek5000](https://nek5000.mcs.anl.gov/)**: Nek5000 is the open-source, highly-scalable, spectral element code.

**\[2]&#160;[Nektar++](http://www.nektar.info)**: Nektar++ is the open-source spectral/hp element code.
