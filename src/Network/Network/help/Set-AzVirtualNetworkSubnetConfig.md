### Example 1: This example creates a resource group with one virtual network containing just one 
```powershell
PS C:\> Set-AzVirtualNetworkSubnetConfig -AddressPrefix 10.0.3.0/23 -Name frontendSubnet -NetworkSecurityGroup $networkSecurityGroup -VirtualNetwork $virtualNetwork
```

