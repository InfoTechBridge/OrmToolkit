# OrmToolkit

## Features

* Tiny, and absolutely no dependencies!
* Works with strictly undecorated POCOs, or attributed almost-POCOs.
* Easy to configure and includes [fluent configuration] out of the box.
* Helper methods for Insert/Delete/Update/Save and IsNew
* Paged requests automatically work out total record count and fetch a specific page.
* Easy transaction support.
* Better parameter replacement support, including grabbing named parameters from object properties.
* Great performance by eliminating Linq and fast property assignment with DynamicMethod generation.
* The query language is good ole SQL.
* Includes a low friction SQL builder class that makes writing inline SQL *much* easier.
* Includes T4 templates to automatically generate POCO classes for you. (V5)
* Hooks for logging exceptions, installing value converters and mapping columns to properties without attributes.
* Works with SQL Server, SQL Server CE, MS Access, SQLite, MySQL, MariaDB, Firebird, and PostgreSQL. (Oracle supported but does not have integration tests).
* Works under Net Standard 2.0, .NET 4.0/4.5+ or Mono 2.8 and later.
* Has [Xunit] unit tests.
* Has supported DBs integration tests.
* OpenSource (MIT License or Apache 2.0)

## Installation

OrmToolkit Nuget packages are available in nuget.org.
These packages contain both .NET Framework v4.5 and .NET Standard 2.0 versions and supports both .NET Framework and .NET Core projects.

* **SQL Server**
```
Install-Package ORMToolkit.Core
```

* **Oracle ODP** - Needs Oracle Client
```
Install-Package ORMToolkit.OracleOdp
```

* **Oracle ODP Managed**
```
Install-Package ORMToolkit.OracleOdpManaged
```

