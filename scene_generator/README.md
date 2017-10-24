# README #

This is the physics simulation code used to generate random scene description textfiles used in the paper:

* **[SceneNet RGB-D: Can 5M Synthetic Images Beat Generic ImageNet Pre-training on Indoor Segmentation?](http://www.imperial.ac.uk/media/imperial-college/research-centres-and-groups/dyson-robotics-lab/jmccormac_etal_iccv2017.pdf)**, *John McCormac, Ankur Handa, Stefan Leutenegger, Andrew J Davison*, ICCV '17

# 1. How to build it? #

Compile ProjectChrono with CMake:

* [Project Chrono](http://projectchrono.org/) (and its [Irrlicht](http://downloads.sourceforge.net/irrlicht/irrlicht-1.8.2.zip) dependency)

Modify the CMakeLists.txt in this folder to the build/cmake directory containing the ChronoConfig.cmake file

```
set(Chrono_DIR "/path/to/your/chrono/build/cmake")
```

Then build normally. I.e.:

```
mkdir build
cd build
cmake ..
make
```