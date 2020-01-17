### Example 1: This command creates a sync group for an Azure SQL Database. "schema.json" is a file in the local disk. It contains the schema payload in json format. An example of the schema json is:
```powershell
PS C:\> New-AzSqlSyncGroup -ConflictResolutionPolicy HubWin -DatabaseCredential $credential -DatabaseName Database01 -IntervalInSeconds 100 -Name SyncGroup01 -ResourceGroupName ResourceGroup01 -ServerName Server01 -SyncDatabaseName syncDatabaseName01 -SyncDatabaseResourceGroupName syncDatabaseResourceGroup01 -SyncDatabaseServerName syncDatabaseServer01
```

