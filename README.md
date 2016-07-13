# Scaling Data Science in Python Tutorial

Tutorial on Scaling Data Science in Python at Data Science Summit SF 2016
Slides: TODO

## Setup

### Clone or download the repo
First get local copies of the tutorial notebooks:

```
$ git clone https://github.com/chdoig/dss-scaling-tutorial.git
```

Or download from: https://github.com/chdoig/dss-scaling-tutorial/archive/master.zip

### Install the dependencies

This tutorial has been tested on:
* bokeh=0.12.0
* pandas=0.18.1
* dask=0.10.0
* datashader=0.3.2
* jupyter=1.0.0

Other combinations may work also. Packages are available via PyPI and anaconda.org.

#### Installing with Anaconda

Install [anaconda](http://continuum.io/downloads)

Anaconda should come with all the dependencies included, but you may need to update your versions.

#### Install with miniconda

Install [miniconda](http://conda.pydata.org/miniconda.html).

Use the command line to create an environment and install the packages:

```
$ conda create -n dss_scaling python=3.4
$ source activate dss_scaling
$ conda install bokeh pandas jupyter dask
$ conda install -c bokeh datashader
```

### Run Jupyter/IPython notebook

From this folder run jupyter notebook, and open the notebooks.

```
$ jupyter notebook
```