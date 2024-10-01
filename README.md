# Beyond Human-Only: Evaluating Human-Machine Collaboration forCollecting High-Quality Translation Data

This repository contains the collaborative translation collection dataset, which accompanies the paper Beyond Human-Only: Evaluating Human-Machine Collaboration forCollecting High-Quality Translation Data.

## Overview
The data can be downloaded from this link. (To be released, Pending Approval).

The zip file contains the collaborative translation datasets, containing the data collected through 11 different approaches involving human translators and large language models (LLMs).

Each data point contains two parts:
* Translation text data in the form of (source, target) pairs 
* Additional MQM error annotations, which contain 10 fields from human annotation following MQM schema. Each pair of translations can have more than one error annotation.

The source sentences come from publicly available test set prepared by [Workshop on Machine Translation](https://www2.statmt.org/wmt23/)(WMT) and the translations were generated and processed from the following origins:
* Publicly available machine translation from WMT;
* Translated from scratch by professional translators;
* Post-edited by professional translators;
* Post-edited by Gemini-1.0 Ultra.

The error annotations are collected from human raters following the publicly-available [MQM schema and instructions](https://aclanthology.org/2021.tacl-1.87/). Each translation can be annotated with multiple errors and each error has error severity, category and error span annotated. 


## Citation
If you use the data from this work, please cite the following paper:

TODO: add arxiv link once uploaded.
