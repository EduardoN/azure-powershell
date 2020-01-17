### Example 1: This example first creates a resource group as a container of the resources to be created. It then creates a subnet configuration and uses it to create a virtual network. The 
```powershell
PS C:\> Add-AzVirtualNetworkSubnetConfig -AddressPrefix 10.0.2.0/24 -Name backendSubnet -VirtualNetwork $virtualNetwork
```

