# DelegatingDbConnector class

Delegates to an inner connector.

```csharp
public class DelegatingDbConnector : DbConnector
```

## Public Members

| name | description |
| --- | --- |
| [DelegatingDbConnector](DelegatingDbConnector/DelegatingDbConnector.md)(…) | Creates an instance that delegates to the specified connector. |
| override [Connection](DelegatingDbConnector/Connection.md) { get; } |  |
| override [SqlSyntax](DelegatingDbConnector/SqlSyntax.md) { get; } |  |
| override [Transaction](DelegatingDbConnector/Transaction.md) { get; } |  |
| override [AttachTransaction](DelegatingDbConnector/AttachTransaction.md)(…) |  |
| override [BeginTransaction](DelegatingDbConnector/BeginTransaction.md)() |  |
| override [BeginTransaction](DelegatingDbConnector/BeginTransaction.md)(…) |  |
| override [BeginTransactionAsync](DelegatingDbConnector/BeginTransactionAsync.md)(…) |  (2 methods) |
| override [CommitTransaction](DelegatingDbConnector/CommitTransaction.md)() |  |
| override [CommitTransactionAsync](DelegatingDbConnector/CommitTransactionAsync.md)(…) |  |
| override [Dispose](DelegatingDbConnector/Dispose.md)() |  |
| override [DisposeAsync](DelegatingDbConnector/DisposeAsync.md)() |  |
| override [GetConnectionAsync](DelegatingDbConnector/GetConnectionAsync.md)(…) |  |
| override [OpenConnection](DelegatingDbConnector/OpenConnection.md)() |  |
| override [OpenConnectionAsync](DelegatingDbConnector/OpenConnectionAsync.md)(…) |  |
| override [ReleaseConnection](DelegatingDbConnector/ReleaseConnection.md)() |  |
| override [ReleaseConnectionAsync](DelegatingDbConnector/ReleaseConnectionAsync.md)() |  |
| override [RollbackTransaction](DelegatingDbConnector/RollbackTransaction.md)() |  |
| override [RollbackTransactionAsync](DelegatingDbConnector/RollbackTransactionAsync.md)(…) |  |

## Protected Members

| name | description |
| --- | --- |
| override [CommandCache](DelegatingDbConnector/CommandCache.md) { get; } |  |
| [Inner](DelegatingDbConnector/Inner.md) { get; } | The inner connector. |
| override [ProviderMethods](DelegatingDbConnector/ProviderMethods.md) { get; } |  |

## See Also

* class [DbConnector](./DbConnector.md)
* namespace [Faithlife.Data](../Faithlife.Data.md)
* [DelegatingDbConnector.cs](https://github.com/Faithlife/FaithlifeData/tree/master/src/Faithlife.Data/DelegatingDbConnector.cs)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Data.dll -->
