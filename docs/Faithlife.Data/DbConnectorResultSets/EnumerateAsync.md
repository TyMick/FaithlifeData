# DbConnectorResultSets.EnumerateAsync&lt;T&gt; method (1 of 2)

Reads a result set, reading one record at a time and converting it to the specified type.

```csharp
public IAsyncEnumerable<T> EnumerateAsync<T>(CancellationToken cancellationToken = default)
```

## See Also

* method [Enumerate&lt;T&gt;](./Enumerate.md)
* class [DbConnectorResultSets](../DbConnectorResultSets.md)
* namespace [Faithlife.Data](../../Faithlife.Data.md)

---

# DbConnectorResultSets.EnumerateAsync&lt;T&gt; method (2 of 2)

Reads a result set, reading one record at a time and converting it to the specified type with the specified delegate.

```csharp
public IAsyncEnumerable<T> EnumerateAsync<T>(Func<IDataRecord, T> map, 
    CancellationToken cancellationToken = default)
```

## See Also

* method [Enumerate&lt;T&gt;](./Enumerate.md)
* class [DbConnectorResultSets](../DbConnectorResultSets.md)
* namespace [Faithlife.Data](../../Faithlife.Data.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Data.dll -->
