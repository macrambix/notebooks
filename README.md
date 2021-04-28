# Python environment for Jupyter Lab Notebooks with requirements.txt

 - Convert a tecplot file using layers into GemPy format : ```convert_lay2gp.ipynb``` 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/macrambix/notebooks/master)

A Binder-compatible repo with a `requirements.txt` file.

Access this Binder at the following URL 

https://mybinder.org/v2/gh/macrambix/notebooks/master

## Notes
The `requirements.txt` file should list all Python libraries that your notebooks
depend on, and they will be installed using:

```
pip install -r requirements.txt
```

The base Binder image contains no extra dependencies, so be as
explicit as possible in defining the packages that you need. This includes
specifying explict versions wherever possible.

In this example we include the library `seaborn` which will be installed in
the environment, and our notebook uses it to plot a figure.

# gempy-examples
Things based on [GemPy](https://github.com/cgre-aachen/gempy). All demonstrated on a simple example model with five different lithologies and no fault:

![](figs/Figure_19.png)

**Important note:** It is not guaranteed that these notebooks will run with the main version of gempy. Gempy is in active development and things are changing fast, which can lead to errors when running code in these notebooks.

#### plot_2d results
![](figs/Figure_13.png)

### ...
