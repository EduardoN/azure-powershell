### Example 1: The Restore-AzSqlInstanceDatabase cmdlet restores an instance database from a geo-redundant backup or a point in time in a live database.
```powershell
PS C:\> Restore-AzSqlInstanceDatabase -FromPointInTimeBackup  -InstanceName managedInstance1 -Name Database01 -PointInTime UTCDateTime -ResourceGroupName ResourceGroup01 -TargetInstanceDatabaseName Database01_restored
```

