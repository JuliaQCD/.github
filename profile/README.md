
![JuliaQCD](logo_juliaqcd.png "JuliaQCD logo")

This code enabales you to perform lattice QCD calculations! A native Julia code for Lattice QCD.

This package is organized as follows. Basically, upper side depends on lower packages.


<figure>
  <img src="blockv2.png" alt="Blick structure" width="25%" />
  <figcaption>Relation between pojects</figcaption>
</figure>

- [LatticeQCD.jl](https://github.com/akio-tomiya/LatticeQCD.jl) : Wrapper of following packages. You can start lattice calucations with standard setups. If you are interested in new gauge action, fermions and other measurements, please use following packages.
- [QCDMeasurements.jl](https://github.com/akio-tomiya/QCDMeasurements.jl) : QCDMeasurements.jl is a package for measuring physical quantities. This has measurements for basic quantities like chiral condensates, plaquettes. Moreover, pion correlators and topological charge with several definitions. This also has the gradient flow with several actions.
- [LatticeDiracOperators.jl](https://github.com/akio-tomiya/LatticeDiracOperators.jl) : LatticeDiracOperators.jl is a package for Dirac operators and fermions on the lattice. Treating pseudo-femrion fields with various lattice Dirac operators, fermion actions with MPI. This can generate configurations with dynamical fermions.
- [Gaugefields.jl](https://github.com/akio-tomiya/Gaugefields.jl) : Gaugefields.jl is a package for lattice lattice SU(N) gauge fileds. Treating gauge fields (links), gauge actions with MPI and autograd. This can generate quenched configurations.  
- [Wilsonloop.jl](https://github.com/akio-tomiya/Wilsonloop.jl) : Wilsonloop.jl helps us to treat with the Wilson loops and generic Wilson lines in any Nc and dimensions. Wilson lines can be defined in symbolly.

# Acknowledgment
If you write a paper using this package, please refer this code.

BibTeX citation is following
```
@misc{nagai2024juliaqcdportablelatticeqcd,
      title={JuliaQCD: Portable lattice QCD package in Julia language}, 
      author={Yuki Nagai and Akio Tomiya},
      year={2024},
      eprint={2409.03030},
      archivePrefix={arXiv},
      primaryClass={hep-lat},
      url={https://arxiv.org/abs/2409.03030}, 
}
```
and the paper is [arXiv:2409.03030](https://arxiv.org/abs/2409.03030).
