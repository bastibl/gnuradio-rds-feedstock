About gnuradio-rds
==================

Home: https://github.com/bastibl/gr-rds

Package license: GPL-3.0

Feedstock license: [BSD-3-Clause](https://github.com/bastibl/gnuradio-rds-feedstock/blob/master/LICENSE.txt)

Summary: GNU Radio RDS Conda package.

Development: https://github.com/bastibl/gr-rds

Documentation: https://github.com/bastibl/gr-rds

FM RDS/TMC Transceiver


Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gnuradio--rds-green.svg)](https://anaconda.org/YOUR_ANACONDA_CHANNEL/gnuradio-rds) | [![Conda Downloads](https://img.shields.io/conda/dn/YOUR_ANACONDA_CHANNEL/gnuradio-rds.svg)](https://anaconda.org/YOUR_ANACONDA_CHANNEL/gnuradio-rds) | [![Conda Version](https://img.shields.io/conda/vn/YOUR_ANACONDA_CHANNEL/gnuradio-rds.svg)](https://anaconda.org/YOUR_ANACONDA_CHANNEL/gnuradio-rds) | [![Conda Platforms](https://img.shields.io/conda/pn/YOUR_ANACONDA_CHANNEL/gnuradio-rds.svg)](https://anaconda.org/YOUR_ANACONDA_CHANNEL/gnuradio-rds) |

Installing gnuradio-rds
=======================

Installing `gnuradio-rds` from the `YOUR_ANACONDA_CHANNEL` channel can be achieved by adding `YOUR_ANACONDA_CHANNEL` to your channels with:

```
conda config --add channels YOUR_ANACONDA_CHANNEL
conda config --set channel_priority strict
```

Once the `YOUR_ANACONDA_CHANNEL` channel has been enabled, `gnuradio-rds` can be installed with:

```
conda install gnuradio-rds
```

It is possible to list all of the versions of `gnuradio-rds` available on your platform with:

```
conda search gnuradio-rds --channel YOUR_ANACONDA_CHANNEL
```




Updating gnuradio-rds-feedstock
===============================

If you would like to improve the gnuradio-rds recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`YOUR_ANACONDA_CHANNEL` channel, whereupon the built conda packages will be available for
everybody to install and use from the `YOUR_ANACONDA_CHANNEL` channel.
Note that all branches in the bastibl/gnuradio-rds-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@bastibl](https://github.com/bastibl/)
* [@ryanvolz](https://github.com/ryanvolz/)

