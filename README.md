\\# FileGeodatabaseAPI_1.4 (1.4.0.183)
The File Geodatabase C++ API for Windows, MacOS and Linux. .NET bindings are included.

## Features

## Instructions
Download the operating system/compiler varient(s) of the API that you need.

## Requirements

For details see the README.md in the operating system\compiler director.
Windows
   Visual Studio 2010
   Visual Studio 2012
   Visual Studio 2013
Linux
   gcc version 4.1.2 (minimum supported compiler)
MacOS
   gcc 4.2.1. Mountain Lion 10.8
   clang 3.7, Mavericks (10.9) and Yosemite (10.10) 

## Resources
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis/)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

##  Known Issues 
* Concurrent access from Windows and Linux clients to the same File GeoDatabase can corrupt data. This combination should be avoided.
* SQL joins are not supported.

## Fixed Issues:

NIM071731 Add support for Compressed Data File. (Read Only)
NIM073951 Request to support custom spatial references with the File Geodatabase API.
NIM082242 ENH: File Geodatabase API (v1.2) executeSQL should honor SELECT statement's nominated field list, in the returned EnumRows object, instead of all fields.
NIM084105 MultiPartShapeBuffer::GetMs return the wrong pointer value 
NIM085366 Using only a null or empty geometry results in a invalid extent.
NIM085995 Using ExecuteSQL with an ORDER BY on a text field fails on MacOS
NIM098151 Table.GetDefinition function leaks memory
NIM098225 CloseGeodatabase hangs on 64-bit if same gdb opened more than once
NIM098322 Getter/setter functions by name need to be optimized for sequential search across the column selection list.
NIM099041 Some apparently valid XML feature class definitions create tables that fail on export and copy/paste.

## Contributing

Esri welcomes contributions from anyone and everyone. Please see our [guidelines for contributing](https://github.com/esri/contributing).

## Licensing
Copyright 2015 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [License.txt](License.txt)

[](Esri Tags: FileGDB API C++)
[](Esri Language: C++)​
