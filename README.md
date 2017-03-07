Open data sets with JSON meta for collaborative and reproducible computer systems' research
===========================================================================================

These are various public data sets for public bechmarks and kernels used
in our research on universal and multi-objective autotuning/crowd-tuning
in the [open Collective Knowledge format](http://cKnowledge.org):

* http://arxiv.org/abs/1506.06256
* http://hal.inria.fr/hal-01054763
* https://hal.inria.fr/inria-00436029
* http://arxiv.org/abs/1407.4075

They can be easily plugged in to various CK research workflows
(such as collaborative benchmarking and optimization of computer systems).

They also help with our [artifact evaluation initiative](http://cTuning.org/ae) 
at various computer systems conferences and journals.

Status
======
Stable reprository

Dependencies on other repositories
==================================
* [ctuning-programs](https://github.com/ctuning/ctuning-programs)
* [ck-autotuning](https://github.com/ctuning/ck-autotuning)
* [ck-env](https://github.com/ctuning/ck-env)

Authors
=======

* [Grigori Fursin](http://fursin.net/research.html), dividiti/cTuning foundation
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

Publications
============

```
@inproceedings{ck-date16,
    title = {{Collective Knowledge}: towards {R\&D} sustainability},
    author = {Fursin, Grigori and Lokhmotov, Anton and Plowman, Ed},
    booktitle = {Proceedings of the Conference on Design, Automation and Test in Europe (DATE'16)},
    year = {2016},
    month = {March},
    url = {https://www.researchgate.net/publication/304010295_Collective_Knowledge_Towards_RD_Sustainability}
}

@inproceedings{Fur2009,
  author =    {Grigori Fursin},
  title =     {{Collective Tuning Initiative}: automating and accelerating development and optimization of computing systems},
  booktitle = {Proceedings of the GCC Developers' Summit},
  year =      {2009},
  month =     {June},
  location =  {Montreal, Canada},
  keys =      {http://www.gccsummit.org/2009}
  url  =      {https://scholar.google.com/citations?view_op=view_citation&hl=en&user=IwcnpkwAAAAJ&cstart=20&citation_for_view=IwcnpkwAAAAJ:8k81kl-MbHgC}
}
```

* http://arxiv.org/abs/1506.06256
* http://hal.inria.fr/hal-01054763
* https://hal.inria.fr/inria-00436029
* http://arxiv.org/abs/1407.4075
* https://scholar.google.com/citations?view_op=view_citation&hl=en&user=IwcnpkwAAAAJ&citation_for_view=IwcnpkwAAAAJ:LkGwnXOMwfcC

Feedback
========

If you have problems, questions or suggestions, do not hesitate to get in touch
via the following mailing lists:
* https://groups.google.com/forum/#!forum/collective-knowledge
* https://groups.google.com/forum/#!forum/ctuning-discussions

![logo](https://github.com/ctuning/ck-guide-images/blob/master/logo-validated-by-the-community-simple.png)
