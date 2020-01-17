### Example 1: The Invoke-AzHDInsightHiveJob cmdlet submits a Hive query to an Azure HDInsight cluster and retrieves query results in one operation.
```powershell
PS C:\> Invoke-AzHDInsightHiveJob -DefaultContainer {DefaultContainer} -DefaultStorageAccountKey $storageAccountKey -DefaultStorageAccountName {DefaultStorageAccountName} -Query $query
```

