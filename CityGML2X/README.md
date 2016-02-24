# CityGML2X

A Java library for converting CityGML to X3D and Collada

Features:
* During conversion, colorize the roofs and wall surfaces
* Multi surfaces referenced by boundary surfaces (boundedBy) will be prefered for LOD2 multi-surface geometries.
* Resolve XLINKS to abstract surfaces and solids
* Converts composite solids
* Converts nested building parts
* Add basic inline documentation and copyright information
* Count the number of processed building parts and geometries
* Reads CityGML v1.0 and v2.0
* Writes X3D v3.3
* Validates CityGML input streams
* Converts solid geometries
* Converts multi-surface geometries
* Converts LOD1 and LOD2 geometries
* Converts composite surfaces
* Resolves XLINKs for composite surfaces
* Resolves XLINKs in multi surfaces (surface members)
* Eliminates douplicated vertices in the final X3D file which saves a significant amount of disk space
* Wraps all converted building geometries in a single X3D indexed face set (increases performance)
* Generates an individual indexed face sets for each converted building geometry
* Converts and combine multiple CityGML files in one shot
* Counts the number of processed buildings