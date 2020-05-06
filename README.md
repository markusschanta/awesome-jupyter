# Awesome Jupyter [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome [Jupyter](http://jupyter.org) projects, libraries and resources. Jupyter is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.

<h1 align="center" style="border-bottom: 0px;">
	<br>
	<img width="400" src="https://raw.githubusercontent.com/adebar/awesome-jupyter/master/logo.png" alt="Jupyter logo">
	<br>
  <br>
</h1>
<br>

## Contents

- [Runtimes/Frontends](#runtimesfrontends)
- [Collaboration/Education](#collaborationeducation)
- [Visualization](#visualization)
- [Rendering/Publishing/Conversion](#renderingpublishingconversion)
- [Version Control](#version-control)
- [JupyterLab Extensions](#jupyterlab-extensions)
- [Testing](#testing)
- [Domain-Specific Projects](#domain-specific-projects)
- [Hosted Notebook Solutions](#hosted-notebook-solutions)
- [Official Resources and Documentation](#official-resources-and-documentation)
- [Community Resources](#community-resources)
- [Articles/Guides/Tutorials](#articlesguidestutorials)
- [Contributing](#contributing)

---

## Runtimes/Frontends

- [Beaker](http://beakerx.com/) - Development environment with seamless data transmission from one language to another.
- [docker-stacks](https://github.com/jupyter/docker-stacks) - Hierarchical stacks of ready-to-run Jupyter applications in Docker.
- [Hydrogen](https://github.com/nteract/hydrogen) - Run code inline in Atom using Jupyter kernels.
- [Jupyter Notebook](https://github.com/jupyter/notebook) - Main Jupyter notebook runtime.
- [JupyterHub](https://github.com/jupyterhub/jupyterhub) - Multi-user server for Jupyter.
- [JupyterLab](https://github.com/jupyterlab/jupyterlab) - JupyterLab is the next generation user interface for Jupyter.
- [JupyterWith](https://github.com/tweag/jupyterWith) - Nix-based framework for the definition of declarative and reproducible Jupyter environments.
- [ShopRunner/jupyter-notify](https://github.com/ShopRunner/jupyter-notify) - Cell magic for browser notification of cell completion.
- [kaggle/docker-python](https://github.com/kaggle/docker-python) - Kaggle Python docker image that includes datasets and packages.
- [ML Workspace](https://github.com/ml-tooling/ml-workspace) - Docker image that includes Jupyter(Lab) and various packages for data science/machine learning.
- [nteract](https://github.com/nteract/nteract) - Native desktop notebook frontend.
- [Stencila](https://github.com/stencila/stencila) - Native desktop notebook frontend.
- [voila](https://github.com/voila-dashboards/voila) - Notebooks as interactive standalone web applications.
- [Visual Studio Code](https://code.visualstudio.com/docs/python/jupyter-support) - Native desktop notebook frontend.

## Collaboration/Education

- [callgraph](https://github.com/osteele/callgraph) - Magic to display a function call graph.
- [IllumiDesk](https://github.com/IllumiDesk/illumidesk) - Docker-based JupyterHub + LTI + nbgrader distribution for education.
- [IPythonBlocks](https://github.com/jiffyclub/ipythonblocks) - Practice Python with colored grids in Jupyter.
- [jupyter-drive](https://github.com/jupyter/jupyter-drive) - Google drive for Jupyter.
- [jupyter-viewer-xblock](https://github.com/ibleducation/jupyter-viewer-xblock) - Fetch and display part of, or an entire Jupyter Notebook in an Open edX XBlock.
- [jupyter-edx-grader-xblock](https://github.com/ibleducation/jupyter-edx-grader-xblock) - Auto-grade a student assignment created as a Jupyter notebook and write the score in the Open edX gradebook.
- [LTI Launch JupyterHub Authenticator](https://github.com/jupyterhub/ltiauthenticator) - Authentication via Edx.
- [nbautoeval](https://github.com/parmentelat/nbautoeval) - Create auto-evaluated exercises.
- [nbgrader](https://github.com/jupyter/nbgrader) - Assigning and grading of Jupyter notebooks.
- [nbtutor](https://github.com/lgpage/nbtutor) - Visualize Python code execution (line-by-line).

## Visualization

- [Altair](https://github.com/altair-viz/altair) - Declarative visualization library for Python, based on [Vega](http://vega.github.io/vega) and [Vega-Lite](https://github.com/vega/vega-lite).
- [Bokeh](https://bokeh.pydata.org/en/latest/) - Interactive visualization library that targets modern web browsers for presentation.
- [bqplot](https://github.com/bloomberg/bqplot) - Grammar of Graphics-based interactive plotting framework for Jupyter.
- [IPySigma](https://github.com/bsnacks000/IPySigma-Demo) - Prototype network visualization frontend for Jupyter notebooks.
- [ipyleaflet](https://github.com/jupyter-widgets/ipyleaflet) - Interactive visualization library for Leaflet.js maps in Jupyter notebooks.
- [ipysheet](https://github.com/QuantStack/ipysheet/) - Interactive spreadsheets in Jupyter.
- [ipytree](https://github.com/QuantStack/ipytree/) - Tree UI element for Jupyter.
- [ipywebrtc](https://github.com/maartenbreddels/ipywebrtc) - Video/Audio streaming in Jupyter.
- [ipywidgets](https://github.com/jupyter-widgets/ipywidgets) - UI widgets for Jupyter.
- [ipyvolume](https://github.com/maartenbreddels/ipyvolume) - 3D plotting for Python in Jupyter based on widgets and WebGL.
- [itk-jupyter-widgets](https://github.com/InsightSoftwareConsortium/itk-jupyter-widgets) - Interactive widgets to visualize images in 2D and 3D.
- [jp_doodle](https://github.com/AaronWatters/jp_doodle) - Infrastructure for building special purpose interactive diagrams in 2D and 3D.
- [jupyter-manim](https://github.com/krassowski/jupyter-manim) - Display [manim](https://github.com/3b1b/manim) (Mathematical Animation Engine) videos or GIFs in Jupyter notebooks.
- [jupyter-gmaps](https://github.com/pbugnion/gmaps) - Interactive visualization library for Google Maps in Jupyter notebooks.
- [mpld3](http://mpld3.github.io) - Combining Matplotlib and D3js vor interactive data visualizations.
- [pd-replicator](https://github.com/scwilkinson/pd-replicator) - Copy a pandas DataFrame to the clipboard with one click.
- [pyecharts](https://github.com/pyecharts/pyecharts) - Python interface for the [ECharts](https://github.com/apache/incubator-echarts) visualization library.
- [pythreejs](https://github.com/jovyan/pythreejs) - Python / ThreeJS bridge utilizing the Jupyter widget infrastructure.
- [Qgrid](https://github.com/quantopian/qgrid) - Interactive grid for sorting, filtering, and editing DataFrames in Jupyter notebooks.
- [tributary](https://github.com/timkpaine/tributary) - Python data streams with Jupyter support.
- [tqdm](https://github.com/tqdm/tqdm) - Fast, extensible progress bar for loops and iterables.
- [xleaflet](https://github.com/QuantStack/xleaflet) - C++ Backend for ipyleaflet.
- [xwebrtc](https://github.com/QuantStack/xwebrtc) - C++ Backend for ipywebrtc.
- [xwidgets](https://github.com/QuantStack/xwidgets) - C++ Backend for ipywidgets.

## Rendering/Publishing/Conversion

- [Binder](http://mybinder.org) - Turn a GitHub repo into a collection of interactive notebooks.
- [Bookbook](https://github.com/takluyver/bookbook) - Bookbook converts a set of notebooks in a directory to HTML or PDF, preserving cross references within and between notebooks.
- [Kapitsa](https://github.com/gitjeff05/kapitsa) - CLI to search local Jupyter notebooks.
- [nbconvert](https://nbconvert.readthedocs.io) - Convert Notebooks to other formats.
- [nbinteract](https://www.nbinteract.com) - Create interactive webpages from Jupyter notebooks.
- [nbflow](https://github.com/jhamrick/nbflow) - One-button reproducible workflows with Jupyter and Scons.
- [nbscan](https://github.com/conery/nbscan) - Search for and print cells contents of Jupyter notebooks.
- [Nikola](https://getnikola.com) - Static Site Generator that converts notebooks into websites.
- [notedown](https://github.com/aaren/notedown/) - Convert Jupyter notebooks to markdown (and back).
- [Papermill](https://github.com/nteract/papermill) - Tool for parameterizing, executing, and analyzing Jupyter notebooks.
- [pynb](https://github.com/minodes/pynb) - Jupyter Notebooks as plain Python code with embedded Markdown text.
- [RISE](https://github.com/damianavila/RISE) - Reveal.js Jupyter/IPython Slideshow.
- [rst2ipynb](https://github.com/nthiery/rst-to-ipynb) - Convert standalone reStructuredText files to Jupyter notebook file.
- [Voila](https://github.com/QuantStack/voila) - Rendering of live Jupyter Notebooks with interactive widgets, allowing dashboarding based on Jupyter Notebooks

## Version Control

- [git](https://github.com/jupyterlab/jupyterlab-git) - Extension for git integration.
- [Jupytext](https://github.com/mwouts/jupytext) - Edit, refactor and version control Jupyter Notebooks represented as scripts or Markdown documents.
- [nbdime](https://github.com/jupyter/nbdime) - Tools for diffing and merging of Jupyter notebooks.
- [ReviewNB](https://www.reviewnb.com/) - Code reviews for Jupyter Notebooks.

## JupyterLab Extensions

- [celltags](https://github.com/jupyterlab/jupyterlab-celltags) - Extension to organise and execute notebooks using cell tags.
- [code_formatter](https://github.com/ryantam626/jupyterlab_code_formatter) - A universal code formatter.
- [debugger](https://github.com/jupyterlab/debugger) - A visual debugger for Jupyter notebooks, consoles, and source files.
- [drawio](https://github.com/QuantStack/jupyterlab-drawio) - Extension that displays drawio/mxgraph diagrams.
- [go-to-definition](https://github.com/krassowski/jupyterlab-go-to-definition) - Extension for navigating to the definition of a variable or function in JupyterLab.
- [google-drive](https://github.com/jupyterlab/jupyterlab-google-drive) - Extension for Google Drive integration.
- [jupyterlab_email](https://github.com/timkpaine/jupyterlab_email) - Email notebooks and their content from within JupyterLab.
- [jupyterlab-kyso](https://github.com/kyso-io/jupyterlab-extension) - Extension to publish notebooks to the [Kyso](https://kyso.io) platform from Jupyterlab.
- [latex](https://github.com/jupyterlab/jupyterlab-latex) - Extension for live editing of LaTeX documents.
- [lsp](https://github.com/krassowski/jupyterlab-lsp) - IDE-like features (code navigation, hover suggestions, linters, diagnostics, kernel-less autocompletion etc.)
- [nb_black](https://github.com/dnanhkhoa/nb_black) - Extension to keep Python code automatically formatted using [black](https://github.com/psf/black).
- [python-bytecode](https://github.com/jtpio/jupyterlab-python-bytecode) - Explore CPython Bytecode in JupyterLab.
- [quickopen](https://github.com/parente/jupyterlab-quickopen) - Quickly open a file in JupyterLab by typing part of its name.
- [shortcutui](https://github.com/jupyterlab/jupyterlab-shortcutui) - An extension for managing keyboard shortcuts.
- [sidecar](https://github.com/jupyter-widgets/jupyterlab-sidecar) - A sidecar output widget for JupyterLab.
- [sql](https://github.com/pbugnion/jupyterlab-sql) - SQL GUI for JupyterLab.
- [system-monitor](https://github.com/jtpio/jupyterlab-system-monitor) - Extension to display system metrics.
- [templates](https://github.com/timkpaine/jupyterlab_templates) - Support for Jupyter Notebook templates.
- [theme-darcula](https://github.com/telamonian/theme-darcula) - A handsome Darcula theme for Jupyterlab.
- [toc](https://github.com/jupyterlab/jupyterlab-toc) - Extension that provides a table of contents for notebooks.
- [topbar](https://github.com/jtpio/jupyterlab-topbar) - Top Bar extension for JupyterLab.
- [variableinspector](https://github.com/lckr/jupyterlab-variableInspector) - Variable inspector extension that shows variables and their values.
- [vim](https://github.com/jwkvam/jupyterlab-vim) - Vim notebook cell bindings.
- [voyager](https://github.com/altair-viz/jupyterlab_voyager) - Extension to view CSV and JSON data in [Voyager](http://vega.github.io/voyager/).

## Testing

- [ipytest](https://github.com/chmp/ipytest) - Test runner for running unit tests from within a notebook.
- [nbval](https://github.com/computationalmodelling/nbval) - Py.test plugin for validating Jupyter notebooks.
- [sphinxcontrib-jupyter](https://github.com/QuantEcon/sphinxcontrib-jupyter) - Sphinx Extension for Generating Jupyter Notebooks.
- [nosebook](https://github.com/bollwyvl/nosebook) - Nose plugin for finding and running IPython notebooks as nose tests.
- [treon](https://github.com/ReviewNB/treon) - Easy-to-use test framework for Jupyter Notebooks.

## Domain-Specific Projects

- [ArcGIS](https://developers.arcgis.com/python/) - Library for working with maps and geospatial data, powered by web GIS.
- [GenePattern Notebook](http://genepattern-notebook.org) - Integrating Genomic Analysis with Interactive Notebooks.
- [GeoNotebook](https://github.com/OpenGeoscience/geonotebook) - Extension for exploratory geospatial analysis.
- [lolviz](https://github.com/parrt/lolviz) - Data-structure visualization tool for lists of lists, lists, dictionaries.
- [Quantopian Notebooks](https://www.quantopian.com/notebooks/survey) - Jupyter-based platform for financial research.
- [vpython-jupyter](https://github.com/BruceSherwood/vpython-jupyter) - VPython 3D engine running in a Jupyter notebook.

## Hosted Notebook Solutions

- [Anaconda Enterprise](https://www.anaconda.com/enterprise/) - Multi-user collaboration and one-click deployment of models, notebooks, and dashboards.
- [Azure Notebooks](https://notebooks.azure.com) - Jupyter notebooks running in the cloud on Microsoft Azure.
- [CoCalc](https://cocalc.com) - Notebooks with 17 supported kernel types, course management, LaTeX document authoring, simultaneous document editing and integration with the SageMath computer algebra system.
- [DataScience.com](https://www.datascience.com) - Platform for enterprise data science.
- [Deepnote](https://www.deepnote.com) - Jupyter-compatible data science notebook with real-time collaboration, versioning and easy deployment.
- [Domino Data Lab](https://www.dominodatalab.com) - Data science platform with integrated collaboration tools, environment management and compute grid.
- [Google Cloud AI Platform Notebooks](https://cloud.google.com/ai-platform-notebooks) - Managed JupyterLab notebook instances configured with GPU-enabled machine learning frameworks on Google Cloud Platform.
- [Google Cloud Dataproc Jupyter component](https://cloud.google.com/dataproc/docs/concepts/components/jupyter) - Jupyter and JupyterLab for Apache Spark using Google Cloud Dataproc.
- [Google Colaboratory](https://research.google.com/colaboratory/unregistered.html) - Cloud-based Jupyter environment aimed at machine learning education and research.
- [Gryd](https://gryd.us) - Simple, managed, ready-to-use, cloud based Jupyter notebooks supporting multiple languages.
- [Kyso](https://kyso.io) - Data science platform to publish and share Jupyter notebooks as data blogs and web applications.
- [PAWS](https://wikitech.wikimedia.org/wiki/PAWS) - Jupyter notebook deployment customized for interacting with Wikimedia wikis.
- [RMOTR Notebooks](https://notebooks.rmotr.com) - JupyterLab-based data science environment in the cloud.
- [Spell.run](https://spell.run) - End-to-end platform for machine learning and deep learning.

## Official Resources and Documentation

- [JupyterLab Documentation](http://jupyterlab.readthedocs.io/en/stable/index.html)
- [Jupyter kernels](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels) - List of all programming languages available as Jupyter kernels.
- [Making kernels for Jupyter](https://jupyter-client.readthedocs.io/en/latest/kernels.html)
- [Try Jupyter](https://try.jupyter.org) - Try Jupyter in your browser.

## Community Resources

- Conference Talks - [PyVideo.org](http://pyvideo.org/search.html?q=jupyter), [JupyterCon](https://www.youtube.com/playlist?list=PL055Epbe6d5aP6Ru42r7hk68GTSaclYgi)
- [jupyter-map](https://elc.github.io/jupyter-map/) - Map of university institutions that use Jupyter.
- Gitter - [Jupyter Gitter Chatroom](https://gitter.im/jupyter/jupyter)
- GitHub - Topics: [jupyter](https://github.com/topics/jupyter), [jupyter-kernels](https://github.com/topics/jupyter-kernels), [jupyter-notebook](https://github.com/topics/jupyter-notebook), [jupyterhub](https://github.com/topics/jupyterhub), [jupyterlab](https://github.com/topics/jupyterlab), [jupyterlab-extension](https://github.com/topics/jupyterlab-extension)
- GitHub - Search: [jupyter](https://github.com/search?type=Repositories&q=jupyter)
- Mailing Lists - [Jupyter General Mailing List](https://groups.google.com/forum/#!forum/jupyter), [Jupyter in Education Mailing List](https://groups.google.com/forum/#!forum/jupyter-education)
- PyPI - [``Framework :: Jupyter``](https://pypi.org/search/?&c=Framework+%3A%3A+Jupyter)
is the PyPI trove classifier for Jupyter projects.
- Reddit - Subreddits: [r/IPython](https://www.reddit.com/r/IPython/), [r/Jupyter/](https://www.reddit.com/r/Jupyter/)
- Stack Overflow - Tags: [jupyter](https://stackoverflow.com/questions/tagged/jupyter), [jupyter-notebook](https://stackoverflow.com/questions/tagged/jupyter-notebook)

## Articles/Guides/Tutorials

- [Exploratory computing with Python](http://mbakker7.github.io/exploratory_computing_with_python/) - Collection of notebooks covering scientific computing.
- [Gallery of Jupyter notebooks I](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)
- [Gallery of Jupyter notebooks II](http://nb.bianp.net/sort/views/)
- [How to Grow Neat Software Architecture out of Jupyter Notebooks](https://github.com/guillaume-chevalier/How-to-Grow-Neat-Software-Architecture-out-of-Jupyter-Notebooks) - Article and [video](https://www.youtube.com/watch?v=K4QN27IKr0g) about growing a neat software architecture from notebooks.
- [Install and run a Jupyter notebook in a Google Cloud Dataproc cluster](https://cloud.google.com/dataproc/docs/tutorials/jupyter-notebook)
- [Interactive Web Plotting with Bokeh](https://github.com/bokeh/bokeh-notebooks)
- [JupyterLab - Your Personal Data Science Workbench](https://github.com/markusschanta/talks/tree/master/2018-03%20-%20JupyterLab%20-%20Full%20Stack%20Quants) - Talk about JupyterLab at Full Stack Quants London.
- [Jupyter Notebook Extensions](http://jupyter-contrib-nbextensions.readthedocs.io)
- [Jupyter Notebook Themes](https://github.com/dunovank/jupyter-themes)
- [Jupyter tips, tricks and shortcuts](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)
- [Lectures on scientific computing with Python](https://github.com/jrjohansson/scientific-python-lectures)
- [The Littlest JupyterHub](https://the-littlest-jupyterhub.readthedocs.io/en/latest/) - JupyterHub distribution for 1-50 users on a single server; more lightweight than the Zero to JupyterHub setup.
- [pytudes](https://github.com/norvig/pytudes) - List of Jupyter Notebooks by Peter Norvig.
- [ResGuides: research with Jupyter](https://www.gitbook.com/book/dansand/resguides-research-with-jupyter/details)
- [Zero to JupyterHub](http://zero-to-jupyterhub.readthedocs.io/en/latest/) - Tutorial to help install and manage JupyterHub.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/adebar/awesome-jupyter/blob/master/CONTRIBUTING.md) first.
