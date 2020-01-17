### Example 1: The first command gets the application gateway named ApplicationGateway01 in the resource group named ResourceGroup01, and stores it in the $AppGw variable.
```powershell
PS C:\> Set-AzApplicationGatewayBackendAddressPool -ApplicationGateway $AppGw -BackendIPAddresses 10.10.10.10, -Name Pool02
```

