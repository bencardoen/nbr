# README

Small demo on 3D volume stats with python.

### Installation

```bash
$git clone https://github.com/bencardoen/nbr.git
```

Install [MiniConda](https://conda.io/miniconda.html)

In a shell:
```bash
$conda env create -f environment.yaml
```

If that fails (I've seen it fail on OSX), install deps manually (the env file has the complete list).

### Running

```bash
$source activate nbr
$jupyter notebook
```

If your browser does not open, open it manually to url : 'localhost:8888'

### Notebooks

*Imaris.ipynb Simple HDF5 exploration of .ims format
*Analysis Rory.ipynb Statistics on csv encoded segments

