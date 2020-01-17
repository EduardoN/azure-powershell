### Example 1: The Add-AzTrafficManagerIpAddressRange cmdlet adds an IP address range to a local Azure Traffic Manager endpoint object.
```powershell
PS C:\> Add-AzTrafficManagerIpAddressRange -First 1.2.3.4 -Last 12.13.14.31 -TrafficManagerEndpoint $TrafficManagerEndpoint
```

