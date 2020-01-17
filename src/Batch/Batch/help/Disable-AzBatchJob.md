### Example 1: This command disables the job that has the ID Job-000001.
```powershell
PS C:\> Disable-AzBatchJob -BatchContext $Context -DisableJobOption Requeue -Id Job-000001
```

