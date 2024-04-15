# NE-CD-Pipeline
Homogeneous Community Detection On Heterogeneous Information Networks: A Node Embedding Approach

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


