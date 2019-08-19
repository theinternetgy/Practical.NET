## Visual Studio Extensions:
- [EF Core Power Tools](https://marketplace.visualstudio.com/items?itemName=ErikEJ.EFCorePowerTools)

## Nuget Packages:
- Microsoft.EntityFrameworkCore
- Microsoft.EntityFrameworkCore.Relational
- Microsoft.EntityFrameworkCore.SqlServer
- ...

## Migrations:
- add-migration 
- remove-migration
- update-database
- script-migration

## Mappings:
- One-to-many
- Many-to-many
- One-to-one
- [Shadow Properties](https://docs.microsoft.com/en-us/ef/core/modeling/shadow-properties)
- [Owned Types](https://docs.microsoft.com/en-us/ef/core/modeling/owned-entities)
- User-defined Functions
- Views ([Query Types](https://docs.microsoft.com/en-us/ef/core/modeling/query-types))
- [Data Seeding (HasData)](https://docs.microsoft.com/en-us/ef/core/modeling/data-seeding)
- [Value Converters](https://docs.microsoft.com/en-us/ef/core/modeling/value-conversions)

## Common SQL Functions:
- EF.Functions.Like

## Querying Data:
- [Query Tags](https://docs.microsoft.com/en-us/ef/core/querying/tags)
- [Views (Query Types)](https://docs.microsoft.com/en-us/ef/core/modeling/query-types)
- [Raw SQL Queries (FromSql)](https://docs.microsoft.com/en-us/ef/core/querying/raw-sql)
- [Loading Related Data](https://docs.microsoft.com/en-us/ef/core/querying/related-data)
  + Eager loading
  + Explicit loading
  + Lazy loading with and without Proxies

## Saving Data:
- [Transactions](https://docs.microsoft.com/en-us/ef/core/saving/transactions)
- [MinBatchSize](https://docs.microsoft.com/en-us/dotnet/api/microsoft.entityframeworkcore.infrastructure.relationaloptionsextension.minbatchsize?view=efcore-2.1)
- [MaxBatchSize](https://docs.microsoft.com/en-us/dotnet/api/microsoft.entityframeworkcore.infrastructure.relationaloptionsextension.maxbatchsize?view=efcore-2.1)

## Logging & Tracking Events:
- [Logging](https://docs.microsoft.com/en-us/ef/core/miscellaneous/logging)
- [ChangeTracker.StateChanged Event](https://docs.microsoft.com/en-us/dotnet/api/microsoft.entityframeworkcore.changetracking.changetracker.statechanged?view=efcore-2.1)
- [ChangeTracker.Tracked Event](https://docs.microsoft.com/en-us/dotnet/api/microsoft.entityframeworkcore.changetracking.changetracker.tracked?view=efcore-2.1)

## Code Analysis:
- Microsoft.EntityFrameworkCore.Analyzers

## Notes:
- GroupBy Issues