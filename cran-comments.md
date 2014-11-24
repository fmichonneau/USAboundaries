## Resubmission

This is a resubmission of the package that makes the following changes requested by CRAN maintainers:

* Capitalized "USA" part of the package title
* Revised the package description to use "United States of America" every time
* Remove "aut" role from the Newberry Library, retaining only their role as copyright holder

## Test environments

* local OS X install (R 3.1.2)
* Ubuntu 14.04.1 in a virtual machine (R 3.1.2)
* win-builder (devel and release)

## R CMD check results

There were no errors or warnings. 

There was 1 NOTE: 

* checking CRAN incoming feasibility ... NOTE
  Non-FOSS package license (CC BY-NC-SA 4.0)

  This package is released under that non-FOSS license because the data it uses is released under that license.

In addition, the package install time seems to be a little high (13 seconds on my machine) but that is because the data is very compressed.