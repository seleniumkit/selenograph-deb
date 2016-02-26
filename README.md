# Selenograph Debian Packages
This repository contains Debian (Ubuntu) package configuration for **Selenograph**.
## How to build package
In order to build this package you need to have **devscripts** package installed. In order to build the package you should execute the following commands from the repository root directory:
```
$ ./build-package.sh
```
When the package is built you should upload package to LaunchPad server via the following command:
```
$ dput ppa:yandex-qatools/selenograph ../yandex-selenograph-<version>.changes
```
