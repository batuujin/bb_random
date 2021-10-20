# Jupyter notebooks
Jupyter notebooks are a convenient, interactive way of using python, for data analysis, generating plots and more.
They allow for easy cell-based code execution so you can run your code in smaller chunks rather than all at once. 
There are two ways in which you can use jupyter notebooks, either as separate jupyter notebooks or through jupyterlab.
- **Jupyter notebook**: Opens one specific notebook in a browser window and you can work within it. You can have multiple notebooks open at the same time as well.
It is generally cleaner and faster than jupyterlab.
- **Jupyter lab**: Opens a browser window where you can navigate through your filetree and have multiple notebooks open inside that single browser window. 
While a bit slower, jupyterlab can be a convenient way to work on multiple notebooks at once. 

## Installation:
Here's some basic instructions to get jupyter lab / notebook running. More information can be found here: https://jupyter.org/install
### Installing through conda:
Install anaconda or miniconda, depending on preference
- If you installed anaconda, jupyter notebook and jupyter lab are already installed in your environment, so no need to re-install it. Skip straight to "Running Jupyter"
- If you installed miniconda, you have to install jupyter notebook and / or jupyter lab along with other packages you might need. To do this:
 Activate your favorite conda environment and then install jupyterlab and jupyter notebook:
```
conda activate <environment_name>

conda install -c conda-forge jupyterlab
conda install -c conda-forge notebook
```
Generally, now would be a good idea to install other useful python packages like numpy, pandas, rdkit, obabel etc., IF you are in a new, empty environment. 
Most of these packages are available through conda, 
with the following pattern `conda install -c conda-forge <package_name>`

### Installing through pip:
If you'd rather install jupyter notebook and / or jupyter-lab through pip, simply run:
```
pip install notebook
pip install jupyterlab
```

## Running Jupyter:
- To run jupyter notebook, execute: `jupyter-notebook`
- To run jupyter lab, execute: `jupyter-lab`


## Fun things you can do with Jupyter notebook

- insert a short rdkit tutorial to show drawn molecules and with meeko to write a pdbqt from smiles 

