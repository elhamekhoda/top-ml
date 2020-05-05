# top-ml
This repository will contain all the scripts used in the ML in ttbar resonance project.

## Documentation
Detailed description will be found in the [documentation page](https://elhamekhoda.github.io/mkdocs-base/).

## Installation
These instructions are to use primarily on flashy (atlas-t3-ubc.westgrid.ca), which only has CPUs. You need to have git and anaconda to start with. Detailed instruction in the [code set-up page](https://elhamekhoda.github.io/mkdocs-base/setup/).

**For the first time**
```bash
git clone git@github.com:elhamekhoda/top-ml.git
cd top-ml
conda env create -f env_top-ml.yml
conda activate top-ml
```

**Future log-in**
```bash
cd top-ml
conda activate top-ml
```

## Data set
The dataset files will be in the Hierarchical Data Format (HDF). Our dataset will be in `hdf5` format. .

The variables are stored in `/data/elham/top-ml-project/inputs/` directory on UBC cluster. Detailed description can be found in the [data-set page](https://elhamekhoda.github.io/mkdocs-base/dataset/).

