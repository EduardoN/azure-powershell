### Example 1: The above will create a resource group, Virtual WAN, Virtual Network, Virtual Hub and a VpnSite in West US in "testRG" resource group in Azure. 
```powershell
PS C:\> Remove-AzVpnConnection -Name testConnection -ParentResourceName $vpnGateway.Name -ResourceGroupName $vpnGateway.ResourceGroupName
```

