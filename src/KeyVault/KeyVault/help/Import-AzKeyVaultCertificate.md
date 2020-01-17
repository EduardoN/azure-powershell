### Example 1: The first command uses the ConvertTo-SecureString cmdlet to create a secure password, and then
```powershell
PS C:\> Import-AzKeyVaultCertificate -FilePath C:\Users\contosoUser\Desktop\import.pfx -Name ImportCert01 -Password $Password -VaultName ContosoKV01
```

