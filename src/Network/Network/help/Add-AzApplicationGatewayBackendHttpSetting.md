### Example 1: The Add-AzApplicationGatewayBackendHttpSetting cmdlet adds back-end HTTP settings to an application gateway.
```powershell
PS C:\> Add-AzApplicationGatewayBackendHttpSetting -ApplicationGateway $AppGw -AuthenticationCertificates {AuthenticationCertificates} -CookieBasedAffinity Enabled -Name Setting02 -PickHostNameFromBackendAddress  -Port 88 -Probe $probe -Protocol Http
```

