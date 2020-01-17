### Example 1: The first command gets a VMSS by using the Get-AzVmss cmdlet, and then stores it in the $VMSS variable.
```powershell
PS C:\> Remove-AzVmssNetworkInterfaceConfiguration -Name ContosoVmssInterface02 -VirtualMachineScaleSet $VMSS
```

