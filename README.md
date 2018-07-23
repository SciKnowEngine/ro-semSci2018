# Towards Evidence Extraction: Analysis of Scientific Figures from Studies of Molecular Interactions

This repository describes a [Research Object](http://www.researchobject.org/) for the data and analysis reported in the paper:

> Burns, et al (2018) "Towards Evidence Extraction: Analysis of Scientific Figures from Studies of Molecular Interactions" [SemSci Workshop 2018](https://semsci.github.io/SemSci2018/). 

The [manifest.ttl](manifest.ttl) file provides linked data for the resources (software and data) used in the data processing that generated this paper. This involves links to three datasets hosted on Zenodo and three software tools hosted on Github. None of these resources are currently linked data / research objects, but we will seek to incorporate more detailed semantic representations of these elements going forward.

## Software

* [<https://github.com/SciKnowEngine/evidX/releases/tag/v0.1.0>](https://github.com/SciKnowEngine/evidX/releases/tag/v0.1.0) - Simple TensorFlow Classifiers used to classify text of subfigure captions by method type.
  * Implementation of Tensorflow classifiers used to classify subcaption text for molecular interaction experiments based on method types. 
* [<https://github.com/SciKnowEngine/UimaBioC>](https://github.com/SciKnowEngine/UimaBioC) - Text preprocessing pipelines
  * Text preprocessing pipelines used to generate word embedding text. 
* [<https://github.com/SciKnowEngine/lapdftext>](https://github.com/SciKnowEngine/lapdftext) - PDF image and text extraction tools
  * Image preprocessing pipelines used to extract whole figures from the pages of PDF files. 

# Data

* [<https://doi.org/10.5281/zenodo.1315036>](https://doi.org/10.5281/zenodo.1315036) - 'Molecular Biology Open Access Pubmed Word and Sentence Representations'
  * Word Embeddings for neural net classifiers extracted from PMC open access papers. 
* [<https://doi.org/10.5281/zenodo.13150211>](https://doi.org/10.5281/zenodo.13150211) - 'Method Classification of Open Access INTACT Molecular Interaction data.'
  * Training / Testign data for the caption classification task. 
* [<https://doi.org/10.5281/zenodo.1319051>](https://doi.org/10.5281/zenodo.1319051) - 'Partitioned Image Data for Machine Learning Analysis of Molecular Biology Figures'
  * Scientific figure image data used for classification experiments. 
