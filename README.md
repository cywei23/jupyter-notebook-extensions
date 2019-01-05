# Jupyter Notebook Extensions

Jupyter notebook extensions are simple add-ons that extend the functionality of Jupyter Notebooks.

They can be installed with

```
pip install jupyter_contrib_nbextensions
jupyter contrib nbextensions install
```

This will install a collection of extensions from [here](https://github.com/ipython-contrib/jupyter_contrib_nbextensions)

[Article on extensions](https://towardsdatascience.com/jupyter-notebook-extensions-517fa69d2231)

## Writing Your Own Extensions

It's possible to write your own extensions to add anything you can think of to Jupyter Notebooks.
The documentation is scarce, but try looking through some of the other examples to get the basics. [Here's the extent](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/internals.html)
of the existing documentation.

The point of this repository is to develop new Jupyter Notebook extensions. Any of the extensions here
should be added to the `nbextensions` subdirectory of the  `jupyter_contrib_nbextensions` library installed
with pip. You can find the location of the library using `pip show jupyter_contrib_nbextensions`. 

For example, I place the new extensions at `C:\Users\XX\Anaconda3\lib\site-packages\jupyter_contrib_nbextensions\nbextensions\`

Each extension has three parts: `name.yaml` file with configuration, `README.md` with documentation,
and `main.js` with the Javascript code. 

Feel free to contribute your own extensions or add on to those available here. 
