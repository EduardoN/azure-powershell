### Example 1: The Restore-AzSqlDatabase cmdlet restores a SQL database from a geo-redundant backup, a backup of a deleted database, a long term retention backup, or a point in time in a live database.
```powershell
PS C:\> Restore-AzSqlDatabase -Edition Standard -FromGeoBackup  -ResourceGroupName $Database.ResourceGroupName -ResourceId $Database.ResourceID -ServerName $Database.ServerName -ServiceObjectiveName S2 -TargetDatabaseName RestoredDatabase
```

