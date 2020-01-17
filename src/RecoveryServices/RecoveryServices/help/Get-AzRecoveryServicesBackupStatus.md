### Example 1: The command returns null/empty if the specified resource is not protected under any Recovery Services vault in the subscription. 
```powershell
PS C:\> Get-AzRecoveryServicesBackupStatus -Name myAzureVM -ResourceGroupName myAzureVMRG -Type AzureVM
```

