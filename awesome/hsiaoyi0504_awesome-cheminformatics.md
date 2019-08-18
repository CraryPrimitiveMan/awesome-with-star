# Information comes from [hsiaoyi0504/awesome-cheminformatics](https://github.com/hsiaoyi0504/awesome-cheminformatics)
# Awesome Cheminformatics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Cheminformatics (also known as chemoinformatics, chemioinformatics and chemical informatics) is the use of computer and informational techniques applied to a range of problems in the field of chemistry.— [Wikipedia](https://en.wikipedia.org/wiki/Cheminformatics)

A curated list of awesome Cheminformatics software, resources, and libraries. Mostly command line based, and free or open-source. Please feel free to [contribute](CONTRIBUTING.md) !

## Contents

* [Applications](#applications)
  * [Visualization](#app-visualization)
  * [Command Line Tools](#app-cmd)
  * [Docking](#app-docking)
* [Libraries](#libraries)
  * [General Purpose](#lib-general)
  * [Visualization](#lib-visualization)
  * [Command Line Tools](#lib-format)
  * [Molecular Descriptors](#lib-des)
  * [Machine Learning](#lib-ml)
  * [Web APIs](#lib-web)
  * [Databases](#lib-db)
  * [Molecular Dynamics](#lib-md)
* [Journals](#journals)
* [Resources](#resources)
  * [Courses](#courses)
  * [Blogs](#blogs)
  * [Books](#books)
* [See Also](#see-also)

## Applications

<a id="app-visualization"></a>
### Visualization

* [PyMOL](https://sourceforge.net/projects/pymol/) - Python-enhanced molecular graphics tool.
* [Jmol](http://jmol.sourceforge.net/) - Browser-based HTML5 viewer and stand-alone Java viewer for chemical structures in 3D.
* [VMD](http://www.ks.uiuc.edu/Research/vmd/) - Molecular visualization program for displaying, animating, and analyzing large biomolecular systems using 3-D graphics and built-in scripting.
* [Chimera](https://www.cgl.ucsf.edu/chimera/) - Highly extensible program for interactive molecular visualization and analysis.

<a id="app-cmd"></a>
### Command Line Tools

* [Open Babel](http://openbabel.org/wiki/Main_Page) - Chemical toolbox designed to speak the many languages of chemical data.
* [MayaChemTools](http://www.mayachemtools.org/index.html) - Collection of Perl and Python scripts, modules, and classes that support day-to-day computational discovery needs.
* [Packmol](http://m3g.iqm.unicamp.br/packmol/home.shtml) - Initial configurations for molecular dynamics simulations by packing optimization.

<a id="app-docking"></a>
### Docking

* [AutoDock Vina](http://vina.scripps.edu/) - Molecular docking and virtual screening.
* [smina](https://sourceforge.net/projects/smina/) - Customized [AutoDock Vina](http://vina.scripps.edu/) to better support scoring function development and high-performance energy minimization.

## Libraries

<a id="lib-general"></a>
### General Purpose

* [RDKit](http://www.rdkit.org/) - Collection of cheminformatics and machine-learning software written in C++ and Python.
* [Indigo](https://github.com/epam/Indigo) - Universal molecular toolkit that can be used for molecular fingerprinting, substructure search, and molecular visualization written in C++ package, with Java, C#, and Python wrappers. :star:78
* [CDK (Chemistry Development Kit)](https://sourceforge.net/projects/cdk/) - Algorithms for structural chemo- and bioinformatics, implemented in Java.
* [ChemmineR](https://www.bioconductor.org/packages/release/bioc/vignettes/ChemmineR/inst/doc/ChemmineR.html) - Cheminformatics package for analyzing drug-like small molecule data in R.

<a id="lib-format"></a>
### Format Checking

* [standardiser](https://wwwdev.ebi.ac.uk/chembl/extra/francis/standardiser/) - Tool designed to provide a simple way of standardising molecules as a prelude to e.g. molecular modelling exercises.
* [MolVS](https://github.com/mcs07/MolVS) - Molecule validation and standardization based on [RDKit](http://www.rdkit.org/). :star:46

<a id="lib-visualization"></a>
### Visulization

* [Kekule.js](http://partridgejiang.github.io/Kekule.js/) - Front-end JavaScript library for providing the ability to represent, draw, edit, compare and search molecule structures on web browsers.
* [JChemPaint](https://github.com/JChemPaint/jchempaint) - Chemical 2D structure editor application/applet based on the [Chemistry Development Kit](https://sourceforge.net/projects/cdk/). :star:54
* [rdeditor](https://github.com/EBjerrum/rdeditor) - Simple RDKit molecule editor GUI using PySide. :star:11

<a id="lib-des"></a>
### Molecular Descriptors

* [mordred](https://github.com/mordred-descriptor/mordred) - Molecular descriptor calculator based on [RDKit](http://www.rdkit.org/). :star:55
* [mol2vec](https://github.com/samoturk/mol2vec) - Vector representations of molecular substructures. :star:73
* [Align-it](http://silicos-it.be.s3-website-eu-west-1.amazonaws.com/software/align-it/1.0.4/align-it.html#alignit-generating-pharmacophore-points) - Align molecules according their pharmacophores.

<a id="lib-ml"></a>
### Machine Learning

* [DeepChem](https://github.com/deepchem/deepchem) - Democratizing deep learning for Chemistry. :star:1665
* [chainer-chemistry](https://github.com/pfnet-research/chainer-chemistry) - A Library for Deep Learning in Biology and Chemistry. :star:338

<a id="lib-web"></a>
### Web APIs

* [webchem](https://github.com/ropensci/webchem) - Chemical Information from the Web. :star:60
* [PubChemPy](http://pubchempy.readthedocs.io) - Python wrapper for the PubChem PUG REST API.
* [ChemSpiPy](http://chemspipy.readthedocs.org) - Python wrapper for the ChemSpider API.
* [CIRpy](http://cirpy.readthedocs.org/) - Python wrapper for the NCI Chemical Identifier Resolver (CIR).
* [Beaker](https://github.com/chembl/chembl_beaker) - [RDKit](http://www.rdkit.org/) and [OSRA](https://cactus.nci.nih.gov/osra/) in the [Bottle](http://bottlepy.org/docs/dev/) on [Tornado](http://www.tornadoweb.org/en/stable/). :star:17

<a id="lib-db"></a>
### Databases

* [razi](https://github.com/rvianello/razi) - Cheminformatic extension for the SQLAlchemy database. :star:15

<a id="lib-md"></a>
### Molecular Dynamics

* [Gromacs](http://www.gromacs.org/) - Molecular dynamics package mainly designed for simulations of proteins, lipids and nucleic acids.
* [OpenMM](http://openmm.org/) - High performance toolkit for molecular simulation including extensive language bindings for Python, C, C++, and even Fortran.
* [MDTraj](https://github.com/mdtraj/mdtraj) - Analysis of molecular dynamics trajectories. :star:239
* [cclib](https://github.com/cclib/cclib) - Parsers and algorithms for computational chemistry logfiles. :star:138

## Journals

* [Journal of Cheminformatics](https://jcheminf.biomedcentral.com/)
* [Journal of Chemical Information and Modeling (ACS Publications)](https://pubs.acs.org/journal/jcisd8)

## Resources

### Courses

* [Learncheminformatics.com](http://learncheminformatics.com/) - "Cheminformatics: Navigating the world of chemical data" courese at Indiana University.
* [cheminfoeducation](https://www.youtube.com/user/cheminfoeducation/videos) - A YouTube channel for cheminformatics education.

### Blogs

* [Open Source Molecular Modeling](https://opensourcemolecularmodeling.github.io/README.html) - Updateable catalog of open source molecular modeling software.
* [PubChem Blog](https://pubchemblog.ncbi.nlm.nih.gov/) - News, updates and tutorials about [PubChem](https://pubchem.ncbi.nlm.nih.gov/).
* [The ChEMBL-og blog](http://chembl.blogspot.tw/) - Stories and news from Computational Chemical Biology Group at [EMBL-EBI](https://www.ebi.ac.uk/).
* [ChEMBL blog](http://chembl.github.io/) - ChEMBL on GitHub.
* [SteinBlog](http://www.steinbeck-molecular.de/steinblog/) - Blog of [Christoph Steinbeck](http://www.steinbeck-molecular.de/steinblog/index.php/about/), who is the head of cheminformatics and metabolism at the EMBL-EBI.
* [Practical Cheminformatics](http://practicalcheminformatics.blogspot.com/) - Blog with in-depth examples of practical application of cheminformatics.
* [So much to do, so little time - Trying to squeeze sense out of chemical data](http://blog.rguha.net/) - Bolg of [Rajarshi Guha](http://blog.rguha.net/?page_id=8), who is a research scientist at NIH Center for Advancing Translational Science.
  * Some old blogs [1](https://rguha.wordpress.com/) [2](http://www.rguha.net/index.html).
* [Noel O'Blog](http://baoilleach.blogspot.tw/) - Blog of [Noel O'Boyle](https://www.redbrick.dcu.ie/~noel/), who is a Senior Software Engineer at NextMove Software.
* [chem-bla-ics](http://chem-bla-ics.blogspot.tw/) - Blog of [Egon Willighagen](http://egonw.github.io/), who is an assistant professor at Maastricht University.
* [Asad's Blog](https://chembioinfo.com/) - Bolg of Syed Asad Rahman, who is a research scientist in the [Thornton group](http://www.ebi.ac.uk/research/thornton) at EMBL-EBI.
* [steeveslab-blog](http://asteeves.github.io/) - Some examples using [RDKit](http://www.rdkit.org/).
* [Macs in Chemistry](http://www.macinchem.org/) - Provide a resource for chemists using Apple Macintosh computers.

### Books

* [Computational Approaches in Cheminformatics and Bioinformatics](https://books.google.com/books/about/Computational_Approaches_in_Cheminformat.html?id=bLqV4rYQoYsC) -  Include insights from public (NIH), academic, and industrial sources at the same time.
* [Chemoinformatics for Drug Discovery](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118742785) - Materials about how to use Chemoinformatics strategies to improve drug discovery results.

<a id="see-also"></a>
## See Also

* [deeplearning-biology](https://github.com/hussius/deeplearning-biology#chemoinformatics-and-drug-discovery-) - Chemoinformatics and drug discovery section in deeplearning-biology repo. :star:1090
* [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry) - Another list focuses on Python stuff related to Chemistry. :star:188

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

