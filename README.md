# tilingdata

This repository contains the  data for the K-uniform tilings (K<=6)

The data is store in a csv file, the colums are LABEL, S, 2E, lambda, Tc, kappa and K.
- `"LABEL"` : The name of the lattices are equal to the name of the lattices in `galebach.json` (see [paper](https://chequesoto.info/tilings.html)).  

- `"S"` : number of seeds in the unit cell.


- `"2 E"` : two times the number of edges in the toroidal graph determined by the  linearly independent vectors T1 and T2 given in  `galebach.json`.

- `"lambda"` : the spanning tree constant.
- `"Tc"` : the critical ising temperature.
- `"kappa"` : 2 E/ S
- `"K"` : K is the uniformity class, so for example if K=1 then the lattice is 1-uniform.



