# PoseLib - Minimal solvers for calibrated camera pose estimation

This is a `build2` package repository for [`PoseLib`](https://github.com/PoseLib/PoseLib),
a library that provides a collection of minimal solvers for camera pose estimation. The focus is on calibrated absolute pose estimation problems from different types of correspondences (e.g. point-point, point-line, line-point, line-line).

This file contains setup instructions and other details that are more
appropriate for development rather than consumption. If you want to use
`PoseLib` in your `build2`-based project, then instead see the accompanying
[`PACKAGE-README.md`](PoseLib/PACKAGE-README.md) file.

The development setup for `PoseLib` uses the standard `bdep`-based workflow.
For example:

```
git clone .../PoseLib.git
cd PoseLib

bdep init -C @gcc cc config.cxx=g++
bdep update
bdep test
```
