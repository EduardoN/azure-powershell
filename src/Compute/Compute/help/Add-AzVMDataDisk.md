### Example 1: The Add-AzVMDataDisk cmdlet adds a data disk to a virtual machine.
```powershell
PS C:\> Add-AzVMDataDisk -CreateOption Attach -Lun 0 -ManagedDiskId $disk.Id -Name DataDisk1 -VM $VirtualMachine
```

