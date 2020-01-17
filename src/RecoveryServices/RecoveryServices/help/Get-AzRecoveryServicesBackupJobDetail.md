### Example 1: The first command gets an array of failed jobs in the vault, and then stores them in the $Jobs array.
```powershell
PS C:\> Get-AzRecoveryServicesBackupJobDetail -Job $Jobs[0] -VaultId $vault.ID
```

