### Example 1: The Backup-AzRecoveryServicesBackupItem cmdlet starts a backup for a protected Azure Backup item that is not tied to the backup schedule.
```powershell
PS C:\> Backup-AzRecoveryServicesBackupItem -ExpiryDateTimeUTC {ExpiryDateTimeUTC} -Item $Item -VaultId $vault.ID
```

