---
title: ColumnMappings
---

# MySqlBulkCopy.ColumnMappings property

A collection of [`MySqlBulkCopyColumnMapping`](../../MySqlBulkCopyColumnMappingType/) objects. If the columns being copied from the data source line up one-to-one with the columns in the destination table then populating this collection is unnecessary. Otherwise, this should be filled with a collection of [`MySqlBulkCopyColumnMapping`](../../MySqlBulkCopyColumnMappingType/) objects specifying how source columns are to be mapped onto destination columns. If one column mapping is specified, then all must be specified.

```csharp
public List<MySqlBulkCopyColumnMapping> ColumnMappings { get; }
```

## See Also

* class [MySqlBulkCopyColumnMapping](../../MySqlBulkCopyColumnMappingType/)
* class [MySqlBulkCopy](../../MySqlBulkCopyType/)
* namespace [MySqlConnector](../../MySqlBulkCopyType/)
* assembly [MySqlConnector](../../../MySqlConnectorAssembly/)

<!-- DO NOT EDIT: generated by xmldocmd for MySqlConnector.dll -->