# Note

This repository is a fork of version 1.1.15 of SECAPR, in which issues #16 and #17 are solved. 
To install this version, follow instructions to [install SECAPR development version](https://htmlpreview.github.io/?https://github.com/AntonelliLab/seqcap_processor/blob/master/docs/documentation/main_doc.html#5.-Install-SECAPR-development-version): first install secapr from Anaconda to obtain dependencies and then update SECAPR only. This can be done with the following commands:

```
conda create -n secapr_env secapr=1.1.15 pip
conda activate secapr_env 
wget https://github.com/brunoasm/seqcap_processor/archive/v.1.1.15-beta.0.zip
unzip v.1.1.15-beta.0.zip
cd seqcap_processor-v.1.1.15-beta.0/
python -m pip install -e .
```

# <img src="images/secapr_logo.png" width="100"> SEquence CApture PRocessor (SECAPR)

**Original Publication: https://doi.org/10.7717/peerj.5175**

___

*We are now teaching a **free 1-week intensive course** on target enrichment data, including practical exercises for all functionalities of the SECAPR pipeline. Check it out and apply!*

http://www.forbio.uio.no/events/courses/2018/target_capture.html

___

## Installation instructions and documentation [click here](./documentation.ipynb)

[![downloads](https://anaconda.org/bioconda/secapr/badges/downloads.svg)](http://bioconda.github.io/recipes/secapr/README.html)


This semi-automated pipeline aims to make the processing and analysis of sequence capture (= target enrichment) data simple and straight forward for all users. The detailed documentation and simple installation makes this pipeline accessible also for users with limited biofinformatic knowledge, while enabling user-defined processing options for the more experienced users.

We included an empirical data tutorial in the [pipeline documentation](./documentation.ipynb), which covers the processing from raw Illumina read data into multiple seqeunce alignments (MSAs) for phylogenetic analyses, including the compiling of allele sequence MSAs. This workflow can be applied to any Illumina dataset, independently of the underlying bait set and organism group.

Some functions in this pipeline are inspired by the scripts from the [Phyluce pipeline](https://github.com/faircloth-lab/phyluce) by Braint Faircloth, which is aimed at the processing of Ultraconserved Elements (UCEs). To honour some of the ingenious ideas belonging to Brant Faircloth, and the generous sharing of all is code as open-source, we ask you to **cite the Phyluce pipeline** (Faircloth 2015) alongside with ours (Andermann et al. 2018), when using SECAPR.  

#### Please cite:

**Andermann T.**, Cano Á., Zizka A., Bacon C., Antonelli A. 2018. SECAPR — A bioinformatics pipeline for the rapid and user-friendly processing of targeted enriched Illumina sequences, from raw reads to alignments. PeerJ 6:e5175. DOI: 10.7717/peerj.5175.

Faircloth BC. 2015. PHYLUCE is a software package for the analysis of conserved genomic loci. bioRxiv. doi: 10.1101/027904.
