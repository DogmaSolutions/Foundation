# About this package
This package is part of the Dogma Solutions *"Foundation"* project.  
For more details, see the list of packages below.

# Dogma Solutions Foundation
The Dogma Solutions *"Foundation"* project (2005-2025) is an attempt to provide a basic and modern set of (opinionated):
- Interfaces and abstractions for objects, DTOs, an entities modeling
- Recyclable low-level functionalities
- Simple implementations of most common design patterns

# Versioning criteria
All packages follows the conventions of [Semantic Versioning 2.0.0](https://semver.org/).  
Cit.:
```
Given a version number MAJOR.MINOR.PATCH, increment the:
1. MAJOR version when you make incompatible API changes
2. MINOR version when you add functionality in a backward compatible manner
3. PATCH version when you make backward compatible bug fixes

Additional labels for pre-release and build metadata are available as extensions
to the MAJOR.MINOR.PATCH format.
```


# Supported .NET versions
Different versions of the packages, support a different set of .NET versions:

| Package version 	   | Status       | Supported .NET versions 	                              | Remarks (compared to previous version)       |   
|---------------------|--------------|--------------------------------------------------------|----------------------------------------------| 
| 5.0.*             	 | ✅ Current    | netstandard2.0, net6.0, net7.0, net8.0, net9.0  	      | Added net9.0, dropped net472                 |
| 4.3.*             	 | ✅ Maintained | netstandard2.0, net472, net5.0, net6.0, net7.0, net8.0 |                                              |
| 4.2.*             	 | ⚠ Obsolete   | netstandard2.0, net472, net5.0, net6.0, net7.0, net8.0 | Added net7.0 & net8.0                        |
| 4.1.*             	 | ❌ EOS        | netstandard2.0, net472, net5.0, net6.0  	              |                                              |
| 4.0.*             	 | ❌ EOS        | netstandard2.0, net472, net5.0, net6.0  	              |                                              |
| 3.2.*             	 | ❌ EOS        | netstandard2.0, net472, net5.0, net6.0  	              |                                              |
| 3.1.*             	 | ❌ EOS        | netstandard2.0, net472, net5.0, net6.0  	              | Added net5.0 & net6.0                        |
| 3.0.*             	 | ❌ EOS        | netstandard2.0, net472  	                              |                                              |
| 2.0.*             	 | ❌ EOS        | netstandard2.0, net472  	                              | Added netstandard2.0 & net472, dropped net46 |
| 1.0.*             	 | ❌ EOS        | net46  	                                               |                                              |
 

---

# Packages
Every package contains a specific subset of functionalities related to a specific area of interest.  
Here follows a list of NuGet packages aggregated by topic.

## Application infrastructure and configuration
- [![DogmaSolutions.ApplicationInfrastructure on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.ApplicationInfrastructure.svg)](https://www.nuget.org/packages/DogmaSolutions.ApplicationInfrastructure/) DogmaSolutions.ApplicationInfrastructure
- [![DogmaSolutions.AspNetCore on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.AspNetCore.svg)](https://www.nuget.org/packages/DogmaSolutions.AspNetCore/) DogmaSolutions.AspNetCore
- [![DogmaSolutions.AspNetCore.Security on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.AspNetCore.Security.svg)](https://www.nuget.org/packages/DogmaSolutions.AspNetCore.Security/) DogmaSolutions.AspNetCore.Security
- [![DogmaSolutions.CommandLine on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.CommandLine.svg)](https://www.nuget.org/packages/DogmaSolutions.CommandLine/) DogmaSolutions.CommandLine
- [![DogmaSolutions.Configuration on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Configuration.svg)](https://www.nuget.org/packages/DogmaSolutions.Configuration/) DogmaSolutions.Configuration
- [![DogmaSolutions.Configuration.SqlLite on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Configuration.SqlLite.svg)](https://www.nuget.org/packages/DogmaSolutions.Configuration.SqlLite/) DogmaSolutions.Configuration.SqlLite
- [![DogmaSolutions.Configuration.SqlServer on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Configuration.SqlServer.svg)](https://www.nuget.org/packages/DogmaSolutions.Configuration.SqlServer/) DogmaSolutions.Configuration.SqlServer

## Benchmarking and monitoring
- [![DogmaSolutions.Benchmarking on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Benchmarking.svg)](https://www.nuget.org/packages/DogmaSolutions.Benchmarking/) DogmaSolutions.Benchmarking
- [![DogmaSolutions.Benchmarking.MicrosoftLogging on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Benchmarking.MicrosoftLogging.svg)](https://www.nuget.org/packages/DogmaSolutions.Benchmarking.MicrosoftLogging/) DogmaSolutions.Benchmarking.MicrosoftLogging
- [![DogmaSolutions.Prtg on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Prtg.svg)](https://www.nuget.org/packages/DogmaSolutions.Prtg/) DogmaSolutions.Prtg

## Security and cryptography
- [![DogmaSolutions.Certificates on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Certificates.svg)](https://www.nuget.org/packages/DogmaSolutions.Certificates/) DogmaSolutions.Certificates
- [![DogmaSolutions.Cryptography on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Cryptography.svg)](https://www.nuget.org/packages/DogmaSolutions.Cryptography/) DogmaSolutions.Cryptography
- [![DogmaSolutions.AspNetCore.Security on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.AspNetCore.Security.svg)](https://www.nuget.org/packages/DogmaSolutions.AspNetCore.Security/) DogmaSolutions.AspNetCore.Security
- [![DogmaSolutions.Security on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Security.svg)](https://www.nuget.org/packages/DogmaSolutions.Security/) DogmaSolutions.Security
- [![DogmaSolutions.Security.Ldap on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Security.Ldap.svg)](https://www.nuget.org/packages/DogmaSolutions.Security.Ldap/) DogmaSolutions.Security.Ldap
- [![DogmaSolutions.EntityFrameworkCore.Encryption on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.EntityFrameworkCore.Encryption.svg)](https://www.nuget.org/packages/DogmaSolutions.EntityFrameworkCore.Encryption/) DogmaSolutions.EntityFrameworkCore.Encryption
- [![DogmaSolutions.EntityFrameworkCore.Encryption.Abstractions on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.EntityFrameworkCore.Encryption.Abstractions.svg)](https://www.nuget.org/packages/DogmaSolutions.EntityFrameworkCore.Encryption.Abstractions/) DogmaSolutions.EntityFrameworkCore.Encryption.Abstractions

## Primitives, data modeling and data manipulation
- [![DogmaSolutions.Contracts on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Contracts.svg)](https://www.nuget.org/packages/DogmaSolutions.Contracts/) DogmaSolutions.Contracts
- [![DogmaSolutions.Collections on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Collections.svg)](https://www.nuget.org/packages/DogmaSolutions.Collections/) DogmaSolutions.Collections
- [![DogmaSolutions.Collections.Smart on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Collections.Smart.svg)](https://www.nuget.org/packages/DogmaSolutions.Collections.Smart/) DogmaSolutions.Collections.Smart
- [![DogmaSolutions.Csv on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Csv.svg)](https://www.nuget.org/packages/DogmaSolutions.Csv/) DogmaSolutions.Csv
- [![DogmaSolutions.Geography on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Geography.svg)](https://www.nuget.org/packages/DogmaSolutions.Geography/) DogmaSolutions.Geography
- [![DogmaSolutions.Json on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Json.svg)](https://www.nuget.org/packages/DogmaSolutions.Json/) DogmaSolutions.Json
- [![DogmaSolutions.PrimitiveTypes on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.PrimitiveTypes.svg)](https://www.nuget.org/packages/DogmaSolutions.PrimitiveTypes/) DogmaSolutions.PrimitiveTypes
- [![DogmaSolutions.Xml on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Xml.svg)](https://www.nuget.org/packages/DogmaSolutions.Xml/) DogmaSolutions.Xml

# Low-level utils
- [![DogmaSolutions.Statistics on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Statistics.svg)](https://www.nuget.org/packages/DogmaSolutions.Statistics/) DogmaSolutions.Statistics
- [![DogmaSolutions.Tasking on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Tasking.svg)](https://www.nuget.org/packages/DogmaSolutions.Tasking/) DogmaSolutions.Tasking
- [![DogmaSolutions.I18n on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.I18n.svg)](https://www.nuget.org/packages/DogmaSolutions.I18n/) DogmaSolutions.I18n
- [![DogmaSolutions.ErrorsHandling on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.ErrorsHandling.svg)](https://www.nuget.org/packages/DogmaSolutions.ErrorsHandling/) DogmaSolutions.ErrorsHandling
- [![DogmaSolutions.FileSystem on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.FileSystem.svg)](https://www.nuget.org/packages/DogmaSolutions.FileSystem/) DogmaSolutions.FileSystem
- [![DogmaSolutions.Networking on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Networking.svg)](https://www.nuget.org/packages/DogmaSolutions.Networking/) DogmaSolutions.Networking

## Reflection
- [![DogmaSolutions.Reflection on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Reflection.svg)](https://www.nuget.org/packages/DogmaSolutions.Reflection/) DogmaSolutions.Reflection
- [![DogmaSolutions.Reflection.Discovery on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Reflection.Discovery.svg)](https://www.nuget.org/packages/DogmaSolutions.Reflection.Discovery/) DogmaSolutions.Reflection.Discovery


## Design abstractions and Design Patterns
- [![DogmaSolutions.DataContracts on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.DataContracts.svg)](https://www.nuget.org/packages/DogmaSolutions.DataContracts/) DogmaSolutions.DataContracts
- [![DogmaSolutions.DesignPatterns on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.DesignPatterns.svg)](https://www.nuget.org/packages/DogmaSolutions.DesignPatterns/) DogmaSolutions.DesignPatterns
- [![DogmaSolutions.StateMachines on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.StateMachines.svg)](https://www.nuget.org/packages/DogmaSolutions.StateMachines/) DogmaSolutions.StateMachines
- [![DogmaSolutions.Services on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Services.svg)](https://www.nuget.org/packages/DogmaSolutions.Services/) DogmaSolutions.Services
- [![DogmaSolutions.Services.Serialization on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Services.Serialization.svg)](https://www.nuget.org/packages/DogmaSolutions.Services.Serialization/) DogmaSolutions.Services.Serialization

## Industrial automation and system integration
- [![DogmaSolutions.Devices on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Devices.svg)](https://www.nuget.org/packages/DogmaSolutions.Devices/) DogmaSolutions.Devices
- [![DogmaSolutions.Devices.I40 on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Devices.I40.svg)](https://www.nuget.org/packages/DogmaSolutions.Devices.I40/) DogmaSolutions.Devices.I40

**IBH devices**
- [![DogmaSolutions.Devices.Ibh on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Devices.Ibh.svg)](https://www.nuget.org/packages/DogmaSolutions.Devices.Ibh/) DogmaSolutions.Devices.Ibh
- [![DogmaSolutions.Devices.Ibh.I40 on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Devices.Ibh.I40.svg)](https://www.nuget.org/packages/DogmaSolutions.Devices.Ibh.I40/) DogmaSolutions.Devices.Ibh.I40

**Siemens devices**
- [![DogmaSolutions.Devices.Siemens on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Devices.Siemens.svg)](https://www.nuget.org/packages/DogmaSolutions.Devices.Siemens/) DogmaSolutions.Devices.Siemens
- [![DogmaSolutions.Devices.Siemens.I40 on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Devices.Siemens.I40.svg)](https://www.nuget.org/packages/DogmaSolutions.Devices.Siemens.I40/) DogmaSolutions.Devices.Siemens.I40

**OPC-UA-abled devices**
- [![DogmaSolutions.Devices.Opc.Ua on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Devices.Opc.Ua.svg)](https://www.nuget.org/packages/DogmaSolutions.Devices.Opc.Ua/) DogmaSolutions.Devices.Opc.Ua
- [![DogmaSolutions.Devices.Opc.Ua.Abstractions on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Devices.Opc.Ua.Abstractions.svg)](https://www.nuget.org/packages/DogmaSolutions.Devices.Opc.Ua.Abstractions/) DogmaSolutions.Devices.Opc.Ua.Abstractions

**OPC-UA integration**
- [![DogmaSolutions.Opc.Ua.Client on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Opc.Ua.Client.svg)](https://www.nuget.org/packages/DogmaSolutions.Opc.Ua.Client/) DogmaSolutions.Opc.Ua.Client
- [![DogmaSolutions.Opc.Ua.Server on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Opc.Ua.Server.svg)](https://www.nuget.org/packages/DogmaSolutions.Opc.Ua.Server/) DogmaSolutions.Opc.Ua.Server
- [![DogmaSolutions.Opc.Ua.Server.Abstractions on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Opc.Ua.Server.Abstractions.svg)](https://www.nuget.org/packages/DogmaSolutions.Opc.Ua.Server.Abstractions/) DogmaSolutions.Opc.Ua.Server.Abstractions
- [![DogmaSolutions.Opc.Ua.Server.Hosting on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Opc.Ua.Server.Hosting.svg)](https://www.nuget.org/packages/DogmaSolutions.Opc.Ua.Server.Hosting/) DogmaSolutions.Opc.Ua.Server.Hosting
- [![DogmaSolutions.Opc.Ua.Server.Hosting.Abstractions on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Opc.Ua.Server.Hosting.Abstractions.svg)](https://www.nuget.org/packages/DogmaSolutions.Opc.Ua.Server.Hosting.Abstractions/) DogmaSolutions.Opc.Ua.Server.Hosting.Abstractions


## Media
- [![DogmaSolutions.Drawing on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Drawing.svg)](https://www.nuget.org/packages/DogmaSolutions.Drawing/) DogmaSolutions.Drawing
- [![DogmaSolutions.Mjpeg on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Mjpeg.svg)](https://www.nuget.org/packages/DogmaSolutions.Mjpeg/) DogmaSolutions.Mjpeg

## Data, database and entities
- [![DogmaSolutions.Data on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Data.svg)](https://www.nuget.org/packages/DogmaSolutions.Data/) DogmaSolutions.Data
- [![DogmaSolutions.Data.Materialization on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Data.Materialization.svg)](https://www.nuget.org/packages/DogmaSolutions.Data.Materialization/) DogmaSolutions.Data.Materialization
- [![DogmaSolutions.Data.Sql on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Data.Sql.svg)](https://www.nuget.org/packages/DogmaSolutions.Data.Sql/) DogmaSolutions.Data.Sql
- [![DogmaSolutions.Entities.Contracts on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Entities.Contracts.svg)](https://www.nuget.org/packages/DogmaSolutions.Entities.Contracts/) DogmaSolutions.Entities.Contracts
- [![DogmaSolutions.EntityFrameworkCore.AspNetCore on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.EntityFrameworkCore.AspNetCore.svg)](https://www.nuget.org/packages/DogmaSolutions.EntityFrameworkCore.AspNetCore/) DogmaSolutions.EntityFrameworkCore.AspNetCore
- [![DogmaSolutions.EntityFrameworkCore.Auditing on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.EntityFrameworkCore.Auditing.svg)](https://www.nuget.org/packages/DogmaSolutions.EntityFrameworkCore.Auditing/) DogmaSolutions.EntityFrameworkCore.Auditing
- [![DogmaSolutions.EntityFrameworkCore.Contracts on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.EntityFrameworkCore.Contracts.svg)](https://www.nuget.org/packages/DogmaSolutions.EntityFrameworkCore.Contracts/) DogmaSolutions.EntityFrameworkCore.Contracts
- [![DogmaSolutions.EntityFrameworkCore.Secured on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.EntityFrameworkCore.Secured.svg)](https://www.nuget.org/packages/DogmaSolutions.EntityFrameworkCore.Secured/) DogmaSolutions.EntityFrameworkCore.Secured
- [![DogmaSolutions.EntityFrameworkCore.Unsecured on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.EntityFrameworkCore.Unsecured.svg)](https://www.nuget.org/packages/DogmaSolutions.EntityFrameworkCore.Unsecured/) DogmaSolutions.EntityFrameworkCore.Unsecured
- [![DogmaSolutions.EntityFrameworkCore.Utils on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.EntityFrameworkCore.Utils.svg)](https://www.nuget.org/packages/DogmaSolutions.EntityFrameworkCore.Utils/) DogmaSolutions.EntityFrameworkCore.Utils
- [![DogmaSolutions.EntityFrameworkCore.Encryption on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.EntityFrameworkCore.Encryption.svg)](https://www.nuget.org/packages/DogmaSolutions.EntityFrameworkCore.Encryption/) DogmaSolutions.EntityFrameworkCore.Encryption
- [![DogmaSolutions.EntityFrameworkCore.Encryption.Abstractions on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.EntityFrameworkCore.Encryption.Abstractions.svg)](https://www.nuget.org/packages/DogmaSolutions.EntityFrameworkCore.Encryption.Abstractions/) DogmaSolutions.EntityFrameworkCore.Encryption.Abstractions
- [![DogmaSolutions.SqlServer.LocalDb on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.SqlServer.LocalDb.svg)](https://www.nuget.org/packages/DogmaSolutions.SqlServer.LocalDb/) DogmaSolutions.SqlServer.LocalDb

## Plugins and extensibility
- [![DogmaSolutions.Extensibility on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Extensibility.svg)](https://www.nuget.org/packages/DogmaSolutions.Extensibility/) DogmaSolutions.Extensibility
- [![DogmaSolutions.Extensibility.HostedEnvironment on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Extensibility.HostedEnvironment.svg)](https://www.nuget.org/packages/DogmaSolutions.Extensibility.HostedEnvironment/) DogmaSolutions.Extensibility.HostedEnvironment

## Logging
- [![DogmaSolutions.Log4NetExtensions on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Log4NetExtensions.svg)](https://www.nuget.org/packages/DogmaSolutions.Log4NetExtensions/) DogmaSolutions.Log4NetExtensions
- [![DogmaSolutions.MicrosoftLoggingExtensions on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.MicrosoftLoggingExtensions.svg)](https://www.nuget.org/packages/DogmaSolutions.MicrosoftLoggingExtensions/) DogmaSolutions.MicrosoftLoggingExtensions

- [![DogmaSolutions.SlidingWindowLogger on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.SlidingWindowLogger.svg)](https://www.nuget.org/packages/DogmaSolutions.SlidingWindowLogger/) DogmaSolutions.SlidingWindowLogger

## Validation
- [![DogmaSolutions.Validation on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Validation.svg)](https://www.nuget.org/packages/DogmaSolutions.Validation/) DogmaSolutions.Validation

## Automated testing
- [![DogmaSolutions.Tests on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Tests.svg)](https://www.nuget.org/packages/DogmaSolutions.Tests/) DogmaSolutions.Tests

## Anagraphics models
- [![DogmaSolutions.Anagraphics on NuGet](https://img.shields.io/nuget/v/DogmaSolutions.Anagraphics.svg)](https://www.nuget.org/packages/DogmaSolutions.Anagraphics/) DogmaSolutions.Anagraphics

---

# License
All packages of the "Foundation" project are released under the [MIT License](https://opensource.org/license/mit).
