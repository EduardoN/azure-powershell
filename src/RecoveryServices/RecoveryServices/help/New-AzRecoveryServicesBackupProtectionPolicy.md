### Example 1: The New-AzRecoveryServicesBackupProtectionPolicy cmdlet creates a Backup protection policy in a vault.
```powershell
PS C:\> New-AzRecoveryServicesBackupProtectionPolicy -Name NewPolicy -RetentionPolicy $RetPol -SchedulePolicy $SchPol -VaultId $vault.ID -WorkloadType AzureVM
```

