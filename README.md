# Awesome Jupyter [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome [Jupyter](http://jupyter.org/) projects, libraries and resources. Jupyter is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.

<h1 align="center" style="border-bottom: 0px;">
	<br>
	<img width="400" src="https://raw.githubusercontent.com/adebar/awesome-jupyter/master/logo.png" alt="Jupyter logo">
	<br>
  <br>
</h1>
<br>

## Contents

- [Awesome Jupyter](#awesome-jupyter)

    - [Runtimes/Frontends](#runtimesfrontends)
    - [Collaboration/Education](#collaborationeducation)
    - [Visualization](#visualization)
    - [Rendering/Publishing/Conversion](#renderingpublishingconversion)
    - [Testing](#testing)
    - [Domain-Specific Projects](#domain-specific-projects)
    - [Hosted Notebook Solutions](#hosted-notebook-solutions)
    - [Official Resources and Documentation](#official-resources-and-documentation)
    - [Community Resources](#community-resources)
    - [Articles/Guides/Tutorials](#articlesguidestutorials)
    - [Jupyter Notebook, JupyterHub, JupyterLab](#jupyter-notebook-jupyterhub-jupyterlab)
      - [Framework :: Jupyter](#framework--jupyter)
      - [Jupyter GitHub Topics](#jupyter-github-topics)
- [Contributing](#contributing)

- - -


## Runtimes/Frontends

* [Beaker](http://beakernotebook.com/) - Development environment with seamless data transmission from one language to another.
* [docker-stacks](https://github.com/jupyter/docker-stacks) - Hierarchical stacks of ready-to-run Jupyter applications in Docker.
* [Hydrogen](https://github.com/nteract/hydrogen) - Run code inline in Atom using Jupyter kernels.
* [Jupyter Notebook](https://github.com/jupyter/notebook) - Main Jupyter notebook runtime.
* [JupyterHub](https://github.com/jupyterhub/jupyterhub) - Multi-user server for Jupyter.
* [JupyterLab](https://github.com/jupyterlab/jupyterlab) - JupyterLab is the next generation user interface for Jupyter.
* [kaggle/docker-python](https://github.com/kaggle/docker-python) - Kaggle Python docker image that includes datasets and packages.
* [nteract](https://github.com/nteract/nteract) - Native desktop notebook frontend.
* [Rodeo](https://www.yhat.com/products/rodeo) - Native Python IDE for Data Science.
* [Stencila](https://github.com/stencila/stencila) - Native desktop notebook frontend.

## Collaboration/Education

* [callgraph](https://github.com/osteele/callgraph) - Magic to display a function call graph.
* [IPythonBlocks](https://github.com/jiffyclub/ipythonblocks) - Practice Python with colored grids in Jupyer.
* [jupyter-drive](https://github.com/jupyter/jupyter-drive) - Google drive for Jupyter.
* [jupyter-viewer-xblock](https://github.com/ibleducation/jupyter-viewer-xblock) - Fetch and display part of, or an entire Jupyter Notebook in an Open edX XBlock.
* [LTI Launch JupyterHub Authenticator](https://github.com/jupyterhub/ltiauthenticator) - Authentication via Edx.
* [nbautoeval](https://github.com/parmentelat/nbautoeval) - Create auto-evaluated exercises.
* [nbgrader](https://github.com/jupyter/nbgrader) - Assigning and grading of Jupyter notebooks.
* [nbtutor](https://github.com/lgpage/nbtutor) - Visualize Python code execution (line-by-line).

## Visualization

* [Altair](https://github.com/altair-viz/altair) - Declarative visualization library for Python, based on [Vega](http://vega.github.io/vega) and [Vega-Lite](https://github.com/vega/vega-lite).
* [Bokeh](https://bokeh.pydata.org/en/latest/) - Interactive visualization library that targets modern web browsers for presentation.
* [bqplot](https://github.com/bloomberg/bqplot) - Grammar of Graphics-based interactive plotting framework for Jupyter.
* [IPySigma](https://github.com/bsnacks000/IPySigma-Demo) - Prototype network visualization frontend for Jupyter notebooks.
* [ipywidgets](https://github.com/jupyter-widgets/ipywidgets) - UI widgets for Jupyter.
* [jupyterlab_voyager](https://github.com/altair-viz/jupyterlab_voyager) - Extension to view CSV and JSON data in [Voyager](http://vega.github.io/voyager/).
* [mpld3](http://mpld3.github.io/) - Combining Matplotlib and D3js vor interactive data visualizations.
* [pythreejs](https://github.com/jovyan/pythreejs) - Python / ThreeJS bridge utilizing the Jupyter widget infrastructure.
* [Qgrid](https://github.com/quantopian/qgrid) - Interactive grid for sorting, filtering, and editing DataFrames in Jupyter notebooks.

## Rendering/Publishing/Conversion

* [Binder](http://mybinder.org/) - Turn a GitHub repo into a collection of interactive notebooks.
* [Bookbook](https://github.com/takluyver/bookbook) - Bookbook converts a set of notebooks in a directory to HTML or PDF, preserving cross references within and between notebooks.
* [nbconvert](https://nbconvert.readthedocs.io/) - Convert Notebooks to other formats.
* [nbdime](https://github.com/jupyter/nbdime) - Tools for diffing and merging of Jupyter notebooks.
* [nbinteract](https://www.nbinteract.com/) - Create interactive webpages from Jupyter notebooks.
* [nbflow](https://github.com/jhamrick/nbflow) - One-button reproducible workflows with Jupyter and Scons.
* [nbscan](https://github.com/conery/nbscan) - Search for and print cells contents of Jupyter notebooks.
* [Nikola](https://getnikola.com/) - Static Site Generator that converts notebooks into websites.
* [notedown](https://github.com/aaren/notedown/) - Convert Jupyter notebooks to markdown (and back).
* [Papermill](https://github.com/nteract/papermill) - Tool for parameterizing, executing, and analyzing Jupyter notebooks.
* [pynb](https://github.com/minodes/pynb) - Jupyter Notebooks as plain Python code with embedded Markdown text.
* [RISE](https://github.com/damianavila/RISE) - Reveal.js Jupyter/IPython Slideshow.
* [rst2ipynb](https://github.com/nthiery/rst-to-ipynb) - convert standalone reStructuredText files to Jupyter notebook file.

## Testing

* [nbval](https://github.com/computationalmodelling/nbval) - Py.test plugin for validating Jupyter notebooks.
* [sphinxcontrib-jupyter](https://github.com/QuantEcon/sphinxcontrib-jupyter) - Sphinx Extension for Generating Jupyter Notebooks.
* [nosebook](https://github.com/bollwyvl/nosebook) - Nose plugin for finding and running IPython notebooks as nose tests.

## Domain-Specific Projects

* [GenePattern Notebook](http://genepattern-notebook.org/) - Integrating Genomic Analysis with Interactive Notebooks.
* [GeoNotebook](https://github.com/OpenGeoscience/geonotebook) - Extension for exploratory geospatial analysis.
* [lolviz](https://github.com/parrt/lolviz) - Data-structure visualization tool for lists of lists, lists, dictionaries.
* [Quantopian Notebooks](https://www.quantopian.com/notebooks/survey) - Jupyter-based platform for financial research.
* [vpython-jupyter](https://github.com/BruceSherwood/vpython-jupyter) - VPython 3D engine running in a Jupyter notebook.

## Hosted Notebook Solutions

* [Anaconda Enterprise](https://www.anaconda.com/enterprise/) - Multi-user collaboration and one-click deployment of models, notebooks, and dashboards.
* [Azure Notebooks](https://notebooks.azure.com/) - Jupyter notebooks running in the cloud on Microsoft Azure.
* [CoCalc](https://cocalc.com/) - Notebooks with 17 supported kernel types, course management, LaTeX document authoring, simultaneous document editing and integration with the SageMath computer algebra system.
* [DataScience.com](https://www.datascience.com/) - Platform for enterprise data science.
* [Domino Data Lab](https://www.dominodatalab.com/) - Data science platform with integrated collaboration tools, environment management and compute grid.
* [Google Cloud Datalab](https://cloud.google.com/datalab/) - Notebook platform integrated with the Google Cloud stack.
* [Google Colaboratory](https://research.google.com/colaboratory/unregistered.html) - Cloud-based Jupyter environment aimed at machine learning education and research.
* [Gryd](https://gryd.us/) - Simple, managed, ready-to-use, cloud based Jupyter notebooks supporting multiple languages.
* [PAWS](https://wikitech.wikimedia.org/wiki/PAWS) - Jupyter notebook deployment customized for interacting with Wikimedia wikis.

## Official Resources and Documentation

* [JupyterLab Documentation](http://jupyterlab.readthedocs.io/en/stable/index.html)
* [Jupyter kernels](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels) - List of all programming languages available as Jupyter kernels.
* [Making kernels for Jupyter](https://jupyter-client.readthedocs.io/en/latest/kernels.html)
* [Try Jupyter](https://try.jupyter.org/) - Try Jupyter in your browser.

## Community Resources

* Conference Talks - [PyVideo.org](http://pyvideo.org/search.html?q=jupyter), [JupyterCon](https://www.youtube.com/playlist?list=PL055Epbe6d5aP6Ru42r7hk68GTSaclYgi)
* [jupyter-map](https://elc.github.io/jupyter-map/) - Map of university institutions that use Jupyter.
* Gitter - [Jupyter Gitter Chatroom](https://gitter.im/jupyter/jupyter)
* Mailing Lists - [Jupyter General Mailing List](https://groups.google.com/forum/#!forum/jupyter), [Jupyter in Education Mailing List](https://groups.google.com/forum/#!forum/jupyter-education)
* Reddit - Subreddits: [r/IPython](https://www.reddit.com/r/IPython/), [r/Jupyter/](https://www.reddit.com/r/Jupyter/)
* Stackoverflow - Tags: [jupyter](https://stackoverflow.com/questions/tagged/jupyter), [jupyter-notebook](https://stackoverflow.com/questions/tagged/jupyter-notebook)

## Articles/Guides/Tutorials

* [Exploratory computing with Python](http://mbakker7.github.io/exploratory_computing_with_python/) - Collection of notebooks covering scientific computing.
* [Gallery of Jupyter notebooks I](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)
* [Gallery of Jupyter notebooks II](http://nb.bianp.net/sort/views/)
* [Install and run a Jupyter notebook in a Google Cloud Dataproc cluster](https://cloud.google.com/dataproc/docs/tutorials/jupyter-notebook)
* [Interactive Web Plotting with Bokeh](https://github.com/bokeh/bokeh-notebooks)
* [JupyterLab - Your Personal Data Science Workbench](https://github.com/markusschanta/talks/tree/master/2018-03%20-%20JupyterLab%20-%20Full%20Stack%20Quants) - Talk about JupyterLab at Full Stack Quants London.
* [Jupyter Notebook Extensions](http://jupyter-contrib-nbextensions.readthedocs.io)
* [Jupyter Notebook Themes](https://github.com/dunovank/jupyter-themes)
* [Jupyter tips, tricks and shortcuts](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)
* [Lectures on scientific computing with Python](https://github.com/jrjohansson/scientific-python-lectures)
* [pytudes](https://github.com/norvig/pytudes) - List of Jupyter Notebooks by Peter Norvig.
* [ResGuides: research with Jupyter](https://www.gitbook.com/book/dansand/resguides-research-with-jupyter/details)
* [Zero to JupyterHub](http://zero-to-jupyterhub.readthedocs.io/en/latest/) - Tutorial to help install and manage JupyterHub.

## Jupyter Notebook, JupyterHub, JupyterLab
- Jupyter Organization
  -
  - Homepage: https://jupyter.org/
  - Homepage: https://jupyter.github.io/
  - Community: https://jupyter.org/community
    - Help: https://github.com/jupyter/help
    - Mailing List: https://groups.google.com/forum/#!forum/jupyter
    - Mailing List: https://groups.google.com/forum/#!forum/jupyter-education
    - Mailing List: https://groups.google.com/forum/?pli=1#!forum/jupyter-research-facilities
    - Chat: https://gitter.im/jupyter/jupyter
    - Q&A: http://stackoverflow.com/questions/tagged/jupyter
  - Source: https://github.com/jupyter
  - Docs: https://jupyter.org/documentation
  - Docs: **https://jupyter.readthedocs.io/en/stable/**
  - Jupyter Governance
    https://github.com/jupyter/governance
    - JEP: Jupyter Enhancement Proposal
      - https://github.com/jupyter/enhancement-proposals
  - Blog: https://blog.jupyter.org/
  - Twitter: [@ProjectJupyter](https://twitter.com/ProjectJupyter)
- Jupyter Notebook
  -
  - Source: https://github.com/jupyter/notebook
  - Docs: https://jupyter-notebook.readthedocs.io/en/stable/
  - https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks
- IPython
  -
  - Source: https://github.com/ipython
  - Source: https://github.com/ipython/ipython
  - Docs: http://github.com/ipython/ipython/wiki
  - IPEP: IPython Enhancement Proposal
    https://github.com/ipython/ipython/wiki/IPEPs:-IPython-Enhancement-Proposals
- JupyterHub
  -
  - Source: https://github.com/jupyterhub
  - Source: https://github.com/jupyterhub/jupyterhub
  - Docs: https://jupyterhub.readthedocs.io/en/stable/
  - Docs: https://github.com/jupyterhub/jupyterhub/wiki
    - JupyterHub Authenticators: https://github.com/jupyterhub/jupyterhub/wiki/Authenticators
    - JupyterHub Spawners: https://github.com/jupyterhub/jupyterhub/wiki/Spawners
  - https://zero-to-jupyterhub.readthedocs.io/en/latest/ (with Kubernetes)
- BinderHub
  -
  - https://mybinder.org/
  - Source: https://github.com/jupyterhub/binderhub
  - Source: https://github.com/jupyter/repo2docker
  - Docs: https://binderhub.readthedocs.io/en/latest/
  - Docs: https://repo2docker.readthedocs.io/en/latest/usage.html
- JupyterLab
  -
  - Source: https://github.com/jupyterlab
  - Source: https://github.com/jupyterlab/jupyterlab
  - Docs: https://jupyterlab.readthedocs.io/en/stable/
  - Docs: https://jupyter.org/documentation

### Framework :: Jupyter
[``Framework :: Jupyter``](https://pypi.org/search/?&c=Framework+%3A%3A+Jupyter)
is the PyPI trove classifier for Jupyter projects.

### Jupyter GitHub Topics
- [ipython](https://github.com/topics/ipython)
- [jupyter](https://github.com/topics/jupyter)
- [jupyter-notebook](https://github.com/topics/jupyter-notebook)
- [jupyter-kernels](https://github.com/topics/jupyter-kernels)
- [jupyter-extension](https://github.com/topics/jupyter-extension)
- [jupyterhub](https://github.com/topics/jupyterhub)
- [jupyterlab](https://github.com/topics/jupyterlab)
- [jupyterlab-extension](https://github.com/topics/jupyterlab-extension)
- https://gitlab.com/explore/projects?name=jupyter
- https://github.com/search?type=Repositories&q=jupyter

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/adebar/awesome-jupyter/blob/master/CONTRIBUTING.md) first.
