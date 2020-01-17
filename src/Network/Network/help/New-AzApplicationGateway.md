### Example 1: The New-AzApplicationGateway cmdlet creates an Azure application gateway.
```powershell
PS C:\> New-AzApplicationGateway -BackendAddressPools $Pool -BackendHttpSettingsCollection $PoolSetting -FrontendIPConfigurations {FrontendIPConfigurations} -FrontendPorts $FrontEndPort -GatewayIPConfigurations <PSApplicationGatewayIPConfiguration[]> -HttpListeners $Listener -Location West US -Name $appgwName -RequestRoutingRules $Rule -ResourceGroupName $rgname -Sku $Sku
```

