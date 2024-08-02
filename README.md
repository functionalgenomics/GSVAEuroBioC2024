# Pathway-centric analyses of omics data with GSVA

# Quick-install

```
BiocManager::install(
    "functionalgenomics/GSVAEuroBioC2024", dependencies=TRUE, build_vignettes=TRUE
)
```

# Instructor names and contact information

[Axel Klenk](mailto:axel.klenk@upf.edu),
[Robert Castelo](mailto:robert.castelo@upf.edu)

Dept. of Medicine and Life Sciences

Universitat Pompeu Fabra

Barcelona

# Workshop description

This workshop demonstrates how to use GSVA to conduct pathway-centric analyses of
omics data.

**Keywords**: pathway analysis, transcriptomics, proteomics

## Pre-requisites

* Basic knowledge of R syntax.
* Familiarity with the `SummarizedExperiment` and the `SingleCellExperiment` classes.

## Time outline

40 minutes total

| Activity                             | Time |
|--------------------------------------|------|
| Import gene set annotations          |  5m  |
| Analysis of bulk RNA-seq data        | 15m  |
| Analysis of single-cell RNA-seq data | 10m  |
| Analysis of spatial RNA-seq data     | 10m  |

## Docker commands for this workshop

The Docker image for this workshop is available on the GitHub Container
Registry. Pull (download) the image with the following command:

```sh
docker pull ghcr.io/functionalgenomics/GSVAEuroBioC2024:latest
```

Run the workshop with Docker by using the following command:

```sh
docker run -e PASSWORD=bioc -p 8787:8787 ghcr.io/functionalgenomics/GSVAEuroBioC2024:latest
```

## Workshop goals and objectives

### Learning goals

* Import gene sets from GMT files.

* Obtain pathway enrichment scores using GSVA.

* Use the resulting pathway enrichment scores in a downstream analyses.

## Questions & Comments

For questions, comments, or bug reports, please use the
Bioconductor [support site](https://support.bioconductor.org/) or create an
issue on the `GSVA` Github [repo](https://github.com/rcastelo/GSVA/issues).
