### Example 1: The New-AzRecoveryServicesAsrPolicy cmdlet creates an Azure Site Recovery replication policy.
```powershell
PS C:\> New-AzRecoveryServicesAsrPolicy -ApplicationConsistentSnapshotFrequencyInHours 5 -AzureToAzure  -Name $policyName1 -RecoveryPointRetentionInHours 20
```

