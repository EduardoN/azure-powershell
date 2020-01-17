### Example 1: The Set-AzSqlDatabaseSecondary cmdlet switches a secondary database to be primary in order to initiate failover.
```powershell
PS C:\> Set-AzSqlDatabaseSecondary -Failover  -PartnerResourceGroupName $primaryResourceGroupName
```

