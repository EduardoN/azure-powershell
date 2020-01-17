### Example 1: The Add-AzTrafficManagerEndpointConfig cmdlet adds an endpoint to a local Azure Traffic Manager profile object.
```powershell
PS C:\> Add-AzTrafficManagerEndpointConfig -EndpointLocation North Europe -EndpointName contoso -EndpointStatus Enabled -Target www.contoso.com -TrafficManagerProfile $TrafficManagerProfile -Type AzureEndpoints
```

