Singularity related files for SET
-------------------------------------------

The image for singularity can be built using `set.def` with the command:
`sudo singularity build image_name.img set.def`.

It can be used to run the Set-NF pipeline with the option
`-with-singularity image_name.img` of Nextflow.

To build the singularity, you have to copy your FreeSurfer `license.txt` to the directory.
Run the command from the directory `set-singularity`.

If you use this singularity, please cite:

```
Kurtzer GM, Sochat V, Bauer MW (2017)
Singularity: Scientific containers for mobility of compute.
PLoS ONE 12(5): e0177459. https://doi.org/10.1371/journal.pone.0177459
```
