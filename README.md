This converts the cmake-based package dynorrt into a conda package

The conda package is at: 
```
https://anaconda.org/quimortiz/dynorrt
```

Download and install the pakcage and dependencies with (conda-forge is needed for dependencies)
```
conda install quimortiz::dynorrt  -c conda-forge
```

Build the package with:
```
conda build recipe -c conda-forge 
```

Upload the package with (I just copy the command that appears in the terminal at the end of the build process)
```
anaconda upload ...
```







