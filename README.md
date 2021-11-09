# occpm
Source code for our project «Object-Centric Comparative Process Mining» in the «Process Discovery Using Python» lab offered at RWTH Aachen University in WS21.

# Installation

## Environment
When using conda you can create an environment from the provided `environment.yml` by:
```
$ conda env create -f environment.yml
$ conda activate occpm
```
If any dependency is missing please add it and only it to `environment.yml` without specifying a version number and please **do not** use `conda env export > environment.yml` since one should avoid hard references to specific package versions unless explicitly necessary.

### Static environment
If the environment created from `environment.yml` does not work you can try using `environment_static.yml`(which was created using `conda env export > environment_static.yml`) to obtain an environment with the exact versions used during development, however this is not guaranteed to work across OS's and if possible one should not use out-of-date versions of packages.

