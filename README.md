# Installation

In this course we will use [Python](https://www.python.org/). If you do not have python installed you can download the installer for your platform (Linux, Mac or Windows) from [python.org](https://www.python.org/).

We will use [pip](https://pip.pypa.io/en/stable/) to install the necessary python packages. If you do not have pip installed, you can install it following [this guide](https://pip.pypa.io/en/stable/installation/#python).

You can check wether pip is installed on your computer by running on a terminal:
```bash
pip --version
```
which should print the version of pip you have installed.

In order to install the course dependencies using pip, run:
```
pip install torch matplotlib notebook
```

# Running a Jupyter Notebook

In this course we will use Jupyter notebooks, which allow us to write and run code interactively from a browser. 

To start a jupyter server just run from a terminal:
```
jupyter notebook
```

This should open a browser window showing a file explorer. Note that although the interface runs on the browser, the server is actually running on the terminal and therefore you should not close it.

Then you can navigate to the desired folder and open a notebook by just clicking on the file, or create a notebook by clicking on the `New` button. Notebooks are text files with the extension `.ipynb`. 

Notebooks are made up of cells that can contain either text (in [markdown](https://en.wikipedia.org/wiki/Markdown) format) or python code. Code cells can be run (by selecting the cell and clicking on the run button) and the code's output is displayed below the code cell that generated it.
