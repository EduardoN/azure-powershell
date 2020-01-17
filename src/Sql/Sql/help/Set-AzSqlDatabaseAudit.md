### Example 1: The Set-AzSqlDatabaseAudit cmdlet changes the auditing settings of an Azure SQL database.
```powershell
PS C:\> Set-AzSqlDatabaseAudit -DatabaseName Database01 -LogAnalyticsTargetState Enabled -ResourceGroupName ResourceGroup01 -ServerName Server01 -WorkspaceResourceId /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/insights-integration/providers/Microsoft.OperationalInsights/workspaces/viruela2
```

