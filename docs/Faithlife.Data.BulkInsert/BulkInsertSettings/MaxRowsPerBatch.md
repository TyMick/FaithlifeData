# BulkInsertSettings.MaxRowsPerBatch property

Specifies the maximum number of rows to insert per batch.

```csharp
public int? MaxRowsPerBatch { get; set; }
```

## Remarks

If neither [`MaxParametersPerBatch`](./MaxParametersPerBatch.md) nor `MaxRowsPerBatch` are specified, the maximum number of parameters is 999.

## See Also

* class [BulkInsertSettings](../BulkInsertSettings.md)
* namespace [Faithlife.Data.BulkInsert](../../Faithlife.Data.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Data.dll -->
