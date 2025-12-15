# PoseLib - Minimal solvers for calibrated camera pose estimation

This is a `build2` package for the [`PoseLib`](https://github.com/PoseLib/PoseLib)
C++ library. This library provides a collection of minimal solvers for camera pose estimation. The focus is on calibrated absolute pose estimation problems from different types of correspondences (e.g. point-point, point-line, line-point, line-line).


## Usage

To start using `PoseLib` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: PoseLib ^2.0.5
```

Then import the library in your `buildfile`:

```
import libs = PoseLib%lib{PoseLib}
```


## Importable targets

This package provides the following importable targets:

```
lib{PoseLib}
```


## Configuration variables

This package provides the following configuration variables:
