### Example 1: The first command gets an application gateway named appGwName and stores it in $appgw variable.
```powershell
PS C:\> Add-AzApplicationGatewayUrlPathMapConfig -ApplicationGateway $Gateway -DefaultBackendAddressPool $AddressPool -DefaultBackendHttpSettings $HttpSettings -Name ContosoUrlPathMap -PathRules $PathRuleConfig
```

