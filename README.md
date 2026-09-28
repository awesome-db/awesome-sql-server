# Awesome SQL Server [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Relational database management system from Microsoft, running on Windows, Linux, containers, and Azure.

**Disclaimer:** This list is maintained by the [Beekeeper Studio](https://github.com/beekeeper-studio) team. Beekeeper Studio is an easy to use database manager for SQL Server and 12+ other databases. Our goal is to keep this list impartial. We'd love other outside maintainers to join the org to help make that happen.

## Contents

- [Database GUIs and Managers](#database-guis-and-managers)
- [Add-ins and Extensions](#add-ins-and-extensions)
- [Command-line Tools](#command-line-tools)
- [Administration and Maintenance](#administration-and-maintenance)
- [Monitoring and Performance](#monitoring-and-performance)
- [Schema Migration and Version Control](#schema-migration-and-version-control)
- [Testing](#testing)
- [Drivers and Client Libraries](#drivers-and-client-libraries)
- [Local Development](#local-development)
- [Sample Databases](#sample-databases)
- [Learning Resources](#learning-resources)
- [Community](#community)

## Database GUIs and Managers

Desktop and web applications for browsing, querying, and managing SQL Server databases.

- [Beekeeper Studio](https://github.com/beekeeper-studio/beekeeper-studio) - Cross-platform SQL editor and database manager with an open source community edition and a commercial edition.
- [DataGrip](https://www.jetbrains.com/datagrip/) - JetBrains' commercial database IDE with code completion, refactoring, and version control integration.
- [DBeaver](https://github.com/dbeaver/dbeaver) - Free, open source, cross-platform universal database tool, with a commercial edition for extra features.
- [dbForge Studio for SQL Server](https://www.devart.com/dbforge/sql/studio/) - Commercial Windows IDE with T-SQL debugging, schema and data comparison, and database design tools.
- [DbGate](https://github.com/dbgate/dbgate) - Open source, cross-platform database manager that runs as a desktop app or in the browser.
- [DbVisualizer](https://www.dbvis.com/) - Cross-platform universal database tool with free and commercial editions.
- [HeidiSQL](https://github.com/HeidiSQL/HeidiSQL) - Free, open source Windows client for SQL Server, MySQL, PostgreSQL, and SQLite.
- [LINQPad](https://www.linqpad.net/) - Windows scratchpad for querying SQL Server with SQL, LINQ, or C#.
- [Navicat for SQL Server](https://www.navicat.com/en/products/navicat-for-sql-server) - Commercial cross-platform GUI with data modeling, transfer, and synchronization tools.
- [SQL Server Management Studio (SSMS)](https://learn.microsoft.com/sql/ssms/download-sql-server-management-studio-ssms) - Microsoft's free, official Windows tool for managing and querying SQL Server.
- [SQLPro for MSSQL](https://www.macsqlclient.com/) - Commercial native SQL Server client for macOS, iOS, Android, and Windows.
- [TablePlus](https://tableplus.com/) - Native, cross-platform GUI for SQL Server and other databases, with a free tier.
- [Toad for SQL Server](https://www.quest.com/products/toad-for-sql-server/) - Quest's commercial Windows tool for development, administration, and performance tuning.

## Add-ins and Extensions

Add-ins and extensions that bring SQL Server features into SQL Server Management Studio (SSMS), Visual Studio, VS Code, and Excel.

- [dbForge SQL Complete](https://www.devart.com/dbforge/sql/sqlcomplete/) - SSMS and Visual Studio add-in for code completion, formatting, and refactoring, with a free Express edition.
- [SQL Prompt](https://www.red-gate.com/products/sql-prompt/) - Redgate's commercial SSMS and Visual Studio add-in for code completion, formatting, and refactoring.
- [SQL Search](https://www.red-gate.com/products/sql-search/) - Free Redgate add-in for finding text and object references across databases from inside SSMS.
- [SQL Server (mssql) for VS Code](https://github.com/microsoft/vscode-mssql) - Microsoft's official VS Code extension for querying and managing SQL Server and Azure SQL, and the recommended replacement for the retired Azure Data Studio.
- [SQL Server Data Tools (SSDT)](https://learn.microsoft.com/sql/ssdt/download-sql-server-data-tools-ssdt) - Visual Studio tooling for database projects, schema compare, and DACPAC deployment.
- [SQL Shades](https://sqlshades.com/) - SSMS add-in that adds dark mode and other themes, branding overlays, and connected-server alerts.
- [SQL Source Control](https://www.red-gate.com/products/sql-source-control/) - Redgate's commercial SSMS add-in that links databases to Git, Subversion, TFS, and other version control systems.
- [SQL Spreads](https://sqlspreads.com/) - Excel add-in for editing and updating SQL Server data directly from spreadsheets.
- [SQLTools](https://github.com/mtxr/vscode-sqltools) - Open source VS Code extension for browsing and querying many databases, including SQL Server through its MSSQL driver.
- [SSMS Schema Folders](https://github.com/nicon/SsmsSchemaFolders) - Open source SSMS add-in that groups Object Explorer items into folders by schema.
- [VersionSQL](https://www.versionsql.com/) - SSMS add-in that commits schema, security, Agent jobs, and static data to Git, Subversion, or TFVC.

## Command-line Tools

- [bcp](https://learn.microsoft.com/sql/tools/bcp-utility) - Bulk copy utility for importing and exporting large volumes of data.
- [sqlcmd](https://github.com/microsoft/go-sqlcmd) - Microsoft's cross-platform CLI for running T-SQL, which can also spin up local SQL Server containers with `sqlcmd create mssql`.
- [sqlfluff](https://github.com/sqlfluff/sqlfluff) - SQL linter and auto-formatter with a T-SQL dialect.
- [SqlPackage](https://learn.microsoft.com/sql/tools/sqlpackage/sqlpackage) - Cross-platform CLI for extracting, publishing, importing, and exporting DACPAC and BACPAC files.
- [usql](https://github.com/xo/usql) - Universal command-line client for SQL databases, including SQL Server.

## Administration and Maintenance

- [dbachecks](https://github.com/dataplat/dbachecks) - PowerShell module that validates SQL Server environments against configurable best-practice checks.
- [dbatools](https://github.com/dataplat/dbatools) - PowerShell module with hundreds of commands for automating SQL Server administration, migrations, and best practices.
- [SQL Server Maintenance Solution](https://ola.hallengren.com/) - Ola Hallengren's free scripts for backups, integrity checks, and index and statistics maintenance.
- [SQL Server Migration Assistant (SSMA)](https://learn.microsoft.com/sql/ssma/sql-server-migration-assistant) - Microsoft's free tool for migrating Oracle, MySQL, DB2, SAP ASE, and Access databases to SQL Server.

## Monitoring and Performance

- [Darling Data scripts](https://github.com/erikdarlingdata/DarlingData) - Erik Darling's free stored procedures for performance triage, including sp_PressureDetector, sp_HumanEvents, and sp_QuickieStore.
- [DBA Dash](https://github.com/trimble-oss/dba-dash) - Free, open source monitoring tool with performance dashboards, configuration tracking, and alerting.
- [First Responder Kit](https://github.com/BrentOzarULTD/SQL-Server-First-Responder-Kit) - Brent Ozar's free health check and performance scripts, including sp_Blitz, sp_BlitzCache, and sp_BlitzIndex.
- [Glenn Berry's Diagnostic Queries](https://glennsqlperformance.com/resources/) - Regularly updated diagnostic information queries for every supported SQL Server version.
- [Paste The Plan](https://www.brentozar.com/pastetheplan/) - Free site for sharing and viewing execution plans.
- [Plan Explorer](https://www.solarwinds.com/free-tools/plan-explorer) - Free SolarWinds tool for analyzing and visualizing execution plans.
- [sp_WhoIsActive](https://github.com/amachanic/sp_whoisactive) - Adam Machanic's stored procedure for seeing what is running on a server right now.
- [SQL Monitor](https://www.red-gate.com/products/sql-monitor/) - Redgate's commercial monitoring platform for SQL Server estates.
- [SQL Sentry](https://www.solarwinds.com/sql-sentry) - SolarWinds' commercial performance monitoring tool for SQL Server.
- [Statistics Parser](https://statisticsparser.com/) - Web tool that turns STATISTICS IO and STATISTICS TIME output into readable tables.

## Schema Migration and Version Control

- [Bytebase](https://github.com/bytebase/bytebase) - Database DevOps platform with schema migration workflows, SQL review, and a web-based SQL editor.
- [DacFx](https://github.com/microsoft/DacFx) - Microsoft's SDK-style SQL database projects and the DacFx library for building and deploying DACPACs cross-platform.
- [DbUp](https://github.com/DbUp/DbUp) - .NET library that tracks and runs SQL scripts to upgrade databases.
- [Flyway](https://github.com/flyway/flyway) - Version control and migrations for database schemas, with SQL Server support in the free Community edition.
- [grate](https://github.com/erikbra/grate) - Cross-platform, convention-based migration tool for SQL Server and other databases, and the successor to RoundhousE.
- [Liquibase](https://github.com/liquibase/liquibase) - Open source database change management with changelogs in SQL, XML, YAML, or JSON.

## Testing

- [SQLQueryStress](https://github.com/ErikEJ/SQLQueryStress) - Lightweight load-testing tool for running a query from many concurrent threads.
- [Testcontainers](https://testcontainers.com/modules/mssql/) - Throwaway SQL Server containers for integration tests, with modules for .NET, Java, Go, Node.js, Python, and more.
- [tSQLt](https://github.com/tSQLt-org/tSQLt) - Unit testing framework for SQL Server, written in T-SQL.

## Drivers and Client Libraries

Official and community drivers for connecting to SQL Server from your language of choice.

- [FreeTDS](https://www.freetds.org/) - Open source implementation of the TDS protocol with ODBC and CT-Library interfaces, and the base for several other drivers.
- [go-mssqldb](https://github.com/microsoft/go-mssqldb) - Microsoft-maintained pure Go driver for the `database/sql` package.
- [Microsoft Drivers for PHP for SQL Server](https://github.com/microsoft/msphpsql) - Official SQLSRV and PDO_SQLSRV extensions for PHP.
- [Microsoft JDBC Driver for SQL Server](https://github.com/microsoft/mssql-jdbc) - Official Type 4 JDBC driver for Java.
- [Microsoft ODBC Driver for SQL Server](https://learn.microsoft.com/sql/connect/odbc/microsoft-odbc-driver-for-sql-server) - Official ODBC driver for Windows, Linux, and macOS, used by many other language drivers.
- [Microsoft.Data.SqlClient](https://github.com/dotnet/SqlClient) - Official .NET data provider for SQL Server and Azure SQL.
- [mssql-python](https://github.com/microsoft/mssql-python) - Microsoft's official Python driver for SQL Server and Azure SQL.
- [node-mssql](https://github.com/tediousjs/node-mssql) - Node.js client that adds connection pooling, prepared statements, and promises on top of tedious.
- [pymssql](https://github.com/pymssql/pymssql) - Simple Python DB-API driver built on FreeTDS.
- [pyodbc](https://github.com/mkleehammer/pyodbc) - Python DB-API module for ODBC, and the most common way to reach SQL Server from Python.
- [tedious](https://github.com/tediousjs/tedious) - Pure JavaScript implementation of the TDS protocol for Node.js.
- [Tiberius](https://github.com/prisma/tiberius) - Async, native TDS client for Rust.
- [TinyTDS](https://github.com/rails-sqlserver/tiny_tds) - Ruby driver built on FreeTDS, used by the Rails SQL Server adapter.

## Local Development

- [SQL Server container images](https://learn.microsoft.com/sql/linux/quickstart-install-connect-docker) - Official Linux container images for running SQL Server with Docker or Podman.
- [SQL Server Developer Edition](https://www.microsoft.com/sql-server/sql-server-downloads) - Free, full-featured edition licensed for development and testing.
- [SQL Server Express LocalDB](https://learn.microsoft.com/sql/database-engine/configure-windows/sql-server-express-localdb) - Lightweight, on-demand SQL Server instance for developers on Windows.

## Sample Databases

- [AdventureWorks](https://learn.microsoft.com/sql/samples/adventureworks-install-configure) - Microsoft's classic OLTP and data warehouse sample databases.
- [Chinook](https://github.com/lerocha/chinook-database) - Sample digital media store database with scripts for SQL Server and other engines.
- [Northwind and pubs](https://github.com/microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs) - Scripts for the classic Northwind and pubs sample databases.
- [SQL Server samples](https://github.com/microsoft/sql-server-samples) - Microsoft's official repository of sample databases, scripts, and applications.
- [Stack Overflow database](https://www.brentozar.com/archive/2015/10/how-to-download-the-stack-overflow-database-via-bittorrent/) - Brent Ozar's SQL Server export of the Stack Overflow data dump, ideal for realistic performance testing.
- [WideWorldImporters](https://learn.microsoft.com/sql/samples/wide-world-importers-what-is) - Microsoft's newer sample database showcasing temporal tables, JSON, columnstore, and other modern features.

## Learning Resources

- [Brent Ozar Unlimited](https://www.brentozar.com/blog/) - Blog, free scripts, and training focused on SQL Server performance tuning.
- [Darling Data blog](https://erikdarling.com/) - Erik Darling's articles on query tuning and SQL Server performance.
- [Microsoft SQL Server Blog](https://www.microsoft.com/en-us/sql-server/blog/) - Official product blog with release announcements and feature deep dives.
- [MSSQLTips](https://www.mssqltips.com/) - Tips and tutorials on SQL Server administration, development, and business intelligence.
- [PASS Data Community Summit](https://passdatacommunitysummit.com/) - Annual conference for the Microsoft data platform community.
- [Simple Talk](https://www.red-gate.com/simple-talk/) - Redgate's technical articles on SQL Server development and administration.
- [SQL Server documentation](https://learn.microsoft.com/sql/sql-server/) - Official Microsoft documentation for the database engine, T-SQL, and tools.
- [SQL Server Execution Plans](https://www.red-gate.com/simple-talk/books/sql-server-execution-plans-third-edition-by-grant-fritchey/) - Grant Fritchey's free book on reading and tuning execution plans.
- [SQLBits](https://sqlbits.com/) - Large SQL Server and Microsoft data platform conference with free session recordings.
- [SQLServerCentral](https://www.sqlservercentral.com/) - Community site with articles, forums, and the Stairway tutorial series.
- [SQLskills](https://www.sqlskills.com/sql-server-resources/) - Paul Randal and Kimberly Tripp's blogs, whitepapers, and training on SQL Server internals.
- [Use The Index, Luke](https://use-the-index-luke.com/) - Guide to SQL indexing and tuning with SQL Server-specific notes.

## Community

- [Database Administrators Stack Exchange](https://dba.stackexchange.com/questions/tagged/sql-server) - Q&A site for database professionals, with an active sql-server tag.
- [r/SQLServer](https://www.reddit.com/r/SQLServer/) - Subreddit for SQL Server news and discussion.
- [SQL Server Community Slack](https://dbatools.io/slack/) - Slack workspace with channels for general help, dbatools, and other SQL Server topics.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/sql-server) - Questions tagged sql-server on Stack Overflow.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](contributing.md) first.
