# Concordance

Visualize concordance and other quality metrics between variant callers.

Usage:

    concordance_counter.py [-h] [-o output] sample-name truth.vcf
                           vcfname=file.vcf [vcfname=file.vcf ...]

    open concordance.html

## Setting up

We use [virtualenv](https://pypi.python.org/pypi/virtualenv) for dependency management.

To get started, run:

    virtualenv env                   # make a new virtualenv named 'env'.
    source env/bin/activate          # activate the env (local pip, python).
    pip install -r requirements.txt  # install the requirements in the env.

## Examples


![](http://link.isaachodes.io/image/3v362B0g1t3B/Screen%20Shot%202014-05-22%20at%204.57.29%20PM.png)

Visualizing calls made against read depth and frequency of variant allele, for all callers.

![](http://link.isaachodes.io/image/003d052e053b/Screen%20Shot%202014-05-22%20at%204.58.00%20PM.png)

Visualizing concordance across variant callers.

![](http://link.isaachodes.io/image/383244063D1q/Screen%20Shot%202014-05-22%20at%204.59.16%20PM.png)

Visualizing scoring data across variant callers.
