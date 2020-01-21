About deepspectrum
==================

Home: https://github.com/DeepSpectrum/DeepSpectrum

Package license: GPL v3

Feedstock license: BSD 3-Clause

Summary: A tool for extracting deep CNN-descriptors from audio data.



Current build status
====================


<table><tr>
    <td>Travis</td>
    <td>
      <a href="https://travis-ci.com/DeepSpectrum/deepspectrum-feedstock">
        <img alt="macOS" src="https://img.shields.io/travis/com/DeepSpectrum/deepspectrum-feedstock/master.svg?label=macOS">
      </a>
    </td>
  </tr><tr>
    <td>Appveyor</td>
    <td>
      <a href="https://ci.appveyor.com/project/DeepSpectrum/deepspectrum-feedstock/branch/master">
        <img alt="windows" src="https://img.shields.io/appveyor/ci/DeepSpectrum/deepspectrum-feedstock/master.svg?label=Windows">
      </a>
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-deepspectrum-green.svg)](https://anaconda.org/DeepSpectrum/deepspectrum) | [![Conda Downloads](https://img.shields.io/conda/dn/DeepSpectrum/deepspectrum.svg)](https://anaconda.org/DeepSpectrum/deepspectrum) | [![Conda Version](https://img.shields.io/conda/vn/DeepSpectrum/deepspectrum.svg)](https://anaconda.org/DeepSpectrum/deepspectrum) | [![Conda Platforms](https://img.shields.io/conda/pn/DeepSpectrum/deepspectrum.svg)](https://anaconda.org/DeepSpectrum/deepspectrum) |

Installing deepspectrum
=======================

Installing `deepspectrum` from the `DeepSpectrum` channel can be achieved by adding `DeepSpectrum` to your channels with:

```
conda config --add channels DeepSpectrum
```

Once the `DeepSpectrum` channel has been enabled, `deepspectrum` can be installed with:

```
conda install deepspectrum
```

It is possible to list all of the versions of `deepspectrum` available on your platform with:

```
conda search deepspectrum --channel DeepSpectrum
```




Updating deepspectrum-feedstock
===============================

If you would like to improve the deepspectrum recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`DeepSpectrum` channel, whereupon the built conda packages will be available for
everybody to install and use from the `DeepSpectrum` channel.
Note that all branches in the DeepSpectrum/deepspectrum-feedstock are
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

* [@DeepSpectrum](https://github.com/DeepSpectrum/)
* [@mauricege](https://github.com/mauricege/)

