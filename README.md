# .NET port of LMAX Disruptor [![Build status](https://ci.appveyor.com/api/projects/status/pwgyxwrgglkbr6md/branch/master?svg=true)](https://ci.appveyor.com/project/MendelMonteiro/disruptor-net/branch/master) [![NuGet](https://buildstats.info/nuget/Disruptor)](http://www.nuget.org/packages/Disruptor/)

This project aims to provide the full functionality of the Disruptor to CLR projects.

## Roadmap

* Include latest changes made to the future java versions

## What's new?

02/05/2017 (v3.3.6):

* Support .NET Core 1.1

01/04/2017 (v3.3.6-alpha):

* All features available in Java Disruptor **3.3.6** have been ported
* Use an aggressive spin wait in all blocking wait strategies (#25)
* Add a new blocking low CPU usage wait strategy

02/08/2016 (v3.3.5):

* All features available in Java Disruptor **3.3.5** have been ported

04/07/2016 (v3.3.4):

* All features available in Java Disruptor **3.3.4** have been ported by the team at [ABC Arbitrage](http://abc-arbitrage.com) 
* Now targeting the .NET 4.6.1 framework and using C# 6 features

11/7/2013 (v2.10.0):

* All features available in Java Disruptor **2.10.0** have been ported 

## Getting Started

The quickest way to get started with the disruptor is by using the [NuGet package]

## Build from source and run tests

You may also build the Disruptor directly from the source:
* You need Visual Studio 2017
* run `Cake-Build.bat`, it will compile, run the tests and output binaries and results into `\output\assembly` folder

You can also run all the performance tests by running `Cake-Perf.bat`.

[NuGet package]: http://nuget.org/packages/Disruptor

## License

Copyright Olivier Deheurles

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License.

You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
