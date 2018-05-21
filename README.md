# how-to
Pointers to code for performing common tasks (also see [TIL](https://github.com/samesense/TIL/)).

* General
    * [Start a new project](https://github.com/samesense/cookiecutter-data-science)
    * [Run Snakemake on respublica](https://github.com/samesense/run-proseq/blob/master/src/rules/run_respublica.sh)
        * [Example config file](https://github.com/samesense/run-proseq/blob/master/configs/cluster.yaml)

* ChipSeq and ProSeq
    * [Pull base-wise signals from bigwig files](https://github.com/samesense/run-proseq/blob/master/src/rules/sf_desert.py#L46)
        * Deeptools does not perform base-wise stats. It gives you an average signal over a region, but there seems to be an error. I suspect that it re-normalizes the signal.
    * [Map ProSeq reads w/ novoalign](https://github.com/samesense/run-proseq/blob/master/src/rules/sf_novo_test.py)
        * Paired end fqs -> bam file with only read one
    * [Locate transcriptionally active elements w/ dreg-hd](https://github.com/samesense/proseq_pipeline/blob/35a602c099cc105da4bc2b0bb2d0d0a06266c7ef/code/rules/sf_dreg_hd.py)
        * [Requires dreg docker container](https://hub.docker.com/r/samesense/danko_reg/)

* Plotting
    * [ggplot2](plots/ggplot2.md)
    * [Seaborn](plots/seaborn.md)
