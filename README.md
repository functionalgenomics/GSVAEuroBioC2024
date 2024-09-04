# Pathway-centric analyses of omics data with GSVA <img align="right" src="https://raw.githubusercontent.com/functionalgenomics/GSVAEuroBioC2024/master/images/CZI.png" height="100"/> <img align="right" src="https://raw.githubusercontent.com/functionalgenomics/GSVAEuroBioC2024/master/images/GSVA.png" height="100"/>

## Quick-install

```
BiocManager::install(
    "functionalgenomics/GSVAEuroBioC2024", dependencies=TRUE, build_vignettes=TRUE
)
```

## Instructor names and contact information

[Axel Klenk](mailto:axelvolker.klenk@upf.edu),
[Robert Castelo](mailto:robert.castelo@upf.edu)

Dept. of Medicine and Life Sciences

Universitat Pompeu Fabra

Barcelona

## Workshop description

This workshop demonstrates how to use GSVA to conduct pathway-centric analyses of
omics data. It uses the current development version of GSVA available at the time
of EuroBioC2024, which contains a number of new features that will become part of
the next version of GSVA 2.0 in the next release of Bioconductor on October 2024.
Some of the features illustrated in this workshop may change until GSVA 2.0 is
released, and others that are currently missing may still become part of that
version.

**Keywords**: pathway analysis, transcriptomics, proteomics

## Pre-requisites

* Basic knowledge of R syntax.
* Familiarity with the `SummarizedExperiment` and the `SingleCellExperiment` classes.

## Time outline

40 minutes total

| Activity                             | Time |
|--------------------------------------|------|
| Import gene set annotations          | 10m  |
| Analysis of bulk RNA-seq data        | 15m  |
| Analysis of single-cell RNA-seq data | 15m  |

## Docker commands for this workshop

The Docker image for this workshop is available on the GitHub Container
Registry. Pull (download) the image with the following command:

```sh
docker pull ghcr.io/functionalgenomics/gsvaeurobioc2024:latest
```
Run the workshop with Docker by first using the following command:

```sh
docker run -d -e PASSWORD=bioc -p 8787:8787 ghcr.io/functionalgenomics/gsvaeurobioc2024:latest
```
Second, open the url [localhost:8787](localhost:8787) in a new tab of
your web browser.

## Workshop goals and objectives

### Learning goals

* Import gene sets from GMT files.

* Obtain pathway enrichment scores using GSVA.

* Use the resulting pathway enrichment scores in downstream analyses.

## Questions & Comments

For questions, comments, or bug reports, please use the
Bioconductor [support site](https://support.bioconductor.org/) or create an
issue on the `GSVA` Github [repo](https://github.com/rcastelo/GSVA/issues).
