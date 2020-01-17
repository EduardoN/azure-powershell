### Example 1: The Set-AzVmss cmdlet sets specific actions on the Virtual Machine Scale Set (VMSS).
```powershell
PS C:\> Set-AzVmss -InstanceId $ID -Reimage  -ResourceGroupName ContosoGroup -TempDisk  -VMScaleSetName ContosoVMSS
```

