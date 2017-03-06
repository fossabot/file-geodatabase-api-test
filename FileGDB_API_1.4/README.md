\\# FileGeodatabaseAPI_1.4 (1.4.0.183)
The File Geodatabase C++ API for Windows, MacOS and Linux. .NET bindings are included.

## Features

## Instructions
Download the operating system/compiler varient(s) of the API that you need and unzip it into a folder.

Linux (32-bit, 64-bit):
FileGDB_API_1_4-32.tar.gz
FileGDB_API_1_4-64.tar.gz

MacOS:
Mountain Lion 10.8: FileGDB_API_1_4-64clang.zip
Mavericks (10.9) and Yosemite (10.10): FileGDB_API_1_4-64gcc.zip

Windows:
FileGDB_API_VS2010_1_4.zip
FileGDB_API_VS2012.zip
FileGDB_API_VS2013.zip
## Requirements

#####Windows
        Windows 2008 Server Standard, Enterprise & Datacenter (32-bit and 64-bit) SP2
        Windows 2008 R2 Server Standard, Enterprise, and Datacenter (64-bit)
        Windows 2012 Server Statard and Datacenter (64-bit)  
        Windows 2012 R2 Server Statard and Datacenter (64-bit)  	 
        Windows 7 Ultimate, Enterprise, Professional, Home Premium (32-bit and 64-bit)
        Windows 8.0 Enterprise, Profesional  (32-bit and 64-bit)
        Windows 8.1 Enterprise, Profesional  (32-bit and 64-bit)
		 
		Visual Studio 2010 (C++) Standard, Professional, or Team Editions required for development.
		Visual Studio 2010 C and C++ Runtimes required for deployment.
		.NET 4.0 Framework is required for the .NET wrapper.

		Visual Studio 2012 SP4 (C++) Premium, Professional, Ultimate or Team Editions required for development.
		Visual Studio 2012 C and C++ Runtimes required for deployment.
		.NET 4.5 Framework is required for the .NET wrapper.

		Visual Studio 2013 SP1 (C++) Premium, Professional, Ultimate or Team Editions required for development.
		Visual Studio 2013 C and C++ Runtimes required for deployment.
		.NET 4.5.1 Framework is required for the .NET wrapper.
#####Linux
		The minimum supported platform is "Red Hat Enterprise Linux Release 5.7" or 
		"SUSE Linux Enterprise Server 11". The minimum supported compiler is gcc 
		version 4.1.2.
#####MacOS
		An Intel-based Mac is required.
		The minimum supported OS is Mountain Lion 10.8. gcc 4.2.1 is required. 
		Also Mavericks (10.9) and Yosemite (10.10) clang 3.7

## Resources
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis/)
* [GeoNet] (https://geonet.esri.com/community/developers/gis-developers/file-geodatabase-api)
* Esri customers can call Technical Support for assistance or to report issues.

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

##  Known Issues 
* Concurrent access from Windows and Linux clients to the same File GeoDatabase can corrupt data. This combination should be avoided.
* SQL joins are not supported.

## Fixed Issues at 1.4:
* NIM071731 Add support for Compressed Data File. (Read Only)
* NIM073951 Request to support custom spatial references with the File Geodatabase API.
* NIM082242 ENH: File Geodatabase API (v1.2) executeSQL should honor SELECT statement's nominated field list, in the returned EnumRows object, instead of all fields.
* NIM084105 MultiPartShapeBuffer::GetMs return the wrong pointer value 
* NIM085366 Using only a null or empty geometry results in a invalid extent.
* NIM085995 Using ExecuteSQL with an ORDER BY on a text field fails on MacOS
* NIM098151 Table.GetDefinition function leaks memory
* NIM098225 CloseGeodatabase hangs on 64-bit if same gdb opened more than once
* NIM098322 Getter/setter functions by name need to be optimized for sequential search across the column selection list.
* NIM099041 Some apparently valid XML feature class definitions create tables that fail on export and copy/paste.

## Licensing
Copyright 2016 Esri

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
