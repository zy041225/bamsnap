# BamSnap

**This is a modified version of Bamsnap which can support long read mapping alignment visualization.**
<!--[![Build Status](https://travis-ci.org/bamsnap/bamsnap.svg?branch=develop)](https://travis-ci.org/bamsnap/bamsnap) 
[![Code Health](https://landscape.io/github/bamsnap/bamsnap/develop/landscape.svg?style=flat)](https://landscape.io/github/bamsnap/bamsnap/develop) 
[![Coverage Status](https://img.shields.io/codecov/c/github/bamsnap/bamsnap/develop.svg)](https://codecov.io/github/bamsnap/bamsnap?branch=develop)-->

BamSnap: a lightweight command-based visualization tool for sequencing reads in BAM files

<!--<img src="https://raw.githubusercontent.com/parklab/bamsnap/master/data/ex1/snapfiles/snap_test11.bam_1_715347-715348.png" height=128px width=405px>-->

For more details, see BamSnap [**Documentation**](http://bamsnap.readthedocs.io/en/latest).

[<img src="https://img.shields.io/pypi/v/bamsnap.svg">](https://pypi.org/project/bamsnap/)
[<img src="https://img.shields.io/pypi/dm/bamsnap.svg">](https://pypi.org/project/bamsnap/)
[<img src="https://readthedocs.org/projects/bamsnap/badge/?version=latest">](https://bamsnap.readthedocs.io/)
[<img src="https://img.shields.io/docker/pulls/danielmsk/bamsnap.svg">](https://hub.docker.com/r/danielmsk/bamsnap)

## Installation

### Prerequisites
* python 3.4+
* [Pillow (Python Imaging Library)](https://pypi.org/project/Pillow/), pillow==9.0 recommended 
* [pysam](https://pypi.org/project/pysam/)
* [pyfaidx](https://pypi.org/project/pyfaidx/)
* [pytabix](https://pypi.org/project/pytabix/)


### Install with github

```
git clone https://github.com/zy041225/bamsnap
cd bamsnap
pip install pillow==9.0
python setup.py install
```

## Usage

### Simple usage
```bash
$ bamsnap -bam test.bam -pos 1:7364529 -out test.png
```

For more details, see BamSnap [**Documentation**](http://bamsnap.readthedocs.io/en/latest).


## Example Use Case

* [**1000 Genome Data**](https://bamsnap-1kg.s3.amazonaws.com/index.html): 1000 genomic loci in 2504 individuals
* [**BamSnap Plot Gallery**](https://bamsnap.readthedocs.io/en/latest/gallery.html)





