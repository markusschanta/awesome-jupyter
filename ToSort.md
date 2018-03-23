# Awesome

## Customization
* [Custom Jupyter Notebook Themes](https://github.com/dunovank/jupyter-themes)
* [Unofficial Jupyter Notebook Extensions](http://jupyter-contrib-nbextensions.readthedocs.io)
* [Unofficial Jupyter Notebook Extensions](https://github.com/ipython-contrib/jupyter_contrib_nbextensions)

## Tutorials/Documentation
* [Exploratory computing with Python by Mark Bakker](http://mbakker7.github.io/exploratory_computing_with_python/)
* [Lectures on scientific computing with Python](https://github.com/jrjohansson/scientific-python-lectures)
* [Install and run a Jupyter notebook in a Google Cloud Dataproc cluster](https://cloud.google.com/dataproc/docs/tutorials/jupyter-notebook)
* [Interactive Web Plotting with Bokeh in IPython notebook](https://github.com/bokeh/bokeh-notebooks)
* [Jupyter tips, tricks and shortcuts](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)
* [List of Jupyter Notebooks by Peter Norvig](https://github.com/norvig/pytudes)
* [Notebook Gallery](http://nb.bianp.net/sort/views/) - links to the best Jupyter Notebooks.
* [ResGuides: research with Jupyter](https://www.gitbook.com/book/dansand/resguides-research-with-jupyter/details)

## Official
* [Making kernels for Jupyter](https://jupyter-client.readthedocs.io/en/latest/kernels.html)
* https://github.com/jupyter/jupyter/wiki/Jupyter-kernels
* [JupyterLab Documentation](http://jupyterlab.readthedocs.io/en/stable/index.html)
* [Try Jupyter](https://try.jupyter.org/) - Try Jupyter in your browser.

## Hosted
* [Google Colaboratory](https://research.google.com/colaboratory/unregistered.html)
* [Gryd](https://gryd.us/)

## Teaching
* [IPythonBlocks](http://ipythonblocks.org/)
* [LTI Launch JupyterHub Authenticator](https://github.com/jupyterhub/ltiauthenticator) - Implements LTI v1 authenticator for use with JupyterHub.

## Community

* [Teaching with Jupyter Notebooks](https://groups.google.com/forum/#!forum/jupyter-education) - mailing list.
* https://groups.google.com/forum/#!forum/jupyter
* https://jupyter.org/community.html
* https://stackoverflow.com/questions/tagged/jupyter-notebook
* https://www.reddit.com/r/IPython/
* https://www.reddit.com/r/Jupyter/

## Domain-specific

* [VPython running in a Jupyter notebook](https://github.com/BruceSherwood/vpython-jupyter)
* [lolviz](https://github.com/parrt/lolviz) - data-structure visualization tool for lists of lists, lists, dictionaries

## Education

* [nbautoeval](https://github.com/parmentelat/nbautoeval) - creating auto-evaluated exercises.
* [nbtutor](https://github.com/lgpage/nbtutor) - visualize Python code execution (line-by-line).

## Testing

* [nbval](https://github.com/computationalmodelling/nbval) - Py.test plugin for validating Jupyter notebooks. => Testing
* [sphinxcontrib-jupyter](https://github.com/QuantEcon/sphinxcontrib-jupyter) - A Sphinx Extension for Generating Jupyter Notebooks
* [nosebook](https://github.com/bollwyvl/nosebook) - nose plugin for finding and running IPython notebooks as nose tests.=> Testing

## Runtimes

* [docker-stacks](https://github.com/jupyter/docker-stacks) - Hierarchical stacks of ready-to-run Jupyter applications in Docker
* [kaggle/docker-python](https://github.com/kaggle/docker-python) - Kaggle Python docker image that includes datasets and packages

## Category unclear

* [nbconvert](https://nbconvert.readthedocs.io/) - convert Notebooks to other formats.
* [nbinteract](https://www.nbinteract.com/) - creates interactive webpages from Jupyter notebooks.
* [nbscan](https://github.com/conery/nbscan) - search for and print contents of cells in Jupyter notebooks.
* [notedown](https://github.com/aaren/notedown/) - Convert Jupyter Notebooks to markdown (and back).
* [pynb](https://github.com/minodes/pynb) - Jupyter Notebooks as plain Python code with embedded Markdown text.
* [rst2ipynb](https://github.com/nthiery/rst-to-ipynb) - convert standalone reStructuredText files to Jupyter notebook file.

# Not so awesome

* [The World of Jupyter — a Tutorial](https://github.com/barbagroup/jupyter-tutorial)
  * A bit dated
* [IPython](http://ipython.org/) is an ancestor of Jupyter project, and now it's a Python kernel for Jupyter.
  * Probably not worth including just for historical reasons; no individual kernels
* [Jupyter Notebook cheatsheet](https://www.cheatography.com/weidadeyue/cheat-sheets/jupyter-notebook/)
  * Obsolete with the Commands tab in JupyterLab
* [Jupyter Notebook on Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/virtual-machines-linux-jupyter-notebook)
  * Article does not seem to exist anymore, page redirects
* [Jupyter Notebook on FullStackPython](https://www.fullstackpython.com/jupyter-notebook.html)
  * Most of the resources on this list are mentioned here anyway
* [NBViewer](https://nbviewer.jupyter.org/) can render your public notebook from GitHub repo or any URL.
  * GitHub can render notebooks out-of-the box. This probably makes NBViewer obsolete. Please correct me if that's not the case.
* [Using the IPython Notebook as a Teaching Tool](https://software-carpentry.org/blog/2013/03/using-notebook-as-a-teaching-tool.html)
  * A bit dated; not all that useful.
* [nbTranslate](https://github.com/jfbercher/jupyter_nbTranslate) - translate cells of a notebook from one language to another - Adds multi language support.
  * not sure if useful; feel free to suggest to include this
* [nbtranslate](https://github.com/devrt/nbtranslate) - translate content of Jupyter notebook using gettext tools.
  * not sure if useful; feel free to suggest to include this
* [https://github.com/taavi/ipython_nose]
  * not sure if useful; feel free to suggest to include this
* [runipy](https://pypi.python.org/pypi/runipy)
  * deprecated, use [Jupyter's execute API instead](http://nbconvert.readthedocs.io/en/latest/execute_api.html)
* [ipynb](https://github.com/ipython/ipynb) - Package / Module importer for importing code from Jupyter Notebook files (.ipynb)
  * Looks like an anti-pattern, porting code to a library seems preferable
* [pypi Jupyter](https://pypi.org/search/?q=Jupyter) - Packages on pypi that match the search term "Jupyter"
  * not a particularly useful way to discover Jupyter packages
