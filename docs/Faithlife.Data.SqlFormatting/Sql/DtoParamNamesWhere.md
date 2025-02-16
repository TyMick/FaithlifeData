# Sql.DtoParamNamesWhere method (1 of 6)

Returns a comma-delimited list of named parameters for the properties of the specified DTO whose names match the specified filter.

```csharp
public static Sql DtoParamNamesWhere(Type type, Func<string, bool> filter)
```

## Remarks

The parameter names are the same as those used by the `Dto` methods of [`DbParameters`](../../Faithlife.Data/DbParameters.md).

## See Also

* class [Sql](../Sql.md)
* namespace [Faithlife.Data.SqlFormatting](../../Faithlife.Data.md)

---

# Sql.DtoParamNamesWhere method (2 of 6)

Returns a comma-delimited list of named parameters for the properties of the specified DTO whose names match the specified filter.

```csharp
public static Sql DtoParamNamesWhere(Type type, Func<string, string> name, 
    Func<string, bool> filter)
```

## Remarks

The parameter names are the same as those used by the `Dto` methods of [`DbParameters`](../../Faithlife.Data/DbParameters.md).

## See Also

* class [Sql](../Sql.md)
* namespace [Faithlife.Data.SqlFormatting](../../Faithlife.Data.md)

---

# Sql.DtoParamNamesWhere method (3 of 6)

Returns a comma-delimited list of named parameters for the properties of the specified DTO whose names match the specified filter.

```csharp
public static Sql DtoParamNamesWhere(Type type, string name, Func<string, bool> filter)
```

## Remarks

The parameter names are the same as those used by the `Dto` methods of [`DbParameters`](../../Faithlife.Data/DbParameters.md).

## See Also

* class [Sql](../Sql.md)
* namespace [Faithlife.Data.SqlFormatting](../../Faithlife.Data.md)

---

# Sql.DtoParamNamesWhere&lt;T&gt; method (4 of 6)

Returns a comma-delimited list of named parameters for the properties of the specified DTO whose names match the specified filter.

```csharp
public static Sql DtoParamNamesWhere<T>(Func<string, bool> filter)
```

## Remarks

The parameter names are the same as those used by the `Dto` methods of [`DbParameters`](../../Faithlife.Data/DbParameters.md).

## See Also

* class [Sql](../Sql.md)
* namespace [Faithlife.Data.SqlFormatting](../../Faithlife.Data.md)

---

# Sql.DtoParamNamesWhere&lt;T&gt; method (5 of 6)

Returns a comma-delimited list of named parameters for the properties of the specified DTO whose names match the specified filter.

```csharp
public static Sql DtoParamNamesWhere<T>(Func<string, string> name, Func<string, bool> filter)
```

## Remarks

The parameter names are the same as those used by the `Dto` methods of [`DbParameters`](../../Faithlife.Data/DbParameters.md).

## See Also

* class [Sql](../Sql.md)
* namespace [Faithlife.Data.SqlFormatting](../../Faithlife.Data.md)

---

# Sql.DtoParamNamesWhere&lt;T&gt; method (6 of 6)

Returns a comma-delimited list of named parameters for the properties of the specified DTO whose names match the specified filter.

```csharp
public static Sql DtoParamNamesWhere<T>(string name, Func<string, bool> filter)
```

## Remarks

The parameter names are the same as those used by the `Dto` methods of [`DbParameters`](../../Faithlife.Data/DbParameters.md).

## See Also

* class [Sql](../Sql.md)
* namespace [Faithlife.Data.SqlFormatting](../../Faithlife.Data.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Data.dll -->
