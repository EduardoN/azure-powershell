### Example 1: The Get-AzRecoveryServicesBackupItem cmdlet gets the items in a container or a value in Azure Backup and the protection status of the items.
```powershell
PS C:\> Get-AzRecoveryServicesBackupItem -Container $Cont[0] -VaultId $vault.ID -WorkloadType AzureVM
```

