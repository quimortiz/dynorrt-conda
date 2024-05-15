# Dynorrt-conda

This repository converts the package [dynorrt](https://github.com/quimortiz/dynorrt) (C++ with Python bindings, CMake-based) into a Conda [package](https://anaconda.org/quimortiz/dynorrt).

## Usage
Download and install the package and dependencies with:
```
conda install quimortiz::dynorrt -c conda-forge
```
Note: conda-forge is needed for dependencies.

## Development

Build the package with:
```
conda build recipe -c conda-forge
```

Upload the package with (copy the command that appears in the terminal at the end of the build process):
```
anaconda upload ...
```
