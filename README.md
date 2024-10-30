# hamFoam

An open-source solver for coupled heat and moisture transport in porous media based on OpenFOAM

Source code for the solver code can be downloaded from [here](https://github.com/OpenFOAM-BuildingPhysics/hamFoam)

The solver is tested for the following OpenFOAM versions:

* OpenFOAM-org (OpenFOAM Foundation) v6, v7, v8, v9, v10, v11
* OpenFOAM-com (OpenCFD-ESI) v1806

### Tutorial case

Tutorial cases solve HAMSTAD Benchmark case 4 (response analysis) and case 5 (capillary active inside insulation).

<img src="https://gitlab.ethz.ch/openfoam-cbp/solvers/hamfoam/-/wikis/img/fig4.png"  width="60%">
<br><i>  Variations of surface temperature and moisture content at the exterior boundary (HAMSTAD Benchmark case 4).  </i>

### Usage

You can use the tutorial for a specific OpenFOAM version by checking out the commit with corresponding tag. For example, for OpenFOAM v9:

	git clone https://github.com/OpenFOAM-BuildingPhysics/hamFoam-tutorials.git
	cd hamfoam-tutorial
	git checkout tags/of-org_v9.0

See the list of tags for different versions [here](https://github.com/OpenFOAM-BuildingPhysics/hamFoam-tutorials/tags)

