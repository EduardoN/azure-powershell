### Example 1: The Backup-AzKeyVaultSecret cmdlet backs up a specified secret in a key vault by downloading it and storing it in a file.
```powershell
PS C:\> Backup-AzKeyVaultSecret -DefaultProfile {DefaultProfile} -Force  -Name MySecret -OutputFile C:\Backup.blob -VaultName MyKeyVault
```

