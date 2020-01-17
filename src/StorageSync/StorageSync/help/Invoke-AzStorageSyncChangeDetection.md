### Example 1: In this example, change detection is run for the "Examples" directory and will recursively detect changes in subdirectories. 
```powershell
PS C:\> Invoke-AzStorageSyncChangeDetection -DirectoryPath Examples -Name myCloudEndpointName -Recursive  -ResourceGroupName myResourceGroup -StorageSyncServiceName myStorageSyncServiceName -SyncGroupName mySyncGroupName
```

