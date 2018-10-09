## sketchtree

### Note
[Additional code for Journal version]

### Introduction



### About this repo

This repo contains the code of Sketchtree for measurement.



This repo also contains a small demo to show how to use this algorithms with a small dataset.

### Requirements

- The gather-and-report part of CF use SIMD instructions to achieve high speed, so the cpu must support SSE2 instruction set.
- cmake >= 2.6
- g++ (MSVC is not supported currently.)

### How to build

The project is built upon [cmake](https://cmake.org/). You can use the following commands to build and run.

```
mkdir build
cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
make
cd ../
./demo
```

### Related paper
Accurate traffic measuremnet with hierarchical filtering (https://github.com/haiporwang/sketchtree/)
