### Example 1: The New-AzApplicationGatewayBackendHttpSetting cmdlet creates back-end HTTP settings for an application gateway.
```powershell
PS C:\> New-AzApplicationGatewayBackendHttpSetting -CookieBasedAffinity Enabled -Name Setting01 -Port 80 -Protocol Http -RequestTimeout {RequestTimeout}
```

