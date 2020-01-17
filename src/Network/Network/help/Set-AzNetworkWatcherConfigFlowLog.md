### Example 1: The Set-AzNetworkWatcherConfigFlowLog configures flow logging for a target resource. 
```powershell
PS C:\> Set-AzNetworkWatcherConfigFlowLog -EnableFlowLog $true -EnableRetention False -NetworkWatcher $NW -RetentionInDays {RetentionInDays} -StorageAccountId $storageID -TargetResourceId $nsg.Id
```

