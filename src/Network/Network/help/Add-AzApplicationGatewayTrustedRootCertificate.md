### Example 1: The first command gets the application gateway and stores it in $gw variable.
```powershell
PS C:\> Add-AzApplicationGatewayTrustedRootCertificate -ApplicationGateway $gw -CertificateFile .\rootCA.cer -Name $certName
```

