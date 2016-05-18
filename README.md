# hg-sdf-metal
A port of the [hg_sdf](http://mercury.sexy/hg_sdf/) glsl library for building signed distance functions, for use in metal compute kernels


## How to use

Add the hg_sdf file to your project in the same folder as your metal compute kernel

Add the following import to your metal kernel file

`#include "hg_sdf"`

Call the sdf functions from your kernel code
