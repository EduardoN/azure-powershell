### Example 1: Imports an existing valid certificate, containing a private key, into Azure Key Vault.
```powershell
PS C:\> Import-AzKeyVaultCertificate -FilePath {FilePath} -Name ImportCert01 -Password {Password} -VaultName ContosoKV01
```


