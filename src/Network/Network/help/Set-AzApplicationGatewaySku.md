### Example 1: The first command gets the application gateway named ApplicationGateway01 that belongs to the resource group named ResourceGroup01, and stores it in the $AppGw variable.
```powershell
PS C:\> Set-AzApplicationGatewaySku -ApplicationGateway $AppGw -Capacity 2 -Name Standard_Small -Tier Standard
```

