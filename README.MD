# Basic deal.II examples

This repository accompanies the presentation "The general-purpose 
finite-element library deal.II - Overview and basic 
concepts" [[slides]](presentation.pdf) given by me 12.11.2020 in Munich and
presents some basic features of the deal.II finite-element
library:

- *elasticity*: solves a simple elasticity problem
- *poisson*: solves the Poisson problem
- *poisson_mf*: solves the Poisson problem without computing a system matrix

## Build & run

```bash
mkdir build
cd build; 
cmake ..
make -j3
./elasticity
```

## Testing

```bash
ctest -j3
```

<img align="right" src="https://github.com/peterrum/dealii-examples/workflows/GitHub%20CI/badge.svg">
