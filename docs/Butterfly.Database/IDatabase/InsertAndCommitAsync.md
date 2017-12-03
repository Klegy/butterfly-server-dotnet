# IDatabase.InsertAndCommitAsync method

Executes the INSERT statement as a single transaction (the INSERT statement may contain vars like @name specified in *vars*)

```csharp
public Task<object> InsertAndCommitAsync(string insertStatement, object vars, bool ignoreIfDuplicate = false)
```

| parameter | description |
| --- | --- |
| insertStatement |  |
| vars |  |
| ignoreIfDuplicate |  |

## See Also

* interface [IDatabase](../IDatabase.md)
* namespace [Butterfly.Database](../../Butterfly.Database.md)

<!-- DO NOT EDIT: generated by xmldocmd for Butterfly.Database.dll -->