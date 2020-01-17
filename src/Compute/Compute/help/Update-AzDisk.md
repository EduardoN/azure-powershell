### Example 1: The first command creates a local empty disk update object with size 10GB in Premium_LRS storage account type.  It also sets Windows OS type and enables encryption settings.
```powershell
PS C:\> Update-AzDisk -DiskName Disk01 -DiskUpdate $diskupdateconfig -ResourceGroupName ResourceGroup01
```

