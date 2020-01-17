### Example 1: Creates a new Azure VpnSite resource. This is an RM representation of customer branches that are uploaded to Azure
```powershell
PS C:\> New-AzVpnSite -AddressSpace $vpnSiteAddressSpaces -DeviceModel SomeDevice -DeviceVendor SomeDeviceVendor -IpAddress 1.2.3.4 -LinkSpeedInMbps 10 -Location East US -Name testVpnSite -ResourceGroupName nonlinkSite -VirtualWanName <String> -VirtualWanResourceGroupName <String>
```

