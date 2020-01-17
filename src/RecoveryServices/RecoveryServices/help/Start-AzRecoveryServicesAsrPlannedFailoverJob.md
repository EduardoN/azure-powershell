### Example 1: The Start-AzRecoveryServicesAsrPlannedFailoverJob cmdlet starts a planned failover for an Azure Site Recovery replication protected item or recovery plan.
```powershell
PS C:\> Start-AzRecoveryServicesAsrPlannedFailoverJob -Direction PrimaryToRecovery -Optimize {Optimize} -ReplicationProtectedItem $ReplicationProtectedItem
```

