### Example 1: The Key Backup operation exports a key from Azure Key Vault in a protected form.
```powershell
PS C:\> Backup-AzKeyVaultKey -DefaultProfile {DefaultProfile} -Force {Force} -Name MyCert -OutputFile {OutputFile} -VaultName MyKeyVault
```


