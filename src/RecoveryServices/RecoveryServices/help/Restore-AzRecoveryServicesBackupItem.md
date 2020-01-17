### Example 1: The Restore-AzRecoveryServicesBackupItem cmdlet restores the data and configuration for an Azure Backup item to a specified recovery point.
```powershell
PS C:\> Restore-AzRecoveryServicesBackupItem -VaultId $vault.ID -WLRecoveryConfig {WLRecoveryConfig}
```

