### Example 1: The first command gets the Azure endpoint named contoso from the profile named ContosoProfile in the resource group named ResourceGroup11, and then stores that object in the $TrafficManagerEndpoint variable.
```powershell
PS C:\> Remove-AzTrafficManagerIpAddressRange -First 1.2.3.4 -TrafficManagerEndpoint $TrafficManagerEndpoint
```

