# MUSE Weak Lensing

## Run on Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marius311/muse-wl/blob/main/TestMuse.ipynb)

First cell in the notebook installs environment using the `pyproject.toml` on the `main` branch of this repo. 

To save edits back to the repo, use `File -> Save a copy in Github`.


## Local Install

Only dependencies you need in your global Python environment:
```
pip install poetry poetry_kernel
```

Then check out the repo (everything will be installed in its own virtual environment):
```
git clone https://github.com/marius311/muse-wl
cd muse-wl
poetry install
```

Then run the notebook (with the Poetry kernel which was installed above).