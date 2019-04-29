Title:   Artifact evaluation
Author:  Soonho Kong
Date:    28 Apr 2018
CSS: css/tufte.css

Artifact evaluation of the following paper.

```
Numerically-Robust Inductive Proof Rules for Continuous Dynamical Systems
Sicun Gao, James Kapinski, Jyotirmoy Deshmukh, Nima Roohi, Armando Solar-Lezama, Nikos Arechiga and Soonho Kong
In CAV (International Conference on Computer Aided Verification) 2019
```

Virtual Machine
---------------

 - Image File: [Google Drive](https://drive.google.com/open?id=1-s0dAHbMBzuUQhMrov34Yi3EBlQTzI7K)
 - SHA256 of Image: `c07ad7c2e5986fbcb10d52df13f8c2c42a59143d958de5125323bc5acb9684db`
 - OS: Ubuntu 16.04.3 LTS
 - Account (ID/Password): cav / ae
 - Host Platform: 2018 Macbook Pro with 2.9 GHz Intel Core i9
   (6-Core) and 32 GB RAM running MacOS 10.14.4

Coverage
--------

 - Section 5 Experiments
    - Table 1: Results for the ε-Lyapunov functions.
    - Table 2: Results for the ε-barrier functions.

Instructions
------------

 - Log in the provided VM. 
 - Open a terminal and run `./examples/RebuildAndRun.sh` (and wait about 6 minutes).

Quality
-------

 - The benchmark is included in the dReal4 build system. One can build and run it by executing the following commands at the dReal4 root directory:
    ```bash
    bazel build //dreal/api:cav19_benchmark
    ./bazel-bin/dreal/api/cav19_benchmark
    ```
 - Source code of the benchmark is available at [dreal/api/test/cav19_benchmark.cc](https://github.com/dreal/dreal4/blob/master/dreal/api/test/cav19_benchmark.cc).
 - We set up a [CI (Continuous Integration) service](https://travis-ci.org/dreal/dreal4) to make sure that
   we can build the benchmark in machines running macOS and Ubuntu.
