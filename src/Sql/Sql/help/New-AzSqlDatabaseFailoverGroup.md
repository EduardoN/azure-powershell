### Example 1: Creates a new Azure SQL Database Failover Group for the specified servers.
```powershell
PS C:\> New-AzSqlDatabaseFailoverGroup -FailoverGroupName fg -FailoverPolicy Automatic -GracePeriodWithDataLossHours 1 -PartnerResourceGroupName rg2 -PartnerServerName secondaryserver -ResourceGroupName rg -ServerName primaryserver
```

