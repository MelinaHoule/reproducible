## Updated release

This is a major release with key dependencies removed and the backend changed from `archivist` to `DBI`. This will break downstream dependencies. See `NEWS.md`.

## Test environments

Tested and passed using winbuilder all three versions, and rhub with no errors, warnings, or notes.

### Previous R versions
* Ubuntu 16.04              (travis-ci), R 3.5.3
* Windows                    (appveyor), R 3.5.3
* Windows                 (win-builder), R 3.5.3

### Current R versions
* macOS 10.13.3 High Sierra (travis-ci), R 3.6.2
* macOS 10.15.1 Catalina        (local), R 3.6.2
* Ubuntu 16.04              (travis-ci), R 3.6.2
* Ubuntu 18.04                  (local), R 3.6.2
* Windows                    (appveyor), R 3.6.2
* Windows                 (win-builder), R 3.6.2

### Development R version
* Ubuntu 16.04              (travis-ci), R 4.0.0 (2020-02-13)
* Ubuntu 18.04                  (local), R 4.0.0 (2020-02-13)
* Windows                    (appveyor), R 4.0.0 (2020-02-13)
* Windows                 (win-builder), R 4.0.0 (2020-02-13)

## R CMD check results

There were no ERRORs, nor WARNINGs, nor NOTEs.

## Downstream dependencies

We have run R CMD check on downstream dependencies. `SpaDES.core` requires updates. We will submit this package immediately upon `reproducible` being accepted. `SpaDES.tools`, `SpaDES` and `SpaDES.addins` are unaffected.

