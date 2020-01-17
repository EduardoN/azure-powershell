### Example 1: The first command gets the application gateway and stores it in the $AppGw variable.
```powershell
PS C:\> Add-AzApplicationGatewayRequestRoutingRule -ApplicationGateway $AppGw -BackendAddressPool $Pool -BackendHttpSettings $Setting -HttpListener $Listener -Name Rule01 -RuleType Basic
```

