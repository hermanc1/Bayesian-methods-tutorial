# Bayesian-methods-tutorial
Data Analysis for Power and Energy Engineering made easy using Probabilistic Programming

**New to Python?**

You don't need to install Python to view this tutorial. The Jupyter notebook runs like a website on any browser.

**If you would like to install Python** in order to run the tutorial code and tinker with it yourself:

Anaconda is the easiest way to get the Python packages you need for scientific computing. If you would like to **install** Python in order to run this tutorial, do the following:

1. Go to https://www.continuum.io/downloads
2. We recommend that you select and download Python 3.5 version, but if you already have 2.7 version, it should not be a problem.
3. Once Anaconda is installed, open the Python command prompt, which you will find in your Start menu.
3. Anaconda comes with lots of useful packages. However, there are a few extra ones you will need to do Bayesian analysis: PyMC3 and its dependent libraries. These can be installed easily using the `conda` command. In the command prompt, type the following:
```python
conda install -c conda-forge pymc3
```
When asked if you want to install additional packages, type `y` and hit \<Enter\>.

Then:

```Python
conda install mingw libpython
```
Your Python installation should be all set! If you encounter any problems, Google is your friend. 

**Downloading and running the tutorial files**

The technically correct way to do it is to install `Git` on your machine, for which you will find many tutorials. The cheap and nasty way of doing it would be:

1. Click on `Clone or download` at the top right of the page.
2. Extract the zip archive to the directory of your choice.
3. Start Jupyter notebook. You can do this by finding it in the start menu. Alternatively, go the Anaconda Command Prompt as above, at type `jupyter notebook`
4. This will open a tab in your browser with a web page of your computer's directory. Navigate to where you extracted the files
5. Look for the .ipynb file and open it.
