About python-json-logger
========================

Home: http://github.com/madzak/python-json-logger

Package license: BSD 2-clause

Feedstock license: BSD 3-Clause

Summary: A python library adding a json log formatter

This library is provided to allow standard python logging to output log
data as json objects. With JSON we can make our logs more readable by
machines and we can stop writing custom parsers for syslog type records.


Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/conda-forge/python-json-logger-feedstock.svg?style=shield)](https://circleci.com/gh/conda-forge/python-json-logger-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/python-json-logger-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/python-json-logger-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/python-json-logger-feedstock?svg=True)](https://ci.appveyor.com/project/conda-forge/python-json-logger-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/nomr/python-json-logger/badges/version.svg)](https://anaconda.org/nomr/python-json-logger)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/nomr/python-json-logger/badges/downloads.svg)](https://anaconda.org/nomr/python-json-logger)

Installing python-json-logger
=============================

Installing `python-json-logger` from the `nomr` channel can be achieved by adding `nomr` to your channels with:

```
conda config --add channels nomr
```

Once the `nomr` channel has been enabled, `python-json-logger` can be installed with:

```
conda install python-json-logger
```

It is possible to list all of the versions of `python-json-logger` available on your platform with:

```
conda search python-json-logger --channel nomr
```




Updating python-json-logger-feedstock
=====================================

If you would like to improve the python-json-logger recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nomr` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nomr` channel.
Note that all branches in the conda-forge/python-json-logger-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
