# GetGene

| **Documentation** | **Build Status** | **Code Coverage**  |
|-------------------|------------------|--------------------|
| Documentation Not Yet Available | [![Build Status](https://travis-ci.org/chris-german/GetGene.jl.svg?branch=master)](https://travis-ci.org/chris-german/GetGene.jl) [![Build status](https://ci.appveyor.com/api/projects/status/xafji8urmg3dfkai?svg=true)](https://ci.appveyor.com/project/chris-german/getgene-jl/branch/master) | [![Coverage Status](https://coveralls.io/repos/github/chris-german/GetGene.jl/badge.svg?branch=master)](https://coveralls.io/github/chris-german/GetGene.jl?branch=master) [![codecov](https://codecov.io/gh/chris-german/GetGene.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/chris-german/GetGene.jl) |  


**GetGene.jl** is a Julia package for getting the nearest loci to an inputted rsid (snpid) through the NCBI's API located [here](https://api.ncbi.nlm.nih.gov/variation/v0/)



## Package features

- Outputs a list of loci associated with the inputted SNP rsids. 

Using:

```julia
    > getgene(rsids)
```

will return associated loci names.


## Contributing and Request 

The software is relatively new. [File an
issue](https://github.com/chris-german/GetGene.jl/issues/new) to report a bug or request a feature.
