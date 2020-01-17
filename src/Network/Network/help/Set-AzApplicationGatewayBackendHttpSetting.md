### Example 1: The Set-AzApplicationGatewayBackendHttpSetting cmdlet updates the back-end Hypertext Transfer Protocol (HTTP) settings for an Azure application gateway.
```powershell
PS C:\> Set-AzApplicationGatewayBackendHttpSetting -ApplicationGateway $AppGw -AuthenticationCertificates {AuthenticationCertificates} -CookieBasedAffinity Enabled -Name Setting02 -PickHostNameFromBackendAddress  -Port 88 -Probe $probe -Protocol Http
```

