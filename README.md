# Source code for "Force-directed graph layouts revisited: a new force based on the t-Distribution". 👋

> This repo implements a python solver, which followed `d3-force` simulation framework, for simulating forces in [t-FDP](#) model.
> Here is the t-FDP source code under clean up. If you want to find experimental data and analysis code, please refer to this [repo](https://github.com/Ideas-Laboratory/t-fdp).

## Environments
The code is tested under ubuntu 20.04.
#### Requires: Anaconda3, python3.8, gcc

#### cmd for conda install:
```
conda install -c conda-forge cupy cudatoolkit=11.1  ## cupy version=8.6.0
pip install scikit-learn pyfftw numba_kdtree torch torchvision pandas dask[dataframe]
pip install numpy==1.20.3 numba==0.54.1
```


#### Setup for BH method.
```
cd bh_tforce
python setup.py build
python setup.py install
```

#### Run the example:

```
python example.py
```


---
If you have any problem, please submit an issue or [email](zhongfahai@gmail.com) us.