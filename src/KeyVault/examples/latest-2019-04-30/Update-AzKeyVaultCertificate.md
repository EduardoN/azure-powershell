### Example 1: The UpdateCertificate operation applies the specified update on the given certificate; the only elements updated are the certificate's attributes.
```powershell
PS C:\> Update-AzKeyVaultCertificate -Confirm  -Enable {Enable} -Name TestCert01 -VaultName ContosoKV01 -Version {Version}
```

