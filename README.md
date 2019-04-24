Title:   Artifact evaluation
Author:  Soonho Kong
Date:    15 Apr 2018
CSS: css/tufte.css

Artifact evaluation of the following paper.

```
Numerically-Robust Inductive Proof Rules for Continuous Dynamical Systems
Sicun Gao, James Kapinski, Jyotirmoy Deshmukh, Nima Roohi, Armando Solar-Lezama, Nikos Arechiga and Soonho Kong
In CAV (International Conference on Computer Aided Verification) 2019
```

Virtual Machine
---------------

 - Image File: `TODO`
 - SHA256 of Image: `TODO`
 - OS: ubuntu-18.04.2-desktop-amd64
 - Account (ID/Password): cav / ae
 - Host Platform: 2018 Macbook Pro with 2.9 GHz Intel Core i9
   (6-Core) and 32 GB RAM running MacOS 10.14.4
   

Coverage
--------

 - Section 4.2 Type 1: Strict Contraction
    - Figure 3 Van der Pol Example
 - Section 4.3 Type 2: Bounded Escape
    - Figure 4 Type 2 Barrier Example
 - Section 5 Experiments
    - Table 1: Results for the ε-Lyapunov functions.
    - Table 2: Results for the ε-barrier functions.

Instructions
------------

Log in the provided VM (ID: `cav`, PASSWORD: `ae`). Open a terminal
and execute the following instructions.

`TODO`

Quality
-------

 - Source code of the implementation, dReal4, is available at
   [https://github.com/dreal/dreal4/tree/cav19](https://github.com/dreal/dreal4/tree/cav19).
 - Its
   [README.md](https://github.com/dreal/dreal4/blob/master/README.md)
   file provides build and install instructions.
 - Source code is documented using Doxygen. Documentation webpage is
   at
   [https://dreal.github.io/dreal4](https://dreal.github.io/dreal4).
 - We provide a comprehensive set of unittests, which can be executed by running
	"`bazel test //...`".
 - We provide packages for macOS (via homebrew) and Debian/Ubuntu
   Linux. The instructions are in the
   [README.md](https://github.com/dreal/dreal4/blob/master/README.md).
