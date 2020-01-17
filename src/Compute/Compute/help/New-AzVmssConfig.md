### Example 1: The New-AzVmssConfig cmdlet creates a configurable local Virtual Manager Scale Set (VMSS)
```powershell
PS C:\> New-AzVmssConfig -Location $Loc -Overprovision False -SkuCapacity 2 -SkuName Standard_A0 -UpgradePolicyMode Automatic
```

