### Example 1: The first command gets the application gateway named appGwName and stores the result in the $appgw variable.
```powershell
PS C:\> Set-AzApplicationGatewayAuthenticationCertificate -ApplicationGateway $appgw -CertificateFile C:\cert2.cer -Name cert01
```

