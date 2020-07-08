# Benchmarks

The following benchmarks should be used to provide performance data for tender responses. Where appropriate we have provided instructions for building and running the benchmark and the results obtained on current ARC HPC clusters. Some tests will be used for acceptance testing only - these being the synthetic tests IOR and mdtest. 

## Synthetic Benchmarks

- [HPL](http://github.com/oxford-arc/HPL-and-STREAM)
- [STREAM](http://github.com/oxford-arc/HPL-and-STREAM)
- [LinkTest (Parallel MPI PingPong Test)](https://github.com/oxford-arc/LinkTest)
- [IOR (acceptance test only)](http://github.com/oxford-arc/HPC-IO-Benchmark)
- [mdtest (acceptance test only)](http://github.com/oxford-arc/HPC-IO-Benchmark)


## Application Benchmarks

### Small (Single Node)

The following single node benchmarks are run from *Singularity* containers which are downloaded or built as part of the installation process. Detailled instructions can be found in the README of each benchmark below:

#### GPU

- [GROMACS](http://github.com/oxford-arc/bench-gromacs-gpu)
- [TensorFlow](http://github.com/oxford-arc/bench-tensorflow-gpu)

#### CPU

- [OpenFOAM](http://github.com/oxford-arc/bench-openfoam)

### Large (Multi-Node) 

- [GROMACS](http://github.com/oxford-arc/bench-gromacs-cpu)
- [CP2K](http://github.com/oxford-arc/bench-cp2k-cpu)
- [OpenSBLI](http://github.com/oxford-arc/bench-opensbli-cpu)

The licence for the ARCHER application benchmark procedures and scripts can be found [here](https://github.com/hpc-uk/archer-benchmarks/blob/master/LICENSE.md)

