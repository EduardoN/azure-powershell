### Example 1: The Backup-AzKeyVaultKey cmdlet backs up a specified key in a key vault by downloading it and storing it in a file.
```powershell
PS C:\> Backup-AzKeyVaultKey -DefaultProfile {DefaultProfile} -Force  -Name MyCert -OutputFile C:\Backup.blob -VaultName MyKeyVault
```

