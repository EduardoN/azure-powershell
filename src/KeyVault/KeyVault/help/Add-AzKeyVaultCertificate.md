### Example 1: The first command uses the New-AzKeyVaultCertificatePolicy cmdlet to create a certificate policy, and then stores it in the $Policy variable.
```powershell
PS C:\> Add-AzKeyVaultCertificate -CertificatePolicy $Policy -Name TestCert01 -VaultName ContosoKV01
```

