### Example 1: The Get-AzExpressRouteCircuitARPTable cmdlet retrieves the ARP table from both interfaces
```powershell
PS C:\> Get-AzExpressRouteCircuitARPTable -DevicePath Primary -ExpressRouteCircuitName $CircuitName -PeeringType AzurePrivatePeering -ResourceGroupName $RG
```

