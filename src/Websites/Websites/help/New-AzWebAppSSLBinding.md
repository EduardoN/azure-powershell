### Example 1: The New-AzWebAppSSLBinding cmdlet creates a Secure Socket Layer (SSL) certificate binding for an Azure Web App.
```powershell
PS C:\> New-AzWebAppSSLBinding -Name www.contoso.com -ResourceGroupName ContosoResourceGroup -SslState Disabled -Thumbprint E3A38EBA60CAA1C162785A2E1C44A15AD450199C3 -WebAppName ContosoWebApp
```

