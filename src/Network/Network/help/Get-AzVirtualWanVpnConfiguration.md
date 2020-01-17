### Example 1: Gets the Vpn configuration for a subset of VpnSites connected to this WAN via VpnConnections. Uploads the generated Vpn
```powershell
PS C:\> Get-AzVirtualWanVpnConfiguration -Name cert01 -ResourceGroupName MyResourceGroup -StorageSasUrl SignedSasUrl -VpnSite $vpnSitesForConfig
```

