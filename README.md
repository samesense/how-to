# how-to
Pointers to code for performing common tasks

* [Pull base-wise signals from bigwig files](https://github.com/samesense/run-proseq/blob/master/src/rules/sf_desert.py#L46)
    * Deeptools does not perform base-wise stats. It gives you an average signal over a region, but there seems to be an error. I suspect that it re-normalizes the signal.
