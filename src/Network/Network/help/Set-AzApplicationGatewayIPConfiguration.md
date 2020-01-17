### Example 1: The Set-AzApplicationGatewayIPConfiguration cmdlet modifies an IP configuration.
```powershell
PS C:\> Set-AzApplicationGatewayIPConfiguration -ApplicationGateway $AppGw -Name AppgwSubnet01 -SubnetId $Vnet.Subnets[0].Id
```

