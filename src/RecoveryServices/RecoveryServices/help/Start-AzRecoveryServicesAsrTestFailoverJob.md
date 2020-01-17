### Example 1: The Start-AzRecoveryServicesAsrTestFailoverJob cmdlet starts test failover of an Azure Site Recovery replication protected item or recovery plan.
```powershell
PS C:\> Start-AzRecoveryServicesAsrTestFailoverJob -AzureVMNetworkId <String> -Direction PrimaryToRecovery -RecoveryPlan $RP
```

