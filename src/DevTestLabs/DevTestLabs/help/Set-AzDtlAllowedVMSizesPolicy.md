### Example 1: The Set-AzDtlAllowedVMSizesPolicy cmdlet sets the allowed virtual machine sizes policy, which specifies a list of virtual machine sizes allowed in a lab.
```powershell
PS C:\> Set-AzDtlAllowedVMSizesPolicy -Enable  -LabName {LabName} -ResourceGroupName MyResourceGroup -VmSizes {VmSizes}
```

