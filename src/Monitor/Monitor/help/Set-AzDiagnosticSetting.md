### Example 1: The Set-AzDiagnosticSetting cmdlet enables or disables each time grain and log category for the particular resource.
```powershell
PS C:\> Set-AzDiagnosticSetting -Category Category1,Category2 -Enabled $False -MetricCategory MetricCategory1,MetricCategory2 -Name MySetting -ResourceId Resource01 -RetentionEnabled False -RetentionInDays {RetentionInDays} -StorageAccountId /subscriptions/40gpe80s-9sb7-4f07-9042-b1b6a92ja9fk/resourceGroups/activitylogRG/providers/Microsoft.Storage/storageAccounts/activitylogstorageaccount
```

