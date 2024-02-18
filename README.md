# RNA-Seq De novo Assembly Using Trinity

image

## Quick Guide for the Impatient
Trinity assembles transcript sequences from Illumina RNA-Seq data.

Download Trinity [here](https://github.com/trinityrnaseq/trinityrnaseq/releases).

Build Trinity by typing 'make' in the base installation directory.

Assemble RNA-Seq data like so:

```
 Trinity --seqType fq --left reads_1.fq --right reads_2.fq --CPU 6 --max_memory 20G 
```
