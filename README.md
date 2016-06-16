# Parallel SMATCH

Based on updated version of SMATCH ([http://amr.isi.edu/](http://amr.isi.edu/)) from [here](http://alt.qcri.org/semeval2016/task8/index.php?id=data-and-tools)

Made compatible with latest Python: now runs on Python 2.7+ including Python 3.3+ (possibly runs on Python 2.6 and Python 3.0-3.2).

Scoring is now run in N parallel processes which enables to score large files faster on multi-core systems.

Paralellization can be controlled with ```-p N``` command line option, where N is the number of processes. By default it will use all available cores, setting it to zero disables parallelization.

For more information on SMATCH tool look in README.txt file.