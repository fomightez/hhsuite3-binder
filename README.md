# hhsuite3-binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/hhsuite3-binder/main?filepath=index.ipynb)

*tl;dr:*  
Click any `launch binder` badge on this page to run command line-based HH-suite3 software inside your browser.

------

***HH-suite3 for fast remote homology detection and deep protein annotation demonstrated in your browser via Jupyter.***

This repository is for running HH-suite3 programs, such as hhblits and hhsearch, in Jupyter environment provided by [MyBinder.org](https://mybinder.org/).  
Additionally, having HH-suite3 working inside the Jupyter environment with interactive Python adds some convenient features that are illustrated. A utility script for moving command line-based HH-suite3 results files into Python is also demonstrated.  

-------

Software
--------

The [HH-suite3](https://github.com/soedinglab/hh-suite/wiki) software will be installed already in each active session launched from this repository. The HH-suite3 software is available directly from the authors [here](https://github.com/soedinglab/hh-suite).


The HH-suite3 software references are listed in full [here](https://github.com/soedinglab/hh-suite/wiki#user-guide) under 'References'.

Users of HH-suite3 here should probably cite:

- Steinegger M, Meier M, Mirdita M, Vöhringer H, Haunsberger S J, and Söding J (2019)
HH-suite3 for fast remote homology detection and deep protein annotation, *BMC Bioinformatics*, 473. [doi: 10.1186/s12859-019-3019-7](https://doi.org/10.1186/s12859-019-3019-7)


***Clarifying Software Attribution: I, Wayne, am not involved in the HH-suite3 software at all. Those in [the lab of Johannes Söding](https://www.mpibpc.mpg.de/soeding) are the developers and source of HH-suite3. See their materials. I simply set up this repository to make the software useable on the command line without installation headaches and in full-feature environment.***

I, Wayne Decatur, did code a Python-based utility for use with the results from command line HH-suite3 results files; it is available [here](https://github.com/fomightez/sequencework/tree/main/hhsuite3-utilities) and utilized in the notebooks in this repository to process the results and allow easily converting the results to other Python-friendly forms.

Usage
-----

This repository is set up to allow running the command line version of HH-suite3 software after pressing the `launch binder` button above or below. The target use case is when you want to learn about using HH-suite3, especially `hhblits`. Importantly, the resources needed for `hhblits` to make a good HHM for a sequence goes beyond what MyBinder provides. You'll need to find more computer resources and power to build on what you learn here. Instead if using a good representative of sequence space provided by the latest release of [the Uniclust30 database](https://uniclust.mmseqs.com/), we'll either use a smaller database as an example or bring in pre-made MSAs or HHMs. The Uniclust30 database (currently the `2020_06` version) is generously provided by the software authors via a webserver [here](https://toolkit.tuebingen.mpg.de/tools/hhblits) for making rich MSAs for a sequence.

In the notebooks that can be launched, I have added some examples illustrating how to use the program and process the results easily with Python and convert to other forms. **Additionally, useful resources for using command line HH-suite3 are in those notebooks.** Alternatively, the notebook with most of resources can be viewed statically [here?????](?????). The ['Credits/Resources'????? section right at the top](?????) is a good place to start.

**The Binder-luanchable version too limiting for your needs?**

The authors have made the software installable via conda, see [here](https://anaconda.org/bioconda/hhsuite).  If you need other installation options, such as configured for a cluster, other installation options are type is discussed [here](https://github.com/soedinglab/hh-suite/wiki#installation-of-the-hhsuite-and-its-databases).

Web-based automated searching for remote homologs via [HHpred](https://toolkit.tuebingen.mpg.de/tools/hhpred) is also available via [the MPI Bioinformatics Toolkit](https://toolkit.tuebingen.mpg.de/). 


Technical Details
-----------------

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.

I borrrowed the 'warning' highlight/introductory text about notebooks at the top of the included notebook from Tim Sherratt's notebook [here](https://github.com/GLAM-Workbench/te-papa-api/blob/main/Exploring-the-Te-Papa-collection-API.ipynb).

Click this button below to begin using HH-suite3 (or BLAST, as well):

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/hhsuite3-binder/main?filepath=index.ipynb)
