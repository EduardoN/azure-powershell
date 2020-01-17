### Example 1: The Remove-AzRecoveryServicesBackupProtectionPolicy cmdlet deletes backup policies for a vault.
```powershell
PS C:\> Remove-AzRecoveryServicesBackupProtectionPolicy -Confirm  -Force  -Policy $Pol -VaultId $vault.ID
```

