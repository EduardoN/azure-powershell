### Example 1: This example creates a Firewall attached to virtual network "vnet" in the same resource group as the firewall.
```powershell
PS C:\> New-AzFirewall -Location centralus -Name AzureFirewall -PublicIpAddress $pip -ResourceGroupName $rgName -VirtualNetwork $vnet
```

