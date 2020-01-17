### Example 1: The Add-AzVpnClientRevokedCertificate cmdlet assigns a client-revocation certificate to a virtual network gateway.
```powershell
PS C:\> Add-AzVpnClientRevokedCertificate -ResourceGroupName ContosoResourceGroup -Thumbprint E3A38EBA60CAA1C162785A2E1C44A15AD450199C3 -VirtualNetworkGatewayName ContosoVirtualNetwork -VpnClientRevokedCertificateName ContosoRevokedClientCertificate-Thumbprint
```

