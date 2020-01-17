### Example 1: The Get-AzRecoveryServicesBackupRecoveryPoint cmdlet gets the recovery points for a backed up Azure Backup item.
```powershell
PS C:\> Get-AzRecoveryServicesBackupRecoveryPoint -Item $BackupItem -VaultId $vault.ID
```

