### Example 1: The first command creates a local empty snapshot object with size 5GB in Standard_LRS storage account type.  It also sets Windows OS type and enables encryption settings.
```powershell
PS C:\> New-AzSnapshot -ResourceGroupName ResourceGroup01 -Snapshot $snapshotconfig -SnapshotName Snapshot01
```

