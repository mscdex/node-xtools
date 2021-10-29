# Description

Cross compiler toolchains (for building node.js addons).

**WARNING:** The structure of this repo and the locations of the toolchains
may change without notice as I try to find out what works best.

# Host requirements

* Any x86_64/amd64 Linux

# Compilers

* Built with crosstools-ng (build.log included)
* gcc/g++ 11.2.0
* Targets:
  * glibc 2.17
  * kernel 3.10
  * architectures:
    * x64 = x86_64/amd64
    * arm64 = armv8-a
