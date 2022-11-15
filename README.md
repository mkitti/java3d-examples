Java3D Examples Readme
===
This project contains the source code for the Java3D example programs.     

The source code for j3d-examples is licensed under a Berkely Software Distribution (BSD) License.  

The copyright notice for this project is in COPYRIGHT.txt  

The source code license information for this project is in LICENSE.txt  

NOTE: This project contains third-party source code that is provided under separate licensing terms. These terms are are found in the THIRDPARTY-LICENSE-*.txt files in the top level-directory of this project.  

Related projects include: java3d-core (the core 3D package), vecmath (the 3D vector math package), and java3d-utils (the 3D core utilities).  
Developers should refer to the java3d-core readme.md file for information on downloading the source code and building j3d-examples. 

# Fork modifications for [mkitti/java3d-examples](https://github.com/mkitti/java3d-examples)

1. Added dependencies to pom.xml 
2. Setup temporary java3d1.7 sub-directory to temporarily hold jar files

## Java3D Links

Several dependencies are needed for Java3D 1.7:
* j3dcore.jar
* j3dutils.jar
* vecmath.jar

The jar files can be downloaded from https://jogamp.org/deployment/java3d/1.7.0-final/

Currently, this fork is modified so these jar files can be placed in the sub-directory `java3d1.7`. This should
be resolved by placing these jar files in a true local or remote mvn repository.

See the discussion here about the release of Java3D 1.7-final:
https://forum.jogamp.org/Where-is-the-latest-version-of-Java3D-tp4040278p4040292.html

Java 3D 1.7 Source URLs:
* https://github.com/philjord/java3d-core
* https://github.com/philjord/java3d-utils
* https://github.com/philjord/vecmath

Alternatively, consider the fork of the repository under JogAmp
* https://github.com/JogAmp/java3d-core
* https://github.com/JogAmp/java3d-utils
* https://github.com/JogAmp/vecmath
* https://github.com/JogAmp/java3d-examples
