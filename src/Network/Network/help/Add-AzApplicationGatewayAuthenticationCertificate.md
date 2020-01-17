### Example 1: The first command gets an application gateway named appGwName and stores it in $appgw variable.
```powershell
PS C:\> Add-AzApplicationGatewayAuthenticationCertificate -ApplicationGateway $appgw -CertificateFile C:\cert.cer -Name cert01
```

