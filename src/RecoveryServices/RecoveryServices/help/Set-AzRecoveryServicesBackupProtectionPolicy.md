### Example 1: The Set-AzBackupProtectionPolicy cmdlet modifies an existing Azure Backup protection policy.
```powershell
PS C:\> Set-AzRecoveryServicesBackupProtectionPolicy -Policy $Pol -RetentionPolicy $RetPol -SchedulePolicy $SchPol -VaultId $vault.ID
```

