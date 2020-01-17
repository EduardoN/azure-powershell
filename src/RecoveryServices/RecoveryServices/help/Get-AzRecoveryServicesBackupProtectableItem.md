### Example 1: The Get-AzRecoveryServicesBackupProtectableItem cmdlet gets the protectable items in a container or a value in Azure Backup and the protection status of the items.
```powershell
PS C:\> Get-AzRecoveryServicesBackupProtectableItem -ItemType SQLDataBase -Name V2VM -ServerName {ServerName} -VaultId $vault.ID -WorkloadType AzureVM
```

