# Staphylococcus aureus enterotoxin database

This is a custom database for abricate to identify enterotoxin genes in S. aureus.

## Installation

If abricate was installed in conda environment name as `abricate`, you can install like this:

```bash
$ git clone https://github.com/enterotoxin
$ cd enterotoxin
$ conda activate abricate
(abricate)$ cp -R enterotoxin $CONDA_PREFIX/db/
(abricate)$ abricate --setupdb
```

## Usage

scanning genomes

```bash
$ abricate --db enterotoxin genomes.fasta
```
