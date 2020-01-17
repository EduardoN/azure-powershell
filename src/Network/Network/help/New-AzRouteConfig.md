### Example 1: The first command creates a route named Route07, and then stores it in the $Route variable.
```powershell
PS C:\> New-AzRouteConfig -AddressPrefix 10.1.0.0/16 -Name Route07 -NextHopType VnetLocal
```

