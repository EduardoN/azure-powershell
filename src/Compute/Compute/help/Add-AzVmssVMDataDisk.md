### Example 1: The first command gets an existing managed disk.
```powershell
PS C:\> Add-AzVmssVMDataDisk -CreateOption Attach -DiskSizeInGB 10 -Lun 0 -ManagedDiskId $disk.Id -StorageAccountType Standard_LRS -VirtualMachineScaleSetVM $VmssVM
```

