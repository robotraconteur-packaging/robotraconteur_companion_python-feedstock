About robotraconteur_companion_python-feedstock
===============================================

Feedstock license: [BSD-3-Clause](https://github.com/robotraconteur/robotraconteur_companion_python-feedstock/blob/main/LICENSE.txt)

Home: http://robotraconteur.com

Package license: Apache-2.0

Summary: Companion library for the Robot Raconteur core library

Current build status
====================


<table><tr>
    <td>All platforms:</td>
    <td>
      <img src="https://img.shields.io/badge/noarch-disabled-lightgrey.svg" alt="noarch disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-robotraconteur_companion_python-green.svg)](https://anaconda.org/r/robotraconteur_companion_python) | [![Conda Downloads](https://img.shields.io/conda/dn/r/robotraconteur_companion_python.svg)](https://anaconda.org/r/robotraconteur_companion_python) | [![Conda Version](https://img.shields.io/conda/vn/r/robotraconteur_companion_python.svg)](https://anaconda.org/r/robotraconteur_companion_python) | [![Conda Platforms](https://img.shields.io/conda/pn/r/robotraconteur_companion_python.svg)](https://anaconda.org/r/robotraconteur_companion_python) |

Installing robotraconteur_companion_python
==========================================

Installing `robotraconteur_companion_python` from the `r` channel can be achieved by adding `r` to your channels with:

```
conda config --add channels r
conda config --set channel_priority strict
```

Once the `r` channel has been enabled, `robotraconteur_companion_python` can be installed with `conda`:

```
conda install robotraconteur_companion_python
```

or with `mamba`:

```
mamba install robotraconteur_companion_python
```

It is possible to list all of the versions of `robotraconteur_companion_python` available on your platform with `conda`:

```
conda search robotraconteur_companion_python --channel r
```

or with `mamba`:

```
mamba search robotraconteur_companion_python --channel r
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search robotraconteur_companion_python --channel r

# List packages depending on `robotraconteur_companion_python`:
mamba repoquery whoneeds robotraconteur_companion_python --channel r

# List dependencies of `robotraconteur_companion_python`:
mamba repoquery depends robotraconteur_companion_python --channel r
```




Updating robotraconteur_companion_python-feedstock
==================================================

If you would like to improve the robotraconteur_companion_python recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`r` channel, whereupon the built conda packages will be available for
everybody to install and use from the `r` channel.
Note that all branches in the robotraconteur/robotraconteur_companion_python-feedstock are
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

* [@johnwason](https://github.com/johnwason/)

