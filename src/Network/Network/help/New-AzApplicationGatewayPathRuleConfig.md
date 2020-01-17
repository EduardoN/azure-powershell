### Example 1: These commands create a new application gateway path rule and then use the Add-AzApplicationGatewayUrlPathMapConfig cmdlet to assign that rule to an application gateway.
```powershell
PS C:\> New-AzApplicationGatewayPathRuleConfig -BackendAddressPool $AddressPool -BackendHttpSettings $HttpSettings -Name base -Paths /base
```

