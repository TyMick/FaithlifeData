# DbConnectorCommand.QuerySingleOrDefaultAsync&lt;T&gt; method (1 of 2)

Executes the query, converting the first record to the specified type.

```csharp
public ValueTask<T> QuerySingleOrDefaultAsync<T>(CancellationToken cancellationToken = default)
```

## Remarks

Returns `default(T)` if no records are returned. Throws InvalidOperationException if more than one record is returned.

## See Also

* method [QuerySingleOrDefault&lt;T&gt;](./QuerySingleOrDefault.md)
* struct [DbConnectorCommand](../DbConnectorCommand.md)
* namespace [Faithlife.Data](../../Faithlife.Data.md)

---

# DbConnectorCommand.QuerySingleOrDefaultAsync&lt;T&gt; method (2 of 2)

Executes the query, converting the first record to the specified type with the specified delegate.

```csharp
public ValueTask<T> QuerySingleOrDefaultAsync<T>(Func<IDataRecord, T> map, 
    CancellationToken cancellationToken = default)
```

## Remarks

Returns `default(T)` if no records are returned. Throws InvalidOperationException if more than one record is returned.

## See Also

* method [QuerySingleOrDefault&lt;T&gt;](./QuerySingleOrDefault.md)
* struct [DbConnectorCommand](../DbConnectorCommand.md)
* namespace [Faithlife.Data](../../Faithlife.Data.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Data.dll -->
