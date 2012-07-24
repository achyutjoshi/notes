# Python Package Management

### tl;dr

setuptools with easy_install, distribute with pip as well as the new distutils2
efforts and not one covers all use cases.

[Source](http://lucumr.pocoo.org/2012/6/22/hate-hate-hate-everywhere/)

## setuptools

setuptools is a collection of enhancements to the Python distutils that allow
you to more easily build and distribute Python packages, especially ones that
have dependencies on other packages.

Packages built and distributed using setuptools look to the user like ordinary
Python packages based on the distutils. Your users don't need to install or even
know about setuptools in order to use them, and you don't have to include the
entire setuptools package in your distributions. By including just a single
bootstrap module (an 8K .py file), your package will automatically download and
install setuptools if the user is building your package from source and doesn't
have a suitable version already installed.

### easy_install

Easy Install is a python module (easy_install) bundled with setuptools that lets
you automatically download, build, install, and manage Python packages.

## distutils

[TBC]
