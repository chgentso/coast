.. COAST documentation master file, created by
   sphinx-quickstart on Mon Jul  8 13:39:59 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

COAST
********

**CO**\ mpiler-\ **A**\ ssisted **S**\ oftware fault **T**\ olerance

.. toctree::
    :maxdepth: 2
    :caption: Contents:

    setup
    make_system
    eclipse
    passes
    troubleshooting
    cfcss

Folder guide
==============

build
---------

This folder contains instructions on how to build LLVM, and when built will contain the binaries needed to compile source code.

llvm
---------

The source code for LLVM and associated tools.

projects
---------

The passes that we have developed as part of COAST.

tests
---------

Benchmarks we use to validate the correct operation of COAST.

Results
========

See the results of fault injection and radiation beam testing

.. toctree::
    :maxdepth: 1
    :glob:

    results/*


Additional Resources
=====================

- Matthew Bohman's `Master's thesis`_.

- IEEE Transactions on Nuclear Science, Vol. 66 Issue 1 - `Microcontroller Compiler-Assisted Software Fault Tolerance`_

.. _Master's thesis: https://scholarsarchive.byu.edu/cgi/viewcontent.cgi?article=7724&context=etd

.. _Microcontroller Compiler-Assisted Software Fault Tolerance: https://ieeexplore.ieee.org/document/8571250
