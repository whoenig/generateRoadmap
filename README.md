# generateRoadmap
Command line tool to generate SPARS roadmaps

## Build

Tested on Unbuntu 16.04

```
mkdir build
cd build
cmake ..
make
```

## Run

```
./generateRoadmap -e ../examples/map1.bt -r "<Sphere:0.15>" -o roadmap.yaml -a ../examples/addVertices1.yaml -c ../examples/roadmapConfig1.yaml --type SPARS
```

The average edge length can be controlled by `sparseDelta` in the roadmapConfig file.
