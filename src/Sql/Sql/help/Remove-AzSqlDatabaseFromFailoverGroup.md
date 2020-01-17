### Example 1: Removes one or more databases from the specified Azure SQL Database Failover Group. The databases and replication relationships are left intact, but they will no longer be accessible through the Failover Group endpoints.
```powershell
PS C:\> Remove-AzSqlDatabaseFromFailoverGroup -Database $databases -FailoverGroupName fg -Force  -ResourceGroupName MyResourceGroup -ServerName s1
```

