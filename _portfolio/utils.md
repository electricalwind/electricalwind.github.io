---
title: "Utils"
excerpt: "Toolkit for SE <br/><img src='/images/tools.jpeg'>"
collection: portfolio
---
# [Files Metric](https://github.com/electricalwind/FilesMetrics/)

Written in Kotlin, this project aims at providing a library for computing common metrics of a C file from Java program.
The analysis is based on the result provided by the [joern tool](https://github.com/fabsx00/joern).
To allow a better handling of dependency the tool has been ported organized for maven and only the parts relevant to this project were kept.
This version can be found in the joern repository

## Computed Metrics
 List of Code Metrics:
 
 * Blank Line
 * LOC
 * preprocessor Lines
 * Lines of comments
 * Comment/LOC ratio
 * Number of Function
 * Number of Variable declaration
 * Cyclomatic Complexity of all Function
 * Essential Complexity of all Function
 * FANIN
 * FANOUT

# [ToolsUtils](https://github.com/electricalwind/tools-utils/)

This library gather all utilitary methods that are used by the different modules of the bugs and vulnerabilities project and that could be used in other context.

## Content

* Git utilitary + diff
* MultiThreading
* Regexp
* Serialization 

[Documentation](https://github.com/electricalwind/tools-utils/doc/)
