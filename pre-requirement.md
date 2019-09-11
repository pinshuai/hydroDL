## installation steps on Mac

- install Anaconda
- create new conda env
```bash
conda create -n DL python=3.7 basemap pandas scipy statmodels
```
- install [PyTorch](https://pytorch.org/)
```bash
(DL) $ conda install pytorch torchvision cpuonly -c pytorch # cpuonly
```
- `git clone` this repo and run on Jupyter