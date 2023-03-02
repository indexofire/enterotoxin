# Staphylococcus aureus enterotoxin database

This is a custom database for abricate to identify enterotoxin genes in S. aureus.

## Installation

use this in a conda environment for abricate

```
$ cp -R enterotoxin $CONDA_PREFIX/db/
$ abricate --setupdb
```

## Usage

scanning genomes

```
$ abricate --db enterotoxin genomes.fasta
```
