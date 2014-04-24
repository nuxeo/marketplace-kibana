marketplace-kibana
===============================

## About

This is project allows to build the marketplace package for `nuxeo-kibana` addon.

The goal of this package is to provide an easy way to test `Kibana` with Nuxeo:

## Building

To build and run the tests, simply start the maven build:

    mvn clean install


## Installing

To install the package:

 - take a fresh nuxeo CAP 5.9.3
 - then install the package
      - from the AdminCenter (Upload + install)
      - from the command line using `nuxeoctl mp-install package.zip --nodeps`


