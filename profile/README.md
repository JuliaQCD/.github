# Julia QCD

This code enabales you to perform lattice QCD calculations! A native Julia code for Lattice QCD.

This package is organized as follows

- [LatticeQCD.jl](https://github.com/akio-tomiya/LatticeQCD.jl) : Wrapper of following packages
- [Wilsonloop.jl](https://github.com/akio-tomiya/Wilsonloop.jl) : Wilsonloop.jl helps us to treat with the Wilson loops and generic Wilson lines in any Nc and dimensions. Wilson lines can be defined in symbolly.
- [Gaugefields.jl](https://github.com/akio-tomiya/Gaugefields.jl) : Gaugefields.jl is a package for lattice lattice SU(N) gauge fileds. Treating gauge fields (links), gauge actions with MPI and autograd. This can generate quenched configurations.
- [LatticeDiracOperators.jl](https://github.com/akio-tomiya/LatticeDiracOperators.jl) : LatticeDiracOperators.jl is a package for Dirac operators and fermions on the lattice. Treating pseudo-femrion fields with various lattice Dirac operators, fermion actions with MPI. This can generate configurations with dynamical fermions.
- [QCDMeasurements.jl](https://github.com/akio-tomiya/QCDMeasurements.jl) : QCDMeasurements.jl is a package for measuring physical quantities. This has measurements for basic quantities like chiral condensates, plaquettes. Moreover, pion correlators and topological charge with several definitions. This also has the gradient flow with several actions.
