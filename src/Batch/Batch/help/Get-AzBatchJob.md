### Example 1: The Get-AzBatchJob cmdlet gets the Azure Batch jobs for the Batch account specified by the BatchAccountContext parameter.
```powershell
PS C:\> Get-AzBatchJob -BatchContext $Context -Filter state eq 'active' -MaxCount {MaxCount} -Select jobPreparationTaskExecutionInfo
```

