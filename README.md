# Homogeneous Community Detection On Heterogeneous Information Networks: A Node Embedding Approach

This thesis proposes a pipeline approach to tackle the challenge of community detection (CD) on static heterogeneous information networks (HINs) using node embedding (NE) in conjunction with homogeneous modularity-based algorithms. It leverages NE techniques (i.e., JUST, Metaptah2Vec) to transform an HIN into a weighted homogeneous network by calculating vector similarity distances in the latent low-dimensional embedding space for each node, and then projecting them as edge weights onto a topologically identical homogeneous counterpart of the HIN. A homogeneous modularity-based CD algorithm (i.e., Louvain, Leiden) can then run on the weighted homogeneous graph to identify community structures. This method attempts to both preserve the high-order semantic meaning and topological structure of the original heterogeneous HIN whilst circumventing the necessity for specialized  heterogeneous CD algorithms.

![An overview of how the pipeline works and which Python versions/libraries needed for each step](https://github.com/kareeemk/NE-CD-Pipeline/assets/149080138/56cb46f3-3ffd-4bb1-b266-4cb82fcf0aac)


## Description
This repository contains implementations for the following Bachelor thesis: (ADD LINK). Full implementations and step-by-step Jupyter Notebooks are provided for the LastFM and DBLP datasets. Follow the instructions in each notebook to execute the processes. Keep an eye out for the Input and Output folders in each step of the pipeline. Please refer to the diagram included in this repository for details on what each step of the pipeline requires. The diagram can help visualize the workflow and dependencies.

## System Requirements
### Python Versions
This project requires multiple Python versions:
- Python 3.9.7
- Python 3.6.15
- Python 2.7.18

We highly recommend the use of `pyenv` to manage multiple Python versions.

### Libraries
Make sure to install the following libraries in their respective folders:
- StellarGraph
- JUST

Anytime you need to use SG or JUST, make sure the source code is in the folder you are working in!

Additionally, the following Python libraries are required:
- CDLib
- StellarGraph
- iGraph
- NetworkX
- MatPlotLib

### Installation

```
pip install cdlib stellargraph python-igraph networkx matplotlib
```

To avoid dependency conflicts, it is advised to use virtual environments. Use pyenv to manage and switch between multiple Python versions.


