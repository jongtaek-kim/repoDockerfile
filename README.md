# repoDockerfile
Modification of Sarek github repository Docker containers for use in the [UFRC HPC/HiPerGator](https://www.rc.ufl.edu/about/).

These docker contatiners are available [here](https://hub.docker.com/u/jongtaek/).



# [![Sarek](https://raw.githubusercontent.com/SciLifeLab/Sarek/master/docs/images/Sarek_logo.png "Sarek")](http://sarek.scilifelab.se/)

#### An open-source analysis pipeline to detect germline or somatic variants from whole genome or targeted sequencing

## Introduction

<img align="right" title="CAW" src="https://raw.githubusercontent.com/SciLifeLab/Sarek/master/docs/images/CAW_logo.png">

Previously known as the Cancer Analysis Workflow (CAW),
Sarek is a workflow designed to run analyses on WGS data from regular samples or tumour / normal pairs, including relapse samples if required.

It's built using [Nextflow][nextflow-link], a domain specific language for workflow building.
Software dependencies are handled using [Docker](https://www.docker.com) or [Singularity](https://www.sylabs.io/singularity/) - container technologies that provide excellent reproducibility and ease of use.
Singularity has been designed specifically for high-performance computing environments.
This means that although Sarek has been primarily designed for use with the Swedish [UPPMAX HPC systems](https://www.uppmax.uu.se), it should be able to run on any system that supports these two tools.

Sarek was developed at the [National Genomics Infastructure][ngi-link] and [National Bioinformatics Infastructure Sweden][nbis-link] which are both platforms at [SciLifeLab][scilifelab-link].
It is listed on the [Elixir - Tools and Data Services Registry](https://bio.tools/Sarek).
