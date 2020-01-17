### Example 1: The first command gets the application gateway named ApplicationGateway01 and stores it in the $AppGw variable.
```powershell
PS C:\> Set-AzApplicationGatewayRequestRoutingRule -ApplicationGateway $AppGw -BackendAddressPool $Pool -BackendHttpSettings $Setting -HttpListener $Listener -Name Rule01 -RuleType Basic
```

