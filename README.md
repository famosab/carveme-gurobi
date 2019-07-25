[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![PyPI version](https://badge.fury.io/py/carveme.svg)](https://badge.fury.io/py/carveme) [![Documentation Status](http://readthedocs.org/projects/carveme/badge/?version=latest)](http://carveme.readthedocs.io/en/latest/?badge=latest)

## COPY of CarveMe 

CarveMe is a python-based tool for genome-scale metabolic model reconstruction.

Please refer to the original repo https://github.com/cdanielmachado/carveme.
 
### Installation

Git clone this repository.

```python setup.py install```

Additionally, you must install diamond and GUROBI.

- https://github.com/bbuchfink/diamond
- https://www.gurobi.com/academia/academic-program-and-licenses/

If both diamond and GUROBI are installed, run carveme_init as sudo in order to update everything.

### Usage

Build you first model using a fasta file:

``` sudo carve genome.faa -o model.xml```

### Documentation

For more details please check: http://carveme.readthedocs.io/

### Credits and License

For citation purposes please refer to their paper:

D. Machado et al, "Fast automated reconstruction of genome-scale metabolic models for microbial species and communities", Nucleic Acids Research, gky537, 2018. 

DOI: https://doi.org/10.1093/nar/gky537

Developed at the European Molecular Biology Laboratory (2017-2018). Released under an Apache License.

