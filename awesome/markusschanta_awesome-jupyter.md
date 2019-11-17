# Information comes from [markusschanta/awesome-jupyter](https://github.com/markusschanta/awesome-jupyter)
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
- [docker-stacks](https://github.com/jupyter/docker-stacks) - Hierarchical stacks of ready-to-run Jupyter applications in Docker. :star:4476
- [Hydrogen](https://github.com/nteract/hydrogen) - Run code inline in Atom using Jupyter kernels. :star:3405
- [Jupyter Notebook](https://github.com/jupyter/notebook) - Main Jupyter notebook runtime. :star:6520
- [JupyterHub](https://github.com/jupyterhub/jupyterhub) - Multi-user server for Jupyter. :star:5185
- [JupyterLab](https://github.com/jupyterlab/jupyterlab) - JupyterLab is the next generation user interface for Jupyter. :star:9067
- [JupyterWith](https://github.com/tweag/jupyterWith) - Nix-based framework for the definition of declarative and reproducible Jupyter environments. :star:98
- [ShopRunner/jupyter-notify](https://github.com/ShopRunner/jupyter-notify) - Cell magic for browser notification of cell completion. :star:349
- [kaggle/docker-python](https://github.com/kaggle/docker-python) - Kaggle Python docker image that includes datasets and packages. :star:1134
- [ML Workspace](https://github.com/ml-tooling/ml-workspace) - Docker image that includes Jupyter(Lab) and various packages for data science/machine learning. :star:696
- [nteract](https://github.com/nteract/nteract) - Native desktop notebook frontend. :star:4534
- [Stencila](https://github.com/stencila/stencila) - Native desktop notebook frontend. :star:549

## Collaboration/Education

- [callgraph](https://github.com/osteele/callgraph) - Magic to display a function call graph. :star:30
- [IPythonBlocks](https://github.com/jiffyclub/ipythonblocks) - Practice Python with colored grids in Jupyter. :star:147
- [jupyter-drive](https://github.com/jupyter/jupyter-drive) - Google drive for Jupyter. :star:391
- [jupyter-viewer-xblock](https://github.com/ibleducation/jupyter-viewer-xblock) - Fetch and display part of, or an entire Jupyter Notebook in an Open edX XBlock. :star:20
- [jupyter-edx-grader-xblock](https://github.com/ibleducation/jupyter-edx-grader-xblock) - Auto-grade a student assignment created as a Jupyter notebook and write the score in the Open edX gradebook. :star:28
- [LTI Launch JupyterHub Authenticator](https://github.com/jupyterhub/ltiauthenticator) - Authentication via Edx. :star:23
- [nbautoeval](https://github.com/parmentelat/nbautoeval) - Create auto-evaluated exercises. :star:5
- [nbgrader](https://github.com/jupyter/nbgrader) - Assigning and grading of Jupyter notebooks. :star:831
- [nbtutor](https://github.com/lgpage/nbtutor) - Visualize Python code execution (line-by-line). :star:351

## Visualization

- [Altair](https://github.com/altair-viz/altair) - Declarative visualization library for Python, based on [Vega](http://vega.github.io/vega) and [Vega-Lite](https://github.com/vega/vega-lite). :star:4304
- [Bokeh](https://bokeh.pydata.org/en/latest/) - Interactive visualization library that targets modern web browsers for presentation.
- [bqplot](https://github.com/bloomberg/bqplot) - Grammar of Graphics-based interactive plotting framework for Jupyter. :star:2557
- [IPySigma](https://github.com/bsnacks000/IPySigma-Demo) - Prototype network visualization frontend for Jupyter notebooks. :star:11
- [ipyleaflet](https://github.com/jupyter-widgets/ipyleaflet) - Interactive visualization library for Leaflet.js maps in Jupyter notebooks. :star:775
- [ipysheet](https://github.com/QuantStack/ipysheet/) - Interactive spreadsheets in Jupyter. :star:227
- [ipytree](https://github.com/QuantStack/ipytree/) - Tree UI element for Jupyter. :star:29
- [ipywebrtc](https://github.com/maartenbreddels/ipywebrtc) - Video/Audio streaming in Jupyter. :star:96
- [ipywidgets](https://github.com/jupyter-widgets/ipywidgets) - UI widgets for Jupyter. :star:1611
- [ipyvolume](https://github.com/maartenbreddels/ipyvolume) - 3D plotting for Python in Jupyter based on widgets and WebGL. :star:1238
- [itk-jupyter-widgets](https://github.com/InsightSoftwareConsortium/itk-jupyter-widgets) - Interactive widgets to visualize images in 2D and 3D. :star:190
- [jp_doodle](https://github.com/AaronWatters/jp_doodle) - Infrastructure for building special purpose interactive diagrams in 2D and 3D. :star:13
- [jupyter-gmaps](https://github.com/pbugnion/gmaps) - Interactive visualization library for Google Maps in Jupyter notebooks. :star:604
- [mpld3](http://mpld3.github.io) - Combining Matplotlib and D3js vor interactive data visualizations.
- [pyecharts](https://github.com/pyecharts/pyecharts) - Python interface for the [ECharts](https://github.com/apache/incubator-echarts) visualization library. :star:7346
- [pythreejs](https://github.com/jovyan/pythreejs) - Python / ThreeJS bridge utilizing the Jupyter widget infrastructure. :star:563
- [Qgrid](https://github.com/quantopian/qgrid) - Interactive grid for sorting, filtering, and editing DataFrames in Jupyter notebooks. :star:1990
- [tributary](https://github.com/timkpaine/tributary) - Python data streams with Jupyter support. :star:89
- [tqdm](https://github.com/tqdm/tqdm) - Fast, extensible progress bar for loops and iterables. :star:12307
- [xleaflet](https://github.com/QuantStack/xleaflet) - C++ Backend for ipyleaflet. :star:37
- [xwebrtc](https://github.com/QuantStack/xwebrtc) - C++ Backend for ipywebrtc. :star:14
- [xwidgets](https://github.com/QuantStack/xwidgets) - C++ Backend for ipywidgets. :star:78

## Rendering/Publishing/Conversion

- [Binder](http://mybinder.org) - Turn a GitHub repo into a collection of interactive notebooks.
- [Bookbook](https://github.com/takluyver/bookbook) - Bookbook converts a set of notebooks in a directory to HTML or PDF, preserving cross references within and between notebooks. :star:76
- [Jupytext](https://github.com/mwouts/jupytext) - Edit, refactor and version control Jupyter Notebooks represented as scripts or Markdown documents. :star:2940
- [nbconvert](https://nbconvert.readthedocs.io) - Convert Notebooks to other formats.
- [nbdime](https://github.com/jupyter/nbdime) - Tools for diffing and merging of Jupyter notebooks. :star:1438
- [nbinteract](https://www.nbinteract.com) - Create interactive webpages from Jupyter notebooks.
- [nbflow](https://github.com/jhamrick/nbflow) - One-button reproducible workflows with Jupyter and Scons. :star:143
- [nbscan](https://github.com/conery/nbscan) - Search for and print cells contents of Jupyter notebooks. :star:12
- [Nikola](https://getnikola.com) - Static Site Generator that converts notebooks into websites.
- [notedown](https://github.com/aaren/notedown/) - Convert Jupyter notebooks to markdown (and back). :star:663
- [Papermill](https://github.com/nteract/papermill) - Tool for parameterizing, executing, and analyzing Jupyter notebooks. :star:2650
- [pynb](https://github.com/minodes/pynb) - Jupyter Notebooks as plain Python code with embedded Markdown text. :star:208
- [RISE](https://github.com/damianavila/RISE) - Reveal.js Jupyter/IPython Slideshow. :star:2475
- [rst2ipynb](https://github.com/nthiery/rst-to-ipynb) - Convert standalone reStructuredText files to Jupyter notebook file. :star:8
- [Voila](https://github.com/QuantStack/voila) - Rendering of live Jupyter Notebooks with interactive widgets, allowing dashboarding based on Jupyter Notebooks :star:1332

## JupyterLab Extensions

- [celltags](https://github.com/jupyterlab/jupyterlab-celltags) - Extension to organise and execute notebooks using cell tags. :star:92
- [code_formatter](https://github.com/ryantam626/jupyterlab_code_formatter) - A universal code formatter. :star:200
- [drawio](https://github.com/QuantStack/jupyterlab-drawio) - Extension that displays drawio/mxgraph diagrams. :star:299
- [git](https://github.com/jupyterlab/jupyterlab-git) - Extension for git integration. :star:450
- [go-to-definition](https://github.com/krassowski/jupyterlab-go-to-definition) - Extension for navigating to the definition of a variable or function in JupyterLab. :star:105
- [google-drive](https://github.com/jupyterlab/jupyterlab-google-drive) - Extension for Google Drive integration. :star:273
- [jupyterlab_email](https://github.com/timkpaine/jupyterlab_email) - Email notebooks and their content from within JupyterLab. :star:32
- [jupyterlab-kyso](https://github.com/kyso-io/jupyterlab-extension) - Extension to publish notebooks to the [Kyso](https://kyso.io) platform from Jupyterlab. :star:4
- [latex](https://github.com/jupyterlab/jupyterlab-latex) - Extension for live editing of LaTeX documents. :star:253
- [nb_black](https://github.com/dnanhkhoa/nb_black) - Extension to keep Python code automatically formatted using [black](https://github.com/psf/black). :star:53
- [python-bytecode](https://github.com/jtpio/jupyterlab-python-bytecode) - Explore CPython Bytecode in JupyterLab. :star:50
- [quickopen](https://github.com/parente/jupyterlab-quickopen) - Quickly open a file in JupyterLab by typing part of its name. :star:45
- [sidecar](https://github.com/jupyter-widgets/jupyterlab-sidecar) - A sidecar output widget for JupyterLab. :star:90
- [sql](https://github.com/pbugnion/jupyterlab-sql) - SQL GUI for JupyterLab. :star:240
- [system-monitor](https://github.com/jtpio/jupyterlab-system-monitor) - Extension to display system metrics. :star:14
- [templates](https://github.com/timkpaine/jupyterlab_templates) - Support for Jupyter Notebook templates. :star:134
- [theme-darcula](https://github.com/telamonian/theme-darcula) - A handsome Darcula theme for Jupyterlab. :star:27
- [toc](https://github.com/jupyterlab/jupyterlab-toc) - Extension that provides a table of contents for notebooks. :star:404
- [topbar](https://github.com/jtpio/jupyterlab-topbar) - Top Bar extension for JupyterLab. :star:38
- [variableinspector](https://github.com/lckr/jupyterlab-variableInspector) - Variable inspector extension that shows variables and their values. :star:447
- [vim](https://github.com/jwkvam/jupyterlab-vim) - Vim notebook cell bindings. :star:549
- [voyager](https://github.com/altair-viz/jupyterlab_voyager) - Extension to view CSV and JSON data in [Voyager](http://vega.github.io/voyager/). :star:190

## Testing

- [ipytest](https://github.com/chmp/ipytest) - Test runner for running unit tests from within a notebook. :star:87
- [nbval](https://github.com/computationalmodelling/nbval) - Py.test plugin for validating Jupyter notebooks. :star:242
- [sphinxcontrib-jupyter](https://github.com/QuantEcon/sphinxcontrib-jupyter) - Sphinx Extension for Generating Jupyter Notebooks. :star:51
- [nosebook](https://github.com/bollwyvl/nosebook) - Nose plugin for finding and running IPython notebooks as nose tests. :star:76

## Domain-Specific Projects

- [ArcGIS](https://developers.arcgis.com/python/) - Library for working with maps and geospatial data, powered by web GIS.
- [GenePattern Notebook](http://genepattern-notebook.org) - Integrating Genomic Analysis with Interactive Notebooks.
- [GeoNotebook](https://github.com/OpenGeoscience/geonotebook) - Extension for exploratory geospatial analysis. :star:942
- [lolviz](https://github.com/parrt/lolviz) - Data-structure visualization tool for lists of lists, lists, dictionaries. :star:635
- [Quantopian Notebooks](https://www.quantopian.com/notebooks/survey) - Jupyter-based platform for financial research.
- [vpython-jupyter](https://github.com/BruceSherwood/vpython-jupyter) - VPython 3D engine running in a Jupyter notebook. :star:65

## Hosted Notebook Solutions

- [Anaconda Enterprise](https://www.anaconda.com/enterprise/) - Multi-user collaboration and one-click deployment of models, notebooks, and dashboards.
- [Azure Notebooks](https://notebooks.azure.com) - Jupyter notebooks running in the cloud on Microsoft Azure.
- [CoCalc](https://cocalc.com) - Notebooks with 17 supported kernel types, course management, LaTeX document authoring, simultaneous document editing and integration with the SageMath computer algebra system.
- [DataScience.com](https://www.datascience.com) - Platform for enterprise data science.
- [Deepnote](https://www.deepnote.com) - Jupyter-compatible data science notebook with real-time collaboration, versioning and easy deployment.
- [Domino Data Lab](https://www.dominodatalab.com) - Data science platform with integrated collaboration tools, environment management and compute grid.
- [Google Cloud Datalab](https://cloud.google.com/datalab/) - Notebook platform integrated with the Google Cloud stack.
- [Google Colaboratory](https://research.google.com/colaboratory/unregistered.html) - Cloud-based Jupyter environment aimed at machine learning education and research.
- [Gryd](https://gryd.us) - Simple, managed, ready-to-use, cloud based Jupyter notebooks supporting multiple languages.
- [Kyso](https://kyso.io) - Data science platform to publish and share Jupyter notebooks as data blogs and web applications.
- [PAWS](https://wikitech.wikimedia.org/wiki/PAWS) - Jupyter notebook deployment customized for interacting with Wikimedia wikis.
- [RMOTR Notebooks](https://notebooks.rmotr.com) - JupyterLab-based data science environment in the cloud.
- [Spell.run](https://spell.run) - End-to-end platform for machine learning and deep learning.

## Official Resources and Documentation

- [JupyterLab Documentation](http://jupyterlab.readthedocs.io/en/stable/index.html)
- [Jupyter kernels](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels) - List of all programming languages available as Jupyter kernels. :star:8904
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
- [Gallery of Jupyter notebooks I](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks) :star:8904
- [Gallery of Jupyter notebooks II](http://nb.bianp.net/sort/views/)
- [Install and run a Jupyter notebook in a Google Cloud Dataproc cluster](https://cloud.google.com/dataproc/docs/tutorials/jupyter-notebook)
- [Interactive Web Plotting with Bokeh](https://github.com/bokeh/bokeh-notebooks) :star:510
- [JupyterLab - Your Personal Data Science Workbench](https://github.com/markusschanta/talks/tree/master/2018-03%20-%20JupyterLab%20-%20Full%20Stack%20Quants) - Talk about JupyterLab at Full Stack Quants London. :star:13
- [Jupyter Notebook Extensions](http://jupyter-contrib-nbextensions.readthedocs.io)
- [Jupyter Notebook Themes](https://github.com/dunovank/jupyter-themes) :star:6485
- [Jupyter tips, tricks and shortcuts](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)
- [Lectures on scientific computing with Python](https://github.com/jrjohansson/scientific-python-lectures) :star:2655
- [The Littlest JupyterHub](https://the-littlest-jupyterhub.readthedocs.io/en/latest/) - JupyterHub distribution for 1-50 users on a single server; more lightweight than the Zero to JupyterHub setup.
- [pytudes](https://github.com/norvig/pytudes) - List of Jupyter Notebooks by Peter Norvig. :star:12680
- [ResGuides: research with Jupyter](https://www.gitbook.com/book/dansand/resguides-research-with-jupyter/details)
- [Zero to JupyterHub](http://zero-to-jupyterhub.readthedocs.io/en/latest/) - Tutorial to help install and manage JupyterHub.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/adebar/awesome-jupyter/blob/master/CONTRIBUTING.md) first.

