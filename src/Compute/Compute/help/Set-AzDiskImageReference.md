### Example 1: The first command creates a local disk object with size 10GB in Premium_LRS storage account type.  It also sets Windows OS type.
```powershell
PS C:\> Set-AzDiskImageReference -Disk $diskconfig -Id $image -Lun 0
```

