### Example 1: The New-AzSqlDatabaseCopy cmdlet creates a copy of an Azure SQL Database that uses the
```powershell
PS C:\> New-AzSqlDatabaseCopy -CopyDatabaseName {CopyDatabaseName} -CopyResourceGroupName {CopyResourceGroupName} -CopyServerName {CopyServerName} -DatabaseName Database01 -ResourceGroupName MyResourceGroup -ServerName s1
```

