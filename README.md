# OpenHDMap
An open HD Map production process for autonomous driving simulation

## Introduce  
The goal of this project is to make it easier to view and edit HD maps. The entire architecture is as follows:
![Architecture](docs/img/Architecture.jpg)  
The tool uses multiple layers to display and edit HD maps.  
![Layers](docs/img/Layers.jpg)  

* Statistics and counting function - How many lanes are there in the whole picture, how big is the curvature, how many intersections, etc.
* Positioning function - Quickly locate to a specified location, including input channels, location information, specific conditions, etc.

Here's how the model to map and map to model conversion relationship  
![map_edit](docs/img/map_edit.jpg)  

## Quick start

#### Process
1. **Make point cloud map** - Use "pycpd" or "Open3D" to make a point cloud map.  
2. **Annotation point cloud map** - Manual or automate generate the topologic of map.  

Benchmark of the process:  
* accurate
* time


#### Examples

#### How to build
  


## Reference
[vector tiles](https://docs.mapbox.com/vector-tiles/reference/)
[awesome-vector-tiles](https://github.com/mapbox/awesome-vector-tiles)

[paperjs](http://paperjs.org/examples/hit-testing/)  
[best-javascript-drawing-libraries](https://www.slant.co/topics/28/~best-javascript-drawing-libraries)  

