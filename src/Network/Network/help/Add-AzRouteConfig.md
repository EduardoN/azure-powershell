### Example 1: The first command gets a route table named RouteTable01 by using the Get-AzRouteTable cmdlet.
```powershell
PS C:\> Add-AzRouteConfig -AddressPrefix 10.3.0.0/16 -Name Route13 -NextHopType VnetLocal -RouteTable $RouteTable
```

