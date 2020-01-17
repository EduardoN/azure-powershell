### Example 1: The Undo-AzRecoveryServicesBackupItemDeletion cmdlet rehydrates a soft-deleted item.
```powershell
PS C:\> Undo-AzRecoveryServicesBackupItemDeletion -Force  -Item $PI[0] -VaultId $vault.ID
```

