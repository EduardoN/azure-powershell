### Example 1: The Disable-AzRecoveryServicesBackupProtection cmdlet disables protection for an Azure Backup-protected item.
```powershell
PS C:\> Disable-AzRecoveryServicesBackupProtection -Force  -Item $PI[0] -VaultId $vault.ID
```

