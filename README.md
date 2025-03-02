About r-zigg-feedstock
======================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-zigg-feedstock/blob/main/LICENSE.txt)


About r-zigg
------------

Home: https://github.com/eddelbuettel/zigg

Package license: GPL-2.0-or-later

Summary: The 'Ziggurat' pseudo-random number generator (or PRNG), introduced by Marsaglia and Tsang (2000, <doi:10.18637/jss.v005.i08>) and further improved by Leong et al (2005, <doi:10.18637/jss.v012.i07>), offers a lightweight and very fast PRNG for the normal, exponential, and uniform distributions. It is provided here in a small zero-dependency package. It can be used from R as well as from 'C/C++' code in other packages as is demonstrated by four included sample packages using four distinct methods to use the PRNG presented here in client package. The implementation is influenced by our package 'RcppZiggurat' which offers a comparison among multiple alternative implementations but presented here in a lighter-weight implementation that is easier to use by other packages. The PRNGs provided are generally faster than the ones in base R: on our machine, the relative gains for normal, exponential and uniform are on the order of 7.4, 5.2 and 4.7 times faster than base R. However, these generators are of potentially lesser quality and shorter period so if in doubt use of the base R functions remains the general recommendation.

About r-zigg
------------

Home: https://github.com/eddelbuettel/zigg

Package license: GPL-2.0-or-later

Summary: The 'Ziggurat' pseudo-random number generator (or PRNG), introduced by Marsaglia and Tsang (2000, <doi:10.18637/jss.v005.i08>) and further improved by Leong et al (2005, <doi:10.18637/jss.v012.i07>), offers a lightweight and very fast PRNG for the normal, exponential, and uniform distributions. It is provided here in a small zero-dependency package. It can be used from R as well as from 'C/C++' code in other packages as is demonstrated by four included sample packages using four distinct methods to use the PRNG presented here in client package. The implementation is influenced by our package 'RcppZiggurat' which offers a comparison among multiple alternative implementations but presented here in a lighter-weight implementation that is easier to use by other packages. The PRNGs provided are generally faster than the ones in base R: on our machine, the relative gains for normal, exponential and uniform are on the order of 7.4, 5.2 and 4.7 times faster than base R. However, these generators are of potentially lesser quality and shorter period so if in doubt use of the base R functions remains the general recommendation.

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=24978&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-zigg-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_r_base4.3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=24978&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-zigg-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.3" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=24978&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-zigg-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=24978&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-zigg-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_r_base4.3" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=24978&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-zigg-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=24978&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-zigg-feedstock?branchName=main&jobName=win&configuration=win%20win_64_r_base4.3" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=24978&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-zigg-feedstock?branchName=main&jobName=win&configuration=win%20win_64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--zigg-green.svg)](https://anaconda.org/conda-forge/r-zigg) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-zigg.svg)](https://anaconda.org/conda-forge/r-zigg) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-zigg.svg)](https://anaconda.org/conda-forge/r-zigg) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-zigg.svg)](https://anaconda.org/conda-forge/r-zigg) |

Installing r-zigg
=================

Installing `r-zigg` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-zigg` can be installed with `conda`:

```
conda install r-zigg
```

or with `mamba`:

```
mamba install r-zigg
```

It is possible to list all of the versions of `r-zigg` available on your platform with `conda`:

```
conda search r-zigg --channel conda-forge
```

or with `mamba`:

```
mamba search r-zigg --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-zigg --channel conda-forge

# List packages depending on `r-zigg`:
mamba repoquery whoneeds r-zigg --channel conda-forge

# List dependencies of `r-zigg`:
mamba repoquery depends r-zigg --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-zigg-feedstock
=========================

If you would like to improve the r-zigg recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-zigg-feedstock are
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

* [@conda-forge/r](https://github.com/orgs/conda-forge/teams/r/)

