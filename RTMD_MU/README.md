
If you failed to install and run this tracker, please email me (<dkn2014@mail.dlut.edu.cn>)

# Introduction

This is a python-implemented visual object tracking algorithm. Use meta-updater to control the update of RTMD.

# Prerequisites

* python 3.6
* ubuntu 16.04
* cuda-9.0

## Installation
1. Clone the GIT repository:
```
 $ git clone https://github.com/Daikenan/LTMU.git
```
2. Clone the submodules.  
   In the repository directory, run the commands:
```
   $ git submodule init  
   $ git submodule update
```
3. Run the install script. 
```
conda env create -f LTDSE.yaml
```
4.Download models
Download [[metric model](https://drive.google.com/open?id=1o-btxlWWA6GlbwMGCGkzn2vAw9qv8D2z)]
the following path:

```
 utils/metric_net/metric_model/metric_model.pt
 ```
 5. Run the demo script to test the tracker:
```
cd path/to/RTMD_MU
source activate LTDSE
python Demo.py
```

# Training tutorial
Refer to [ATOM_MU](https://github.com/Daikenan/LTMU/tree/master/ATOM_MU).
