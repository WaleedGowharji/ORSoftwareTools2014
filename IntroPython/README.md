# Introduction to [I]Python

## Installation Instructions
Please download and install the [Anaconda Distribution for Python](https://store.continuum.io/cshop/anaconda/).

**Remark**: [[known issue](http://stackoverflow.com/questions/23343484/python-3-statsmodels)] statsmodels 0.5.0 doesn't yet work with Python 3.4

For Mac and Linux users, open up your terminal. Windows users need to open up their Command Prompt. Change directories in the terminal (using the `cd` command) to the working directory where you want to store your IPython Notebook data.

To run IPython Notebook, enter the following command:

	ipython notebook

It may take a minute or two to set itself up, but eventually IPython Notebook will open in your default web browser. For a brief introduction to the IPython notebook, visit the following link: [introduction to the IPython notebook](http://nbviewer.ipython.org/github/esc/scipy2013-tutorial-numpy-ipython/blob/master/ipython.ipynb). For more details, visit the [IPython website](http://ipython.org/notebook.html).

**Remark**: Currently, IPython Notebook only supports Firefox and Chrome.

## Assignment
Run the `README.ipynb` notebook by entering the command:

	ipython notebook README.ipynb

Run the code the notebook, and save the output to a .txt file.  Submit the file to Stellar.

The first two lines of your output should look like:

```
                            OLS Regression Results                            
==============================================================================
```

## Lecture Instructions
- The slides are contained in `IntroPythonSlides.ipynb`, and available as a [notebook](http://nbviewer.ipython.org/github/yeesian/ORSoftwareTools2014/blob/master/IntroPython/IntroPythonSlides.ipynb), or as [slides](https://slideviewer.herokuapp.com/github/yeesian/ORSoftwareTools2014/blob/master/IntroPython/IntroPythonSlides.ipynb))
- You can browse through a HTML rendering of [each section on nbviewer](http://nbviewer.ipython.org/github/yeesian/ORSoftwareTools2014/tree/master/IntroPython/)

**README**: Installation instructions to get a working copy of [I]Python up and running with the necessary libraries.

**IntroPython0**: An introduction to the IPython notebook, teaching users how to operate the notebook in different ("Edit" and "Command") modes, loading and saving files, embedding multimedia objects, and markdown text. It is an [unmodified copy](http://nbviewer.ipython.org/github/esc/scipy2013-tutorial-numpy-ipython/blob/master/ipython.ipynb) of the same from [Valentin Haenel's 2013 Scipy tutorial](https://github.com/esc/scipy2013-tutorial-numpy-ipython/tree/master/).

**IntroPython1**: Introduces the basics of data manipulation in Python, using NumPy for array operations, pandas for working with tabular and panel data, and matplotlib for data visualization. There are some exercises at the end to test understanding of topics mentioned.

**IntroPython2**: Introduces linear and logistic regression in Python. We also introduce the idea of splitting data into a training and testing set. There are some exercises at the end to test understanding of the topics mentioned.

**IntroPython3**: Introduces CART and random forest in Python. There are some exercises at the end to test understanding of the topics mentioned.

**IntroPython4**: Demonstrates how to use hierarchical and k-means clustering. There are some exercises at the end to test understanding of the topics mentioned.

**IntroPython5**: Demonstrates how to apply Support Vector Machines in Python.
