About numkl
===========

Home: https://github.com/refraction-ray/numkl

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: A thin cython/python wrapper on some routines from Intel MKL



Current build status
====================


<table><tr>
    <td>Travis</td>
    <td>
      <a href="https://travis-ci.org/conda-forge/numkl-feedstock">
        <img alt="macOS" src="https://img.shields.io/travis/conda-forge/numkl-feedstock/master.svg?label=macOS">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/numkl-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/numkl-feedstock?branchName=master&jobName=linux&configuration=linux_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/numkl-feedstock?branchName=master&jobName=osx&configuration=osx_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/numkl-feedstock?branchName=master&jobName=win&configuration=win_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
 <tr>
    <td>ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-numkl-green.svg)](https://anaconda.org/refraction-ray/numkl) | [![Conda Downloads](https://img.shields.io/conda/dn/refraction-ray/numkl.svg)](https://anaconda.org/refraction-ray/numkl) | [![Conda Version](https://img.shields.io/conda/vn/refraction-ray/numkl.svg)](https://anaconda.org/refraction-ray/numkl) | [![Conda Platforms](https://img.shields.io/conda/pn/refraction-ray/numkl.svg)](https://anaconda.org/refraction-ray/numkl) |

Installing numkl
================

Installing `numkl` from the `refraction-ray` channel can be achieved by adding `refraction-ray` to your channels with:

```
conda config --add channels refraction-ray
```

Once the `refraction-ray` channel has been enabled, `numkl` can be installed with:

```
conda install numkl
```

It is possible to list all of the versions of `numkl` available on your platform with:

```
conda search numkl --channel refraction-ray
```




Updating numkl-feedstock
========================

If you would like to improve the numkl recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`refraction-ray` channel, whereupon the built conda packages will be available for
everybody to install and use from the `refraction-ray` channel.
Note that all branches in the conda-forge/numkl-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@refraction-ray](https://github.com/refraction-ray/)

