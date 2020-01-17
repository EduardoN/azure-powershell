### Example 1: The New-AzRecoveryServicesAsrReplicationProtectedItem cmdlet creates a new replication protected item.
```powershell
PS C:\> New-AzRecoveryServicesAsrReplicationProtectedItem -AzureToAzure  -AzureToAzureDiskReplicationConfiguration $disk1,$disk2 -AzureVmId $vmId -Name $VM.Name -ProtectionContainerMapping $ProtectionContainerMapping -RecoveryResourceGroupId $RecoveryResourceGroupId
```

