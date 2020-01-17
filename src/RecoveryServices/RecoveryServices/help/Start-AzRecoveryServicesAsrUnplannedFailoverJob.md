### Example 1: The Start-AzRecoveryServicesAsrUnplannedFailoverJob cmdlet starts unplanned failover of an Azure Site Recovery replication protected item or recovery plan.
```powershell
PS C:\> Start-AzRecoveryServicesAsrUnplannedFailoverJob -Direction PrimaryToRecovery -RecoveryPoint $rp[0] -ReplicationProtectedItem $ReplicationProtectedItem
```

