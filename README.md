# how-to
Pointers to code for performing common tasks (also see [TIL](https://github.com/samesense/TIL/)).

* [Start a new project](https://github.com/samesense/cookiecutter-data-science)

* [Run Snakemake on respublica](https://github.com/samesense/run-proseq/blob/master/src/rules/run_respublica.sh)
    * [Example config file](https://github.com/samesense/run-proseq/blob/master/configs/cluster.yaml)

* [Pull base-wise signals from bigwig files](https://github.com/samesense/run-proseq/blob/master/src/rules/sf_desert.py#L46)
    * Deeptools does not perform base-wise stats. It gives you an average signal over a region, but there seems to be an error. I suspect that it re-normalizes the signal.
    
* [Map ProSeq reads w/ novoalign](https://github.com/samesense/run-proseq/blob/master/src/rules/sf_novo_test.py)
    * Paired end fqs -> bam file with only read one
