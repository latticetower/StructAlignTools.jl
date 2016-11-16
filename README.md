# StructAlignTools.jl

The aim of this repository is to provide tools for proteins structure comparison. 

According to current plan, this package will include:

* SVD-based superposition algorithm (the same as those implemented in biopython) 
* tools for structure manipulation and refinement
* tools for extraction of structure components described in pdb header (symmetry elements) 
* tools for chain/atoms coordinates manipulation (transition, reflection, etc.) 
* structural alignment
* secondary structure elements extraction
* functional domains detection (last task before world domination)

I plan to use BioJulia.jl, and probably won't implement things which already present there.
My main goal is to study existing algorithms, that's why I plan to implement all these. 
I also plan to benchmark with existing implementations - to use faster tool.
