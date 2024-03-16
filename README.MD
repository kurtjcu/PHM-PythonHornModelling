# PHM-PythonHornModelling

## Introduction

A Collection of tools and information/lings WRT to making the modelling, simulation and development of acoustic horns for audio reproduction.

[See DEVELOP branch for latest...](https://github.com/kurtjcu/PHM-PythonHornModelling/tree/develop)

This repo is to organise my exploration im making this process simpler, better and/or easier to automate via python.

## Goals
### stage 1 
Model some horns/waveguides that are already well characterised to ensure the approach is a resonable solution to the problem.

### Assumptions
1. Priorities are for modelling horns/waveguides driven by compression drivers
2. Start of the wavefront is planar (spherical can come later).
3. Primary interest is developing/simulating constant directivity horns.
4. Simulations to be done either in free space ( free standing horn) or on an essentially infinite plane (baffle mounted horn).
5. Output id top generate graphs of interest when developing these types of devices i.e. SPL vs freq @ angle.

### problems
1. Spherical source radiating
  1.1.Free space
  1.2 Half space
  1.3 Quarter space
2. Hemispherical source in a planar tube
3. Planar source in 
  3.1 a planar tube
  3.2 a conical tube
  3.3 an oblate spheriod 



## Developing
This repo uses a git-flow branching methodology. The master branch is the stable release branch. The develop branch is the current development branch. Feature branches are created from the develop branch and merged back into the develop branch. When a release is ready, the develop branch is merged into the master branch and tagged with the release number. It is likely that a release may take a long time to be ready, so the master branch may be behind the develop branch for a long time( or forever...:) ). 

