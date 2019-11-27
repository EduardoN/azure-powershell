### Example 1: Creates or updates a service namespace.
```powershell
PS C:\> Set-AzServiceBusNamespace -DefaultProfile {DefaultProfile} -Location westus -Name SB-Example1 -ResourceGroupName MyResourceGroup -SkuCapacity 0 -SkuName Premium -Tag @{Tag2=Tag2Value}
```

