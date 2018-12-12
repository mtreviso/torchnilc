# TorchNILC

Minicurso de como implementar modelos neurais para PLN usando o PyTorch.

## Installation 

First, clone this repository using `git`:

```sh
git clone https://github.com/mtreviso/torchnilc.git
```

 Then, `cd` to the TorchNILC folder:
```sh
cd torchnilc
```

Automatically create a Python virtualenv and install all dependencies 
using `pipenv install`. And then activate the virtualenv with `pipenv shell`:
```sh
pip3 install pipenv
pipenv install --skip-lock
pipenv shell
```

The `--skip-lock` flag informs pipenv to ignore its lock mechanism, so it works just like pip in a virtual env and then it performs a faster installation.
<!-- 
Run the install command:
```sh
python3 setup.py install
```
 -->

Please note that since Python 3 is required, all the above commands (pip/python) 
have to be the Python 3 version.

Afterwards, we are going to install the torchnilc package when we complete the course. For now, 
just run and follow the first notebook:

```bash
cd torchnilc/notebooks
jupyter-notebook 
``` 