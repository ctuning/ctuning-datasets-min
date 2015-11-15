Minimal data sets used for autotuning and co-design in computer engineering
===========================================================================

Various public data sets for public bechmarks and kernels used
in our research on universal and multi-objective autotuning/crowd-tuning.
It is possible to reproduce and extend some techniques from our recent papers:

* http://arxiv.org/abs/1506.06256
* http://hal.inria.fr/hal-01054763
* https://hal.inria.fr/inria-00436029
* http://arxiv.org/abs/1407.4075

Our eventual goal is to gradually release all our artifacts (code and data)
to help community reproduce and extend this research.

Status
======
Stable reprository

Dependencies on other repositories
==================================
* ctuning-programs
* ck-autotuning
* ck-env

Authors
=======

* Grigori Fursin, cTuning foundation (France) / dividiti (UK)
* Various authors of shared programs (see individual entries)

Prerequisites
=============
* Collective Knowledge Framework: http://github.com/ctuning/ck

Installation
============

> ck pull repo:ctuning-datasets-min

List of other CK data set repositories shared as zip
====================================================

It is possible to share CK repositories as zip archives (useful to share artifacts along with publications and add them as supplementary material for ACM Digital Library, for example). Such repositories can be installed via

> ck add repo:[repo_name] --zip=[zip archive name or full URL] --quiet

We shared multiple repositories with thousands of data sets for our shared benchmarks via Google Drive:

* https://drive.google.com/folderview?id=0B-wXENVfIO82dzYwaUNIVElxaGc&usp=sharing 

For example, you can download ckr-ctuning-datasets.zip 
(or other and much larger datasets ckr-usb-ctuning-dataset-* from our PLDI paper).

Register it with CK simply via:

> ck add repo:ctuning-datasets --zip=ckr-ctuning-datasets.zip --quiet

Now, when you run shared cTuning benchmarks (programs), 
you will automatically have an extended choice of data sets.

If you want to compile and run our benchmarks on Android-based mobile phones,
you need to download and register with CK Android NDK as described here:
* https://github.com/ctuning/ck/wiki/Getting_started_guide_tools

List of other CK data set repositories shared via BitTorrent
============================================================

We share some large CK repositories in zip via BitTorrent to optimize sharing (upload and download) of such repositories across multiple users. We use the following file name convention for such repositories: ckr-<repo></repo>-YYYYMMDD.zip.

* ckr-32332f6412da1be1-20150803.zip (~287Mb) - Data sets (MiDatasets and cDatasets) from our past R&D to crowdsource autotuning and benchmarking (crowd-tuning and crowd-benchmarking). Get torrent here: https://github.com/ctuning/ck-guide-images/blob/master/ckr-32332f6412da1be1-20150804.zip.torrent?raw=true
