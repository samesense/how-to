# how-to
Pointers to code for performing common tasks

* [Run Snakemake on respublica](https://github.com/samesense/run-proseq/blob/master/src/rules/run_respublica.sh)
    * [Example Config file](https://github.com/samesense/run-proseq/blob/master/configs/cluster.yaml)

* [Pull base-wise signals from bigwig files](https://github.com/samesense/run-proseq/blob/master/src/rules/sf_desert.py#L46)
    * Deeptools does not perform base-wise stats. It gives you an average signal over a region, but there seems to be an error. I suspect that it re-normalizes the signal.
    
* [Map ProSeq reads w/ novoalign](https://github.com/samesense/run-proseq/blob/master/src/rules/sf_novo_test.py)
    * Fq -> bam file with only read one
