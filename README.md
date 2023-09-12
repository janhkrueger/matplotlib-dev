# matplotlib-dev



## Purpose

Demo for MatPlotLib. Running in a devcontainer so no other installation beside Docker and Visual Studio Code needed.


## Container

The used container is prebuild and can loaded from Docker hub but can also fully build locally:


``` bash
docker build --no-cache -t janhkrueger/matplotlib_devcontainer:20230911 -f .devcontainer/Dockerfile .
```