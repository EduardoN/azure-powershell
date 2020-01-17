### Example 1: The Add-AzLogProfile cmdlet creates a log profile.
```powershell
PS C:\> Add-AzLogProfile -Location Global,West US -Name ExportLogProfile -RetentionInDays {RetentionInDays} -StorageAccountId /subscriptions/40gpe80s-9sb7-4f07-9042-b1b6a92ja9fk/resourceGroups/activitylogRG/providers/Microsoft.Storage/storageAccounts/activitylogstorageaccount
```

