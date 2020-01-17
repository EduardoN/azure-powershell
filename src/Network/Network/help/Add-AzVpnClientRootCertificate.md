### Example 1: This example adds a client root certificate to a virtual gateway named ContosoVirtualGateway.
```powershell
PS C:\> Add-AzVpnClientRootCertificate -PublicCertData $CertificateText -ResourceGroupName ContosoResourceGroup -VirtualNetworkGatewayName ContosoVirtualGateway -VpnClientRootCertificateName ContosoClientRootCertificate
```

