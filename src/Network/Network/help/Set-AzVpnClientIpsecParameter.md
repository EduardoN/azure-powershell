### Example 1: This example sets custom vpn ipsec policy to existing virtual network gateway named ContosoVirtualGateway from Resource group named ContosoResourceGroup.
```powershell
PS C:\> Set-AzVpnClientIpsecParameter -ResourceGroupName $rgname -VirtualNetworkGatewayName $rname -VpnClientIPsecParameter $vpnclientipsecparams
```

