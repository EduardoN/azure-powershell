### Example 1: The first command creates a public IP address object and stores it in the $PublicIp variable.
```powershell
PS C:\> Set-AzApplicationGatewayFrontendIPConfig -ApplicationGateway $AppGw -Name FrontEndIp01 -PublicIPAddress $PublicIp
```

