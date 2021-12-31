# Smaller than BigBaseV2
I keep losing the source code of my hacky native entry point dumper built on BigBaseV2 so I'm just going to keep the repo here.
Will work with 2545.

## Features
* A console
* Edgy ascii art
* Dumps entry points of natives to natives.txt

## Building
To build BigBaseV2 you need:
* Visual Studio 2019
* [Premake 5.0](https://premake.github.io/download.html) in your PATH

To set up the build environment, run the following commands in a terminal:
```dos
git clone https://github.com/rudehacks/SmallBaseV2.git --recurse-submodules
cd SmallBaseV2
premake5 vs2019
```
Now, you will be able to open the solution, and simply build it in Visual Studio.
