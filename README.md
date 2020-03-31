## Introduction

## Pipeline summary

1. Raw read QC
2. Adapter trimming
3. Mapping
4. Variant calling
5. QC

## Quick start

i. Install [`nextflow`](https://nf-co.re/usage/installation)

ii. Install one of [`docker`](https://docs.docker.com/engine/installation/), [`singularity`](https://www.sylabs.io/guides/3.0/user-guide/) or [`conda`](https://conda.io/miniconda.html)

iii. Download the pipeline and test it on a minimal dataset with a single command

```bash
nextflow run mpcrseq/mpcrseq-eval -profile test,<docker/singularity/conda/institute>
```


## Documentation