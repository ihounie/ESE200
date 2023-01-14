# Installation

In this course we will use [Python](https://www.python.org/) and [conda](https://docs.conda.io/en/latest/miniconda.html) to install the necessary dependencies.
You can check wether you have conda installed by running 
```
conda --version
```
which should print the version of conda that you have installed.

You can install miniconda by downloading the latest version of the the installer for your platform (Linux, Mac or Windows) from [this site](https://docs.conda.io/en/latest/miniconda.html). Then you simply run the downloaded file (you can also find detailed installation instructions [here](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

Once you installed conda you can create a new environment for the course and install all dependencies by running on a terminal:
```
conda create -n ese200 python=3.8 matplotlib notebook pytorch torchvision torchaudio -c pytorch
```
Everytime you want to run code or install packages in this environment from a new terminal you have to run:
```
conda activate ese200
```

# Running a Jupyter Notebook

In this course we will use Jupyter notebooks, which allow us to write and run code interactively from a browser. 

To start a jupyter server just run from a terminal (after activating the conda environment):
```
jupyter notebook
```

This should open a browser window showing a file explorer. Note that although the interface runs on the browser, the server is actually running on the terminal and therefore you should not close it.

Then you can navigate to the desired folder and open a notebook by just clicking on the file, or create a notebook by clicking on the `New` button. Notebooks are text files with the extension `.ipynb`. 

Notebooks are made up of cells that can contain either text (in [markdown](https://en.wikipedia.org/wiki/Markdown) format) or python code. Code cells can be run by selecting the cell and clicking on the run button, and the code's output is displayed below the code cell that generated it.
