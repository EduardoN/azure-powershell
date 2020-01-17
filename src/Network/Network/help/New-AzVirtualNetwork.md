### Example 1: This example creates a virtual network with two subnets. First, a new resource group is created in
```powershell
PS C:\> New-AzVirtualNetwork -AddressPrefix $VnetAddressPrefix -Location $LocationName -Name $NetworkName -ResourceGroupName $ResourceGroupName -Subnet $SingleSubnet
```

